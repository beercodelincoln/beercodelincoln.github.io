---
layout: default
title: Home
---

<div class="jumbotron">

    <img id="beerandcodelogo" class="pull-right" src="img/beerandcodelogo.jpg" width="150px"
    height="150px" />

    <h1>Socialize, write code, and drink good beer!</h1>

    <p class="lead">Take your passion for programming and love of beer and
    join us for our monthly <strong>Beer and Code</strong> meetup.</p>

</div>

<div id="posts">

    <ul>
    {% for post in site.posts %}

        <li>
            <div class="post-header">
                <p class="pull-right">posted: {{ post.date | date: "%m/%d/%y" }}</p>
                <h1>{{ post.title }}</h1>
            </div>

            <p>{{ post.content }}</p>
        </li>

    {% endfor %}
    </ul>

</div>
