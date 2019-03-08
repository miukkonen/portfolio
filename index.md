---
layout: front
title: Portfolio | Mikko Oikkonen
---



<section class="hero is-primary is-fullheight-with-navbar" style="background: #ffffff url('img/coffee-background-1600.jpg') no-repeat scroll center 40%; background-size: cover;">

  
  <div class="hero-body with-bg-opacity">

	<div class="container has-text-centered" style="max-width: 765px;">
      	
      	<img src="img/oma39b.jpg" style="width: 280px; border-radius: 290486px;">
		
      	<h1 class="title is-1" style="color: #363636;">Mikko Oikkonen</h1>
      	<h2 class="subtitle is-3" style="color: #363636;">Työnantajan paras ystävä</h2>
    
      	<p style="color: #363636;">

      		Olen Mikko Oikkonen, ohjelmistotuotannon ammattilainen Tampereelta. Tämä sivu on portfolioni, jossa esittelen työkokemustani ja projektejani. Olen innostunut uusista haasteista ja uuden oppimisesta. Haluaisin mukaan innovatiiviseen tiimiin jossa kehittyisin entistä taitavammaksi ohjelmistokehittäjäksi. Kutsu minut työhaastatteluun!

		</p>


      	<br />

      	<a href="#yhteystiedot" class="button is-large is-info">Kutsu Mikko työhaastatteluun</a>


    </div>
  
  </div>




</section>




<section class="section" id="kokemus">


	<div class="columns is-centered">

		<div class="column is-half">
		  
		      
		      	<h1 class="title">Työkokemus</h1>
		      	<h2 class="subtitle">Viimeisin työkokemus ohjelmistoalalta</h2>
		    

		      	<div class="content">

					{% assign jobs_in_order = site.jobs | sort: "order" %}

					{% for job in jobs_in_order %}

						<h3 class="subtitle">{{ job.title }}</h3>
						<h4 class="subtitle">{{ job.subtitle }}</h4>
						{{ job.content }}

					{% endfor %}      	

				</div>

		</div>

	</div>

  
</section>


  



<section id="projektit" class="hero is-primary is-fullheight" style="background: #ffffff url('img/code-background-1600.jpg') no-repeat scroll center 40%; background-size: cover;">

  
	<div class="hero-body with-bg-opacity has-text-centered">


		<div class="content" style="max-width: 765px; margin: auto; color: black;">

	      	<h1 class="title" style="color: #506C7B;">Projektit</h1>
    	  	<h2 class="subtitle" style="color: #506C7B;">Koodiprojektejani on Githubissa näkyvissä ja niiden avulla voi tutustua tekemisiini...</h2>

			
    	  	{% assign visible_projects = site.projects | where: "show", "true" %}

			{% for project in visible_projects %}

				<article class="notification is-info">

				<p class="subtitle">{{ project.title }}</p>
				<p class="subtitle">{{ project.subtitle }}</p>
				{{ project.content }}
				<a href="{{ project.link }}">{{ project.link }}</a>

				</article>

			{% endfor %}      	


   	 	</div>

	</div>

</section>





<section class="section heroi is-fullheighti">


	<div class="hero-bodyi">


		<div class="columns">

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-toolbox fa-4x"></i>
		    <h3 class="title">Monipuolinen kokemus</h3>
		    <p>Minulla on monipuolista kokemusta kaikista ohjelmistojen elinkaaren vaiheista alkaen asiakkaan ensimmäisestä sähköpostista aina ohjelmien alasajoon saakka.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-users fa-4x"></i>
		    <h3 class="title">Tiimi-yhteensopiva</h3>
		    <p>Viihdyn parhaiten intensiivisissä tiimeissä mutta osaan työskennellä myös yksin oma-aloitteisesti.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-question-circle fa-4x"></i>
		    <h3 class="title">Ympäristö-agnostinen</h3>
		    <p>Kokemusta kaikista työpöytäympäristöistä Windows - Linux - Mac, mutta koen olevani kotona linuxissa</p>
		  </div>


		</div>


		<div class="columns">

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-file fa-4x"></i>
		    <h3 class="title">Projektit hallinnassa</h3>
		    <p>Olen ollut mukana projekteissa joissa on käytetty eri tyylisiä projektinhallintamenetelmiä: Vesiputous - Agile - Lean</p>
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
		    <i class="fas fa-comments fa-4x"></i>
		    <h3 class="title">Kommunikoiva</h3>
		    <p>Pyrin selkeään kommunikointiin ja kirjallinen ilmaisuni on sujuvaa. Minulla on kokemusta myös asiakaspalvelutöistä.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-upload fa-4x"></i>
		    <h3 class="title">Teknologianeutraali</h3>
		    <p>Minulla on tällä hetkellä tuotannossa pyörimässä koodia jotka on toteutettu seuraavilla teknologioilla: C++, DotNet/C#, PHP, JavaScript, Python.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		  	<i class="fas fa-bicycle fa-4x"></i>
		    <h3 class="title">Ilmastoystävällinen</h3>
		    <p>Kuljen työmatkat polkupyörillä jotka on kierrätetty kaivamalla ne roskiksista ja kunnostamalla uusiokäyttöön.</p>
		  </div>


		</div>




	</div>


</section>





<section class="section hero is-fullheight is-info " id="yhteystiedot">


	<div class="hero-body has-text-centered">

		<div class="container has-text-centered">

			<h1 class="title is-1">Kutsu Mikko haastatteluun!</h1>

			<p>Mikko Oikkonen</p>
			<p>mikko.oikkonen@lowbudget.fi</p>
			<p>+358 40 592 4303</p>

		</div>

	</div>

</section>






