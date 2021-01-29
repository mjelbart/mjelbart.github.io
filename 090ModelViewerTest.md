---
title: 3D Modelling
layout: landing
description: 'I have been learning 3D modelling as a hobby for many years and have used it in a few projects.'
image: assets/images/ARGallery01.png
nav-menu: false
show_tile: false

---
<!-- The following libraries and polyfills are recommended to maximize browser support -->
    <!-- NOTE: you must adjust the paths as appropriate for your project -->

    <!-- 🚨 REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
    <script src="https://unpkg.com/@webcomponents/webcomponentsjs@2.1.3/webcomponents-loader.js"></script>

    <!-- 💁 OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
    <script src="https://unpkg.com/intersection-observer@0.5.1/intersection-observer.js"></script>

    <!-- 💁 OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
    <script src="https://unpkg.com/resize-observer-polyfill@1.5.0/dist/ResizeObserver.js"></script>

    <!-- 💁 OPTIONAL: Fullscreen polyfill is needed to fully support AR features -->
    <script src="https://unpkg.com/fullscreen-polyfill@1.0.2/dist/fullscreen.polyfill.js"></script>

    <!-- 💁 OPTIONAL: Include prismatic.js for Magic Leap support -->
    <script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>

    <!-- 💁 OPTIONAL: The :focus-visible polyfill removes the focus ring for some input types -->
    <script src="https://unpkg.com/focus-visible@5.0.2/dist/focus-visible.js" defer></script>

<!-- Main assets/images/ar-business-card_urs_01.PNG -->
<div id="main">

<!-- One -->

<section id="one" class="spotlights">
<section>
<div class="content">
	<div class="inner">
	<model-viewer src="{% link assets/models/santabox.glb %}" data-position="25% 25%" /
								ios-src=""
								alt=""
								autoplay
								shadow-intensity="1"
								camera-controls
								interaction-prompt="auto"
								auto-rotate ar magic-leap>
		<div id="lazy-load-poster" slot="poster"></div>
	</model-viewer>

		</div>
	</div>
</section>

<section>
<section>

<iframe width="560" height="315" src="https://www.youtube.com/embed/3Iog89yVh34" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  <!-- <a href="generic.html" class="image"> -->
    <!-- img src="{% link assets/images/blue512.png %}" alt="" data-position="top center" / -->
  <!-- </a> -->
  <div class="content">
    <div class="inner">
      <header class="major">
        <h3>VR Lab Equipment</h3>
      </header>
      <p>
      Paragraph text.
      </p>
      <!-- ul class="actions">
        <li><a href="generic.html" class="button">Learn more</a></li>
      </ul -->
    </div>
  </div>
</section>
</section>

<!--
  vr lab equipment
  <iframe width="560" height="315" src="https://www.youtube.com/embed/3Iog89yVh34" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
urs costume
<iframe width="560" height="315" src="https://www.youtube.com/embed/QomYoaxt66c" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
-- >

</section>



<!-- Three -->


</div>
