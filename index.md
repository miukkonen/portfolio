---
layout: front
title: Portfolio | Mikko Oikkonen
---



<section class="hero is-primary is-fullheight-with-navbar" style="background: #ffffff url('img/coffee-background.jpg') no-repeat scroll center 40%; background-size: cover;">

  
  <div class="hero-body with-bg-opacity">

	<div class="container has-text-centered" style="max-width: 765px;">
      	
      	<img src="img/oma39b.jpg" style="width: 280px; border-radius: 290486px;">
		
      	<h1 class="title" style="color: #363636;">Mikko Oikkonen</h1>
      	<h2 class="subtitle" style="color: #363636;">Työnantajan paras ystävä</h2>
    
      	<p style="color: #363636;">

      		Olen Mikko Oikkonen, ohjelmistotuotannon ammattilainen Tampereelta. Tämä sivu on portfolioni, jossa esittelen työkokemustani ja projektejani. Olen innostunut uusista haasteista ja uuden oppimisesta. Haluaisin mukaan innovatiiviseen tiimiin jossa kehittyisin entistä taitavammaksi ohjelmistokehittäjäksi. Kutsu minut työhaastatteluun!

		</p>


      	<br />

      	<a href="#yhteystiedot" class="button is-large is-info">Kutsu Mikko työhaastatteluun</a>


    </div>
  
  </div>




</section>








<section id="kokemus" class="hero is-fullheight" style="background: #ffffff;">

  
  <div class="hero-body">

	<div class="container" style="max-width: 765px;">
      
      	<h1 class="title">Työkokemus</h1>
      	<h2 class="subtitle">Viimeisin työkokemus ohjelmistoalalta</h2>
    

      	<div class="content">

			{% for job in site.jobs %}

				<h3 class="subtitle">{{ job.title }}</h3>
				{{ job.content | markdownify }}

			{% endfor %}      	

		</div>


      	<a href="/kokemus" class="button is-large is-success">Näytä lisää</a>

    </div>
  
  </div>

</section>


  



<section class="hero is-primary is-fullheight" style="background: #ffffff url('img/code-background.jpg') no-repeat scroll center 40%; background-size: cover;">

  
	<div class="hero-body with-bg-opacity has-text-centered">


		<div class="content" style="max-width: 765px; margin: auto; color: black;">

	      	<h1 class="title" style="color: #506C7B;">Projektit</h1>
    	  	<h2 class="subtitle" style="color: #506C7B;">Koodiprojektejani on Githubissa näkyvissä ja niiden avulla voi tutustua tekemisiini...</h2>

			<article class="notification is-primary">
				<p class="title is-4">Kukko Kevytyrittäjyyssofta</p>
				<p class="subtitle is-5">Node.js+Vue BackEnd-FrontEnd</p>
				<p>Webbisofta jossa toteutettu suosittujen kevytyrittäjyyspalvelujen perustoiminnallisuuksia. Käyttäjien rekisteröinti, asiakasrekisteri, laskujen luonti, palkkalaskuri, palkat. Käyttäjät voivat muodostaa laskuja asiakkaille ja nostaa itselleen palkkaa maksettujen laskujen perusteella. Palkanlaskijat voivat merkitä laskuja maksetuksi ja merkitä palkkoja maksetuksi. Frontend-koodi vue.js:llä, joka keskustelee backendin kanssa, joka toteutettu Node.js+Adonis.js:llä.</p>
				<a href="#">Lue lisää</a>
			</article>

			<article class="notification is-primary">
				<p class="title is-4">NetvisorClient</p>
				<p class="subtitle is-5">Yhteyspalikka taloushallintaohjelmisto Netvisoriin</p>
				<p>Taloushallinto-ohjelma Netvisorin ohjelmistorajapintaan JavaSkrirptillä toteuttamani clientti, jolla voi siirtää laskuja, asiakkaita, palkansaajia ja palkkoja Netvisorin ohjelmistorajapinnan kautta. Clientti löytyy npm-pakkauksena ja sen voi liittää omaan Node.js -projektiinsa joka halutaan intekroida taloushallintaohjelmisto Netvisorin kanssa.</p>
				<a href="#">Gitpubbiin</a>
			</article>

			<article class="notification is-primary">
				<p class="title is-4">Alerent.fi</p>
				<p class="subtitle is-5">Staattinen nettisivu WordPressillä</p>
				<p>Halpa-autovuokraamo Alerentin sivut on toteutettu WordPressillä. Sivut ovat kuitenkin niin yksinkertaiset, että niiden on turha olla massiivisen sisällönhallintajärjestelmän päällä. Viritin sivut sellaisiksi, että wp:n asennus ja hallintapaneeli on salaisessa paikassa ja aina kun niitä päivitetään (page/post publish) sivut pullautetaan staattiseksi sivuksi alerent.fi -osoitteeseen. Tämä lisää sivujen nopeutta ja tietoturvaa, koska säilönnänhallintaa tarvitaan vain sivujen päivitysvaiheessa, ei joka kerta kun joku sattuu sivuille surffaamaan.</p>
				<a href="https://www.alerent.fi">alerent.fi</a>
			</article>

			<article class="notification is-primary">
				<p class="title is-4">Esittelysivu</p>
				<p class="subtitle is-5">Tämä portfoliosivu Jekyll+Github</p>
				<p>Tämän portfoliosivuston toteutin Jekyllillä staattisena nettisivuna ja se on hostattuna githubissa. Voin päivittää sivua omalla kotikoneellani ja kun pushaan gitpuppiin, sivut automaagisesti päivittyvät. Hostaus on ilmaista. Https on ilmainen. Maksan vain omasta domainista. Käytin Bulma css-kirjastoa sivun toteutuksessa.</p>
				<a href="#">Esittelysivu</a>
			</article>


   	 	</div>

	</div>

