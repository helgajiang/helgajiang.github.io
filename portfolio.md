---
layout: page
title: Portfolio
permalink: /portfolio/
---
<div class="grid">

{% for project in site.portfolio %}

<!--
{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}
-->

<div class="grid-item">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <p class="project-title">{{ project.title }}</p>
            <p class="project-desc">{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

<!--{% endif %}-->

{% endfor %}

</div>