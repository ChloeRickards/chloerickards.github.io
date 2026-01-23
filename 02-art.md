---
layout: landing
title: Art
description: Enter a world of science illustration, playful creations, and immersive storytelling.
image: assets/images/rightbrain.webp
permalink: /art/
order: 2
nav-menu: true
---

<!--Flipbook trigger-->
<style>
    .flip_trigger { display: none; }
</style>

<!-- Main -->
<div id="main">

<!-- Artist Statement -->
<section id="artstatement">
	<div class="inner">
		<header class="major">
			<h2>Curating Curiosity</h2>
		</header>
		<p>One common theme runs throughout all of my creations: curiosity. From investigating the intricacies of nature in watercolor to exploring every rabbit hole in an immersive experience, I use art as a tool for discovery. My current projects include: </p>
		<ul>
			<li> Watercolor and graphite designs for singer/songwriter <a href = "https://www.rosesbyothernames.com/">Ilia Rose</a></li>
			<li> Needlefelted dioramas for the <a href = "https://www.sccmod.org/">Santa Cruz Children's Museum of Discovery</a></li>
			<li> Mural-making for local Santa Cruz businesses</li>	
			<li> An interactive play about an AI possessed by a demon</li>
		</ul>
		<a href="https://ko-fi.com/chloerickards" class="button special">Buy me a coffee on Ko-fi</a>
	</div>
</section>
		<!-- 
		Watercolors
		-->
<section id="watercolors">
	<div class = "inner">
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
		<!-- 
		Sketchbook 
		-->
		<p> Note: This sketchbook is not optimized for mobile or narrow windows, but you can try!</p>
		<input type="checkbox" id="sketchbook_cover_checkbox" class="flip_trigger">
			{% for i in (1..7) %}<input type="checkbox" id="sketchbook_page{{ i }}_checkbox" class="flip_trigger">{% endfor %}
	    <div id="sketchbook" class = "flip_container landscape-book">
			<!--Cover-->
	        <div class="front_cover">
				<div class="front_page_cover">
		            <label for="sketchbook_cover_checkbox">
						<img src="{% link assets/images/sketchbook.webp %}" 
								alt="Sketchbook cover">
					</label>
				</div>
				<div class="back_page_cover"></div>
	        </div>
				<!--Page 1-->
	        <div class="page" id="sketchbook_page1">
	            <div class="front_page">
	                <label for="sketchbook_page1_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/beltane.webp %}" alt="Full-page watercolor of a festival scene">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page1_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/cordy_ant.webp %}" alt="Watercolor of an ant infected with the Cordyceps fungus">
	            </div>
	        </div>
			<!--Page 2-->
	        <div class="page" id="sketchbook_page2">
	            <div class="front_page">
	                <label for="sketchbook_page2_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/mosquito.webp %}" alt="Watercolor of a mosquito filled with blood">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page2_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/savannahhat.webp %}" alt="Watercolor of a bearded dragon in a witch's hat">
	            </div>
	        </div>
				<!--Page 3-->
			<div class="page" id="sketchbook_page3">
	            <div class="front_page">
	                <label for="sketchbook_page3_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/redwoodflowers.webp %}" alt="Watercolor of several wildflowers common to redwood forests">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page3_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/bluebutterfly.webp %}" alt="Watercolor of a small blue butterfly">
	            </div>
	        </div>
			<!--Page 4-->
			<div class="page" id="sketchbook_page4">
	            <div class="front_page">
	                <label for="sketchbook_page4_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/creepyplants.webp %}" alt="Watercolor of a corpse flower and a California pitcher plant">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page4_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/crow.webp %}" alt="Watercolor of a crow looking upward">
	            </div>
	        </div>
				<!--Page 5-->
			<div class="page" id="sketchbook_page5">
	            <div class="front_page">
	                <label for="sketchbook_page5_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/lm.webp %}" alt="Watercolor of a series of montage from the immersive world of Lennox Mutual">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page5_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/pug.webp %}" alt="Watercolor of a pug dog in magenta and yellow">
	            </div>
	        </div>
			<!--Page 6-->
			<div class="page" id="sketchbook_page6">
	            <div class="front_page">
	                <label for="sketchbook_page6_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/towhee.webp %}" alt="Watercolor of a Spotted Towhee">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page6_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/salamander.webp %}" alt="Watercolor of a black salamander with orange spots, infectd with Cordyceps fungus">
	            </div>
	        </div>
			<!--Page 7-->
			<div class="page" id="sketchbook_page7">
	            <div class="front_page">
	                <label for="sketchbook_page7_checkbox"></label>
	                <img class="front_content" src="{% link assets/images/cordy_deer.webp %}" alt="Watercolor of a deer infected with Cordyceps">
	            </div>
	            <div class="back_page">
	                <label for="sketchbook_page7_checkbox"></label>
	                <img class="back_content" src="{% link assets/images/zayante.webp %}" alt="Watercolor of a Zayante band-winged grasshopper">
	            </div>
	        </div>
	        <div class="back_cover"></div> 
	    </div>
		<hr />
		<div class="book-feature">
    		<span class="image book-cover">
        		<img src="{% link assets/images/poisonedbrother.webp %}" alt="Book cover featuring a watercolor salamander, titled The Poisoned Brother by David Rickards" />
    		</span> 
    		<p>
        		My watercolor, <i> Santa Cruz Long-toed Salamander Infected with Cordyceps</i> is featured on the cover of <i>The Poisoned Brother</i> by David Rickards. Read it on Kindle or in paperback at <a href = "https://a.co/d/0Ng47ts">https://a.co/d/0Ng47ts</a>.
			</p>
		</div>
	</div>