</section>





<section class="section heroi is-fullheighti">


	<div class="hero-bodyi">


		<div class="columns">

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-toolbox fa-4x"></i>
		    <h3 class="title">Monipuolinen</h3>
		    <p>Monipuolista kokemusta kaikista ohjelmistojen elinkaaren vaiheista.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-users fa-4x"></i>
		    <h3 class="title">Tiimi-yhteensopiva</h3>
		    <p>Viihdyn parhaiten tiimissä mutta osaan työskennellä myös yksin oma-aloitteisesti.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-question-circle fa-4x"></i>
		    <h3 class="title">Ympäristö-agnostinen</h3>
		    <p>Kokemusta kaikista työpöytäympäristöistä Windows - Linux - MacOs, mutta koen olevani kotona linuxissa</p>
		  </div>


		</div>


		<div class="columns">

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-file fa-4x"></i>
		    <h3 class="title">Projektinhallinta</h3>
		    <p>Kokemusta monista eri tyylisistä projektimenetelmistä: Vesiputous - Agile - Lean</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-unlock fa-4x"></i>
		    <h3 class="title">Ratkaisukeskeinen</h3>
		    <p>Keskityn ongelmien ratkaisemiseen, en syyllisten etsimiseen.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-rocket fa-4x"></i>
		    <h3 class="title">Lisäarvoa tuottava</h3>
		    <p>Kirjoittamaani koodia on tälläkin hetkellä ajossa tuotantoympäristöissä tuottamassa lisäarvoa asiakkaille.</p>
		  </div>


		</div>



		<div class="columns">


		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-upload fa-4x"></i>
		    <h3 class="title">Teknologianeutraali</h3>
		    <p>Minulla on tällä hetkellä tuotannossa pyörimässä koodia jotka on toteutettu seuraavilla ohjelmointikielillä: C++, C#, PHP, JavaScript, Python.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-upload fa-4x"></i>
		    <h3 class="title">Teknologianeutraali</h3>
		    <p>Minulla on tällä hetkellä tuotannossa pyörimässä koodia jotka on toteutettu seuraavilla ohjelmointikielillä: C++, C#, PHP, JavaScript, Python.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		  	<i class="fas fa-bicycle fa-4x"></i>
		    <h3 class="title">Ilmastoystävällinen</h3>
		    <p>Kuljen työmatkat pääasiassa polkupyörillä jotka on löydetty roskiksista ja kunnostettu uusiokäyttöön.</p>
		  </div>


		</div>




	</div>


</section>





<section class="section hero is-fullheight is-info " id="yhteystiedot">


	<div class="hero-body has-text-centered">

		<div class="container has-text-centered">

			<h1 class="title">Kutsu Mikko haastatteluun!</h1>

			<p>Mikko Oikkonen</p>
			<p>mikko.oikkonen@lowbudget.fi</p>
			<p>0405924303</p>

		</div>

	</div>

</section>






