---
layout: default
title: Home
---

<div class="jumbotron">

    <img class="pull-right" src="img/beerandcodelogo.jpg" width="150px"
    height="150px" />

    <h1>Socialize, write code, and drink good beer!</h1>

    <p class="lead">Take your passion for programming and love of beer and
    join us for our monthly <strong>Beer and Code</strong> meetup.</p>

</div>

<div>

The next meetup is...

</div>

<div id="posts">

    {% for post in site.posts %}

        <!-- put post content here -->

    {% endfor %}

</div>