</section>

<!-- Immersive Design -->
<section id="immersive">
	<div class="inner">
		<header class="major">
			<h2>Art that Invites You In</h2>
		</header>
		<p>I love to make art you can touch -- from large-scale murals to interactive elements in an immersive exhibit. Recently, I worked on some elements of a multi-sensory exhibit for the Santa Cruz Children's Museum of Discovery, titled "The Enchanted Forest". Stay tuned for future projects!</p>
		<div class="box alt">
			<div class="row 50% uniform">
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/wipstainedglass.webp %}" alt="Pieces of acrylic lasercut flower in a stained glass style, mid-assembly" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						I used lasercut Plexiglas to create this "stained glass" piece for the window of the Enchanted Forest's Hobbit Hole play structure.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/flowerstainedglass.webp %}" alt="Acrylic lasercut flower in a stained glass style, fully installed" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Fully installed "stained glass" window in the Hobbit Hole.
					</p>
				</div>
				<!-- Break -->
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/mosswall.webp %}" alt="Large wall decorated with green fabrics, with a TV screen in the middle" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						The Moss Wall, made out of recycled fabric to create the moss texture. The TV screen is part of the <a href = "https://digitalnest.org/bizznest-brings-childrens-drawings-to-life-with-ai-machine-learning/">Animation Station designed by Digital NEST</a>.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/mosswall_detail.webp %}" alt="Close-up details of some of the fabric that makes up the moss wall." /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Moss Wall close-up, featuring recycled fabrics from rugs, scarves, yarn, upholstery, and sweaters.
					</p>
				</div>
			</div>
		</div>
		<span class="image fit"><img src="{% link assets/images/fullexhibit.webp %}" alt="" /></span>
		<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
			The Enchanted Forest exhibit, featuring the Hobbit Hole structure with the "stained glass" window I designed, and the moss wall in the background.
		</p>
	</div>
</section>

