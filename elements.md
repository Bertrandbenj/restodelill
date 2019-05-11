---
layout: page
title: Carte
description: Voir la carte
nav-menu: true
---


<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>La carte</h1>
		</header>

<!-- Content -->
<h1 id="content">Entrées</h1>
<div class="row">
{% for starter in site.restaurant.starter %}
 <div class="4u 12u$(small)">
<h3>{{starter.name}}</h3>
{{starter.desc}}
{{starter.ix}}
 </div>
 
 <div class="4u 12u$(small)">
<h3> Les asperges d'Alsace</h3>
aux deux jambons & mayonnaise maison
 </div>
 
 <div class="4u 12u$(small)">
<h3> Les escargots</h3>
 <ul>
 <li>Beurre maison, la 1/2 douzaine</li>
 <li>Beurre maison, la douzaine</li>
</ul>
 
 </div>
</div>

<hr class="major" />


<h1 id="content">Plats</h1>	
<div class="row">
 <div class="4u 12u$(small)">
 </div>
</div>

<hr class="major" />


<h1 id="content">Desserts</h1>

<div class="row">
 <div class="4u 12u$(small)">
 </div>
</div>


</div>
</section>