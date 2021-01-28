---
title: 3D Modelling
layout: landing
description: 'I have been learning 3D modelling as a hobby for many years and have used it in a few projects.'
image: assets/images/ARGallery01.png
nav-menu: true
---

<!-- Main assets/images/ar-business-card_urs_01.PNG -->
<div id="main">

<!-- One -->

<section id="one" class="spotlights">
	<section>
		<!-- <a href="generic.html" class="image"> -->
			<img src="{% link assets/images/costume01_small02.jpg %}" alt="" data-position="center center" />
		<!-- </a> -->
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Elephant - low poly model for 3D printing</h3>
				</header>
				<p>A low poly elephant for <a href="https://www.youtube.com/watch?v=G-64TGEd5ds">Mitwy's</a> plant watering reminder.</p>
				<!-- ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul -->
			</div>
		</div>
	</section>

	<section>
		<!-- <a href="generic.html" class="image"> -->
			<img src="{% link assets/images/pic09.jpg %}" alt="" data-position="top center" />
		<!-- </a> -->
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Mountains and caves for Everskye VR demo</h3>
				</header>
				<p>Everskye is a story driven VR adventure game that provides an exhilarating flying experience through spectacular landscapes.</p>
				<!-- ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul -->
			</div>
		</div>
	</section>


	<section>
		<a href="https://santabox.glitch.me/" class="image">
			<img src="{% link assets/images/santabox.png %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Santa</h3>
				</header>
				<p>An animated Santa-in-a-box I created for as an AR Christmas card.</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<section>

	<model-viewer src="{% link assets/models/santabox.glb %}"
								ios-src=""
								alt=""
								autoplay
								shadow-intensity="1"
								camera-controls
								interaction-prompt="auto"
								auto-rotate ar magic-leap>
		<div id="lazy-load-poster" slot="poster"></div>
	</model-viewer>
		<!-- img src="{% link assets/models/santabox.glb %}" alt="" data-position="25% 25%" / -->

	<div class="content">
		<div class="inner">
			<header class="major">
				<h3>Santa</h3>
			</header>
			<p>An animated Santa-in-a-box I created for as an AR Christmas card.</p>
			<ul class="actions">
				<li><a href="generic.html" class="button">Learn more</a></li>
			</ul>
		</div>
	</div>
</section>


</section>


<!-- Three -->


</div>
