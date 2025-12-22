---
layout: landing
title: Art
description: Enter a world of science illustration, playful creations, and immersive storytelling.
image: assets/images/rightbrain.webp
permalink: /art/
order: 2
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Curating Curiosity</h2>
		</header>
		<p>One common theme runs throughout all of my creations: curiosity. From investigating the intricacies of nature in watercolor to exploring every rabbit hole in an immersive experience, I use art as a tool for discovery. My current projects include:
			<ul>
				<li> Watercolor and graphite designs for singer/songwriter <a href = "https://www.rosesbyothernames.com/">Ilia Rose</a></li>
				<li> Needlefelted dioramas for the <a href = "https://www.sccmod.org/">Santa Cruz Children's Museum of Discovery</a></li>
				<li> Mural-making for local Santa Cruz businesses</li>	
				<li> An interactive play about an AI possessed by a demon</li>
			</ul>
		</p>
		<hr />
		<!-- Watercolors -->
		<header class="major">
			<h2>Selected Watercolors</h2>
		</header>
		<div class="box alt">
			<div class="row 50% uniform">
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/freakyfrog.webp %}" alt="Watercolor of a small green frog with a leg deformity" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<i>Pacific Chorus Frog infected with a Ribeiroia parasite</i>, 2025. Featured in <i>The Art of Nature</i> exhibit at the Santa Cruz Museum of Natural History
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/westcliff_flowers.webp %}" alt="Watercolor postcard of four wildflowers, labeled with their common name and scientific name. Clockwise starting from the top left: Seaside Buckwheat (Eriogonum latifolium), California fuchsia (Epilobum canum), California Poppy (Eschscholzia californica), and Seaside Daisy (Erigeron glaucus)" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<i>Flowers of West Cliff Drive, Santa Cruz, CA</i>, 2024. Postcard design.
					</p>
				</div>
				<!-- Break -->
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/tulips.webp %}" alt="Watercolor of a colorful tulip bouquet" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<i>Tulips for Irina</i>, 2025.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/audreyII.webp %}" alt="Watercolor of a drooling Audrey II, an alien carnivorous plant from Little Shop of Horrors" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<i>Audrey II</i>, 2025.
					</p>
				</div>
				<!-- Break -->
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/savannaheye.webp %}" alt="Watercolor of a close-up of a bearded dragon eye" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<i>Savannah's Eye</i>, 2023.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/tigerbeetle.webp %}" alt="Watercolor of an Ohlone Tiger Beetle with sharp pincing jaws and a shiny green carapace" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<i>Ohlone Tiger Beetle</i>, 2024.
					</p>
				</div>
			</div>
		</div>
		<hr />
		<!-- Zines, stencils, etc -->
		<header class="major">
			<h2>Educational Materials</h2>
		</header>
		<h3>Zines</h3>
		<!--<input type="checkbox" id="cover_checkbox" class="flip_trigger">-->
        <input type="checkbox" id="page1_checkbox" class="flip_trigger">
        <input type="checkbox" id="page2_checkbox" class="flip_trigger">
        <!-- Flip Book https://github.com/fchavonet/creative_coding-flip_book/blob/main/index.html -->
		<div style="display: flex; justify-content: center; align-items: center; min-height: 500px;">
	        <div id="flip_book">
	            <!-- <div class="front_cover">
	                <label for="cover_checkbox" id="cover"></label>
	            </div> -->
	            <div class="page" id="page1">
	                <div class="front_page">
	                    <label for="page1_checkbox"></label>
	                    <img class="edge_shading" src="{% link assets/images/front_page_edge_shading.webp %}" alt="Front page edge shading">
	                    <img class="front_content" src="{% link assets/images/ribeiroia_sneakpeek.webp %}" alt="Sketched-out form of a mini magazine on Ribeiroia">
	                </div>
	                <div class="back_page">
	                    <label for="page1_checkbox"></label>
	                    <img class="edge_shading" src="{% link assets/images/back_page_edge_shading.webp %}" alt="Back page edge shading">
	                    <img class="back_content" src="{% link assets/images/leftbrain.webp %}" alt="Graphite drawing of the left hemisphere of the brain.">
	                </div>
	            </div>
	            <div class="page" id="page2">
	                <div class="front_page">
	                    <label for="page2_checkbox"></label>
	                    <img class="edge_shading" src="{% link assets/images/front_page_edge_shading.webp %}" alt="Front page edge shading">
	                    <img class="front_content" src="{% link assets/images/rightbrain.webp %}" alt="Watercolor of the right hemisphere of the brain">
	                </div>
	                <div class="back_page">
	                    <label for="page2_checkbox"></label>
	                    <img class="edge_shading" src="{% link assets/images/back_page_edge_shading.webp %}" alt="Back page edge shading">
	                    <img class="back_content" src="{% link assets/images/cordyceps_sneakpeek.webp %}" alt="Sketches of a mini-magazine on Cordyceps">
	                </div>
	            </div>
	            <div class="back_cover"></div> 
	        </div>
		<style>
    		.flip_trigger { display: none; }
		</style>
		</div>
	</div>
</section>

<!-- Two -->

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Massa libero</h2>
		</header>
		<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet pharetra et feugiat tempus.</p>
		<ul class="actions">
			<li><a href="generic.html" class="button next">Get Started</a></li>
		</ul>
	</div>
</section>

</div>