<!-- Educational Materials -->
<section id="edmaterials">
	<div class = "inner">
		<header class="major">
			<h2>Educational Materials</h2>
		</header>
		<!-- zines and lectures -->
		<h3>Zines</h3>
		<p>I make zines (mini-magazines) to accompany scientific lectures. These are sneak peeks of the zines from two "Naturalist Night" lectures from the Santa Cruz Museum of Natural History.</p>
		<!-- Zine placeholders -->
		<!-- Cordyceps Zine
		<div style="display: flex; justify-content: center; align-items: center; min-height: 450px;">
            {% for i in (1..4) %}<input type="checkbox" id="C_page{{ i }}_checkbox" class="flip_trigger">{% endfor %}
            <div id="cordyceps" class="flip_container portrait-book">
				Page 1
                <div class="page" id="C_page1">
                    <div class="front_page">
                        <label for="C_page1_checkbox"></label>
                        <img src="{% link assets/images/crow.webp %}" alt="Cordyceps Front">
                    </div>
                    <div class="back_page">
                        <label for="C_page2_checkbox"></label>
                        <img src="{% link assets/images/pug.webp %}" alt="Cordyceps Page 2">
                    </div>
                </div>
				<!-- Page 2
				<div class="page" id="C_page2">
					<div class="front_page">
        				<label for="C_page2_checkbox"></label>
        				<img src="{% link assets/images/towhee.webp %}" alt="Cordyceps Page 3">
    				</div>
    				<div class="back_page">
        				<label for="C_page3_checkbox"></label>
        				<img src="{% link assets/images/mosquito.webp %}" alt="Cordyceps Page 4">
    				</div>
				</div>
				<!-- Page 3
				<div class="page" id="C_page3">
    				<div class="front_page">
        				<label for="C_page3_checkbox"></label>
        				<img src="{% link assets/images/crow.webp %}" alt="Cordyceps Page 5">
    				</div>
    				<div class="back_page">
        				<label for="C_page4_checkbox"></label>
        				<img src="{% link assets/images/pug.webp %}" alt="Cordyceps Page 6">
    				</div>
				</div>
				<!-- Page 4
				<div class="page" id="C_page4">
				    <div class="front_page">
				        <label for="C_page4_checkbox"></label>'
				        <img src="{% link assets/images/towhee.webp %}" alt="Cordyceps Page 7">
				    </div>
				    <div class="back_page">
				        <img src="{% link assets/images/mosquito.webp %}" alt="Cordyceps Page 8">
				    </div>
				</div>
                <div class="back_cover"></div>
            </div>
        </div>
		<!-- Frog Zine 
        <div style="display: flex; justify-content: center; align-items: center; min-height: 450px; margin-top: 4em;">
            {% for i in (1..4) %}<input type="checkbox" id="F_page{{ i }}_checkbox" class="flip_trigger">{% endfor %}
            <div id="frog" class="flip_container portrait-book">
				<!-- Page 1 
                <div class="page" id="F_page1">
                    <div class="front_page">
                        <label for="F_page1_checkbox"></label>
                        <img src="{% link assets/images/mosquito.webp %}" alt="Frog Zine Front">
                    </div>
                    <div class="back_page">
                        <label for="F_page2_checkbox"></label>
                        <img src="{% link assets/images/towhee.webp %}" alt="Frog Zine Page 2">
                    </div>
                </div>
				<!-- Page 2 
				<div class="page" id="F_page2">
				    <div class="front_page">
				        <label for="F_page2_checkbox"></label>
				        <img src="{% link assets/images/crow.webp %}" alt="Frog Page 3">
				    </div>
				    <div class="back_page">
				        <label for="F_page3_checkbox"></label>
				        <img src="{% link assets/images/pug.webp %}" alt="Frog Page 4">
				    </div>
				</div>
				<!-- Page 3 
				<div class="page" id="F_page3">
				    <div class="front_page">
				        <label for="F_page3_checkbox"></label>
				        <img src="{% link assets/images/crow.webp %}" alt="Frog Page 5">
				    </div>
				    <div class="back_page">
				        <label for="F_page4_checkbox"></label>
				        <img src="{% link assets/images/mosquito.webp %}" alt="Frog Page 6">
				    </div>
				</div>
				<!-- Page 4 
				<div class="page" id="F_page4">
				    <div class="front_page">
				        <label for="F_page4_checkbox"></label>
				        <img src="{% link assets/images/towhee.webp %}" alt="Frog Page 7">
				    </div>
				    <div class="back_page">
				        <img src="{% link assets/images/pug.webp %}" alt="Frog Page 8">
				    </div>
				</div>
                <div class="back_cover"></div>
            </div>
        </div>
		<!-- Zine pictures -->
		<div class="box alt">
			<div class="row 50% uniform">
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/cordyceps_sneakpeek.webp %}" alt="Pencil and ink sketches that show information about the Cordyceps fungus" />
					</span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						"What would it look like if Cordyceps infected other animals?" is a zine about speculative evolution for the cordyceps pathogenic fungus.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/ribeiroia_sneakpeek.webp %}" alt="Sketches and watercolors that show information about the Ribeiroia pathogen" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						"Freaky Frogday" is a zine about <i>Ribeiroia ondrata</i>, a parasitic worm native to western North America that causes amphibian deformities.
					</p>
				</div>
			</div>
		</div>
		<hr />
		<!-- Stencils -->
		<h3>Stencils</h3>
		<p>I design lasercut and 3D-printed scientifically-accurate stencils that I use for wax resist watercolor activity stations in events like the Santa Cruz Fungus Fair.</p>
		<div class="box alt">
			<div class="row 50% uniform">
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/chanterelle.webp %}" alt="Wooden lasercut stencil of a chanterelle mushroom being filled in with an orange crayon" />
					</span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Chanterelle mushroom stencil, designed and lasercut for the Santa Cruz Fungus Fair in 2025.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/tardigrade.webp %}" alt="3D-printed tardigrade stencil in front of a wax-resist watercolor." /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Tardigrade stencil, designed and lasercut for the "Out of this World" Halloween party at the Santa Cruz Museum of Natural History.
					</p>
				</div>
			</div>
		</div>
	</div>
