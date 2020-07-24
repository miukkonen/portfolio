---
layout: front
title: Portfolio | Mikko Oikkonen
---



<section class="hero is-fullheight-with-navbar" style="background: #ffffff url('img/coffee-background-1600.jpg') no-repeat scroll center 40%; background-size: cover;">

  
  <div class="hero-body with-bg-opacity">

	<div class="container has-text-centered" style="max-width: 765px;">
      	
    	<div class="content">

	      	<img src="img/oma39b.jpg" style="width: 280px; border-radius: 290486px;">
			
	      	<h1 class="title is-1">Mikko Oikkonen</h1>
	      	
	      	<i class="fas fa-coffee fa-3x"></i>
	      	<i class="fas fa-coffee fa-3x"></i>
	      	<i class="fas fa-coffee fa-3x"></i>
	      	
	      	
	      	<h2 class="subtitle is-3">Työnantajan paras ystävä</h2>
	    
	      	<p class="subtitle is-5">

	      		Olen Mikko Oikkonen, ohjelmistotuotannon ammattilainen Tampereelta. Tämä sivu on portfolioni, jossa esittelen työkokemustani ja projektejani.
	      	
	      	</p>

			<p class="subtitle is-5">

		      	Olen innostunut uusista haasteista ja uuden oppimisesta. Haluaisin mukaan innovatiiviseen tiimiin jossa kehittyisin entistä taitavammaksi ohjelmistokehittäjäksi.

			</p>

			<p class="subtitle is-5">

				Kutsu minut työhaastatteluun!

			</p>


	      	<br />

	      	<a href="#yhteystiedot" class="button is-large is-info">Kutsu Mikko työhaastatteluun</a>

	    </div>


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


  



<section id="projektit" class="hero is-primary is-fullheight" style="/*background: #ffffff url('img/code-background-1600.jpg') no-repeat scroll center 40%; background-size: cover;*/ background: #979fa4;">

  
	<div class="hero-body with-bg-opacity has-text-centered">


		<div class="content" style="max-width: 765px; margin: auto; color: black;">

	      	<h1 class="title">Projektit</h1>
    	  	<h2 class="subtitle">Koodiprojektejani on Githubissa näkyvissä ja niiden avulla voi tutustua tekemisiini...</h2>

			
    	  	{% assign visible_projects = site.projects | where: "show", "true" %}

			{% for project in visible_projects %}

				<article class="notification is-info-i" style="background: white;">

					<p class="title" style="color: #23a2c7">{{ project.title }}</p>
					<p class="subtitle" style="color: #23a2c7">{{ project.subtitle }}</p>
					{{ project.content }}
					<a href="{{ project.link }}">{{ project.link }}</a>

				</article>

			{% endfor %}      	


   	 	</div>

	</div>

</section>












<section class="section heroi is-fullheighti" id="features">


	<div class="hero-bodyi">


		<div class="columns">

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-toolbox fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Monipuolinen kokemus</h3>
		    <p>Minulla on monipuolista kokemusta kaikista ohjelmistojen elinkaaren vaiheista alkaen asiakkaan ensimmäisestä sähköpostista aina ohjelmien alasajoon saakka.</p>
		  </div>

		  <div class="column notificationi is-primary has-text-centered">
		    <i class="fas fa-users fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Tiimi-yhteensopiva</h3>
		    <p>Viihdyn parhaiten intensiivisissä tiimeissä mutta osaan työskennellä myös yksin oma-aloitteisesti.</p>
		  </div>


		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-file fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Projektit hallinnassa</h3>
		    <p>Olen ollut mukana projekteissa joissa on käytetty eri tyylisiä projektinhallintamenetelmiä: Vesiputous - Agile - Lean</p>
		  </div>

		</div>


		<div class="columns">



		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-book-open fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Dokumentointi</h3>
		    <p>Pidän dokumentoinnista ja pyrin siihen että joku muu voi jatkaa siitä mihin jäin tai pystyn jatkamaan jos palaan koodin pariin vasta vuoden tauon jälkeen.</p>

		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-unlock fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Ratkaisukeskeinen</h3>
		    <p>Keskityn ongelmien ratkaisemiseen, en syyllisten etsimiseen.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-rocket fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Lisäarvoa tuottava</h3>
		    <p>Kirjoittamaani koodia on tälläkin hetkellä ajossa tuotantoympäristöissä tuottamassa lisäarvoa asiakkaille.</p>
		  </div>


		</div>



		<div class="columns">


		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-comments fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Kommunikoiva</h3>
		    <p>Pyrin selkeään kommunikointiin ja kirjallinen ilmaisuni on sujuvaa. Minulla on kokemusta myös asiakaspalvelutöistä.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		    <i class="fas fa-upload fa-4x" style="color: #23a2c7;"></i>
		    <h3 class="title">Teknologianeutraali</h3>
		    <p>Minulla on tällä hetkellä tuotannossa pyörimässä koodia jotka on toteutettu seuraavilla teknologioilla: C++, DotNet/C#, PHP, JavaScript, Python.</p>
		  </div>

		  <div class="column notificationi is-primary-i has-text-centered">
		  	<i class="fas fa-bicycle fa-4x" style="color: #23a2c7;"></i>
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











<section class="section" id="blogi">


	<div class="columns is-centered">

		<div class="column is-half">
		  
		      
		      	<h1 class="title">Ammatillinen blogi</h1>
		      	<h2 class="subtitle">Uusimmat kirjoitukset</h2>
		    

		      	<div class="content">

					{% for post in site.posts limit:2 %}

						<h2 class="title">{{ post.title }}</h2>
						<p class="subtitle">Kirjoitettu: {{ post.date | date: '%d.%m.%Y' }}</p>

						<p>{{ post.excerpt }}</p>

						<a class="" href="{{ post.url }}">Näytä kirjoitus</a>

					{% endfor %}      	

				</div>


				<a class="button is-large is-info" href="/blogi">Näytä kaikki blogikirjoitukset</a>


		</div>

	</div>

  
</section>










