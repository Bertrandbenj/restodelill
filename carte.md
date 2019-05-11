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
            {% for dish in site.restaurant.starter %}
                <div class="4u 12u$(small)">
                    <h3>{{dish.name}}</h3>
                    <p>{{dish.desc}}<br/>
                    {{dish.prix}} €</p>
                </div>
            {% endfor %} 
         </div>
        
        
        <hr class="major" />
        
        
         <h1 id="content">Plats</h1>	
         <div class="row">Nous
          {% for dish in site.restaurant.maindish %}
                <div class="6u 12u$(small)">
                    <h3>{{dish.name}}</h3>
                    <p>{{dish.desc}}<br/>
                        {% if dish.prix %}
                            {{dish.prix}} €
                        {% endif %}
                     </p>
                </div>
            {% endfor %} 
         </div>
        
        <hr class="major" />
        
        
        <h1 id="content">Desserts</h1>
        
        <div class="row">
            {% for dish in site.restaurant.dessert %}
                <div class="4u 12u$(small)">
                    <h3>{{dish.name}}</h3>
                    <p>{{dish.desc}}<br/>
                    {{dish.prix}} €</p>
                </div>
            {% endfor %} 
        </div>


<p>Sous réserve de modifications</p>
<p>L'abus d'alcool est dangereux pour la santé</p>
</div>
</section>

</div>