---
layout: post
title: "Kokemuksia virtualisoinnin iloista"
date: 2016-09-08
published: false
---

Hiljattain olin mukana erään asiakkaan projektissa, jossa virtualisoitiin vanhoja linux ja windows palvelimia.

Asiakkaalla oli konehuoneessaan useita vanhoja palvelimenrouskuja raksuttamassa ja pyörittämässä vanhoja Ubuntu-asennuksia, joiden päivämäärät olivat jo aikaa sitten menneet ja vanhoja windows server asennuksia. Koneet olivat ajalta, jolloin käyttikset asennettiin todelliselle raudalle. Hankimme tilalle kaksi uutta pöytäkonetta ja pistimme sinne Virtualboxin Ubuntu-linuksiin pyörimään niin että kerralla saimme vapautettua kuusi vanhaa rouskupalvelinta ansaitsemilleen eläkepäiville. Asentelin ensin ubuntu asennukset uusimpiin versioihinsa. Osa ubuntuista päivittyi pienen säädön jälkeen uusimpaan julkaisuun, mutta vanhimpia en saanut enää päivitettyä vaan jouduin asentamaan ne tyhjästä ja Ubuntu 10.04 -> 12.04 -> 16.04.

Kyseessä on pk-yritys, joka tarvitsee palvelimia omiin sisäisiin puuhiinsa, muttei tarvitse mitään massiivisia super-palvelimia, vaan ihan tavallinen verkkokaupasta hankittu pelikone-pöytäkone riittää tähän tarkoitukseen.

Kaksi uutta palvelinta toimivat toistensa varapalvelimina siten, että toisella pyörii kolme virtuaalista palvelinta ja toisella kolme. Jos toinen kone poksahtaa niin toista voi käyttää varakoneena ja kun virtuaalisista palvelimista on muistanut ottanut riittävästi klooneja niin ne saa äkkiä polkaistua käyntiin toisella koneella, koska ympäristöt ovat identtiset.