</section>

<section id="other">
	<div class = "inner">
		<header class="major">
			<h2>Other Creative Projects</h2>
		</header>
		<h3> Needlefelting</h3>
		<div class="box alt">
			<div class="row 50% uniform">
				<div class="4u">
					<span class="image fit"><img src="{% link assets/images/amanita.webp %}" alt="Needlefelted sculpture of Amanita muscaria" />
					</span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Needlefelted <i>Amanita muscaria</i> mushroom for <a href = "https://www.taylorseamount.com/installation.html">Taylor Seamount's "Reading Nook of Amanita M. EnnJax" installation</a>. 
					</p>
				</div>
				<div class="4u">
					<span class="image fit"><img src="{% link assets/images/seamount.webp %}" alt="Reading Nook installation by Taylor Seamount, featuring a needlefelted mushroom on a table" />
					</span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						<a href = "https://www.taylorseamount.com/installation.html">Taylor Seamount's "Reading Nook of Amanita M. EnnJax" installation</a>, featuring my needlefelted mushroom on the side table. 
					</p>
				</div>
				<div class="4u$">
					<span class="image fit"><img src="{% link assets/images/needlefelts.webp %}" alt="Collage of two needlefelted sculpture, one of Appa the air bison, and one of a rate" /></span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Appa and rat sculptures
					</p>
				</div>
			</div>
		</div>
		<h3> Halloween Costumes </h3>
		<p> Because Santa Cruz goes hard for Halloween and I LOVE Halloween!</p>
		<div class="box alt">
			<div class="row 50% uniform">
				<div class="6u">
					<span class="image fit"><img src="{% link assets/images/bogwitch.webp %}" alt="A 4-legged creature on stilts for a Halloween costume" />
					</span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						I went a little wild with a stilt idea in 2024.
					</p>
				</div>
				<div class="6u$">
					<span class="image fit"><img src="{% link assets/images/magicschoolbus.webp %}" alt="Halloween costume of myself as Miss Frizzle, with a Magic School Bus companion, and with my bearded dragon as Lizzy the lizard." />
					</span>
					<p style="font-size: 0.8em; line-height: 1.2em; margin-top: -10px;">
						Featuring Savannah, my bearded dragon, as Liz.
					</p>
				</div>
			</div>
		</div>
	</div>
</section>
</div>
