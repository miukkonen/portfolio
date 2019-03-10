---
layout: post
title: "Virtualisoinnin iloista"
subtitle: "Palvelinfarmin korvaaminen virtuaalikoneilla"
date: 2016-09-30
published: true
---

Toteutin hiljattain eräälle asiakkaalle mielenkiintoisen projektin, jossa päivitettiin asiakkaan vanhoja palvelinkoneita virtuaalisiksi palvelimiksi.

Asiakkaalla oli toimistollaan koko joukko erilaisia pikku palvelimia, jotka toimittivat erilaisia virkoja sähköpostipalvelimesta ja versionhallintapalvelimesta monimutkaisempiin tarkoituksiin. Nämä olivat Ubuntu Linux- ja Windows Server -koneita ja ne oli pystytetty aikana, jolloin jokainen palvelin laitettiin kiltisti omalle fyysiselle koneelleen pyörimään.

Koska palvelimet olivat ainoastaan asiakkaan sisäiseen käyttöön eikä niissä ollut vaatimusta suuriin käyttäjämääriin tai massiiviseen laskentatehoon, päätimme lähteä liikkeelle hankkimalla virtuaalialustaksi tavallisia pc-koneita. Hankimme kaksi kotikäyttöön tarkoitettua pc-konetta, joissa oli järeästi muistia ja levytilaa. Ajatuksena oli että olisi kaksi samanlaista konetta, jotka toimisivat toistensa varakoneina. Jos toisesta koneesta hajoaa vaikkapa kovalevy, niin toinen kone voi hoitaa toisen koneen kriittiset tehtävät sillä välin kun odotellaan uutta kovalevyä saapuvaksi.

Koneille viritettiin identtiset XUbuntu-linux asennukset ja linuxin päälle VirtualBox -ohjelma. Nämä olivat niin kutsuttuja virtuaali-isäntäkoneita ja VirtualBoxin avulla luotiin kummallekin isäntäkoneelle useita virtuaalipalvelimia eri tarkoituksiin ja eri käyttöjärjestelmillä.

On myös olemassa VirtualBoxia järeämpiä ratkaisuja jotka eivät tarvitse välttämättä omaa käyttöjärjestelmää alleen vaan toimivat puhtaan raudan päällä, mutta VirtualBox osoittautui riittävän käteväksi ja luotettavaksi ympäristöksi asiakkaan käyttötarkoituksiin. Ubuntu otettiin käyttöön sen takia että se oli tuttu Linux-jakelu asiakkaalle, ei välttämättä kaikkein optimaalisin virtualisointitarkoituksiin.

Virtualisointiprojekti osoittautui erittäin menestyksekkääksi. Asiakkaan "konehuoneeseen" tuli melkoisesti tilaa kun kaksi siistiä pc-konetta korvasi kokonaisen rivistön vanhoja pölyisiä raatoja ja tilan lattialta hävisi melkoinen vyyhti ylimääräisiä sähköjohtoja ja nettipiuhoja.

Fyysistä siisteyttä suurempi helpotus oli virtuaalisen palvelinympäristön helppous. Koneita on helppo muokata, niille on helppo jakaa lisää resursseja, niitä on helppo kloonata ja ottaa varmuuskopioita koko ympäristöstä ja siirtää koneita uusiin ympäristöihin. Isäntäkoneille on helppo pystyttää nopeasti erilaisia kokeilupalvelimia.
