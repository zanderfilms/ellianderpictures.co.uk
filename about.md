---
title: About
layout: just-text
---
# ABOUT

<img src= "./elliot_zander.jpg" alt="Elliot &amp; Zander Weaver" style="max-width: 400px; float: left"/>

{% assign elliotBday = '1988-03-16' | date: '%s' %}
{% assign zanderBday = '1991-01-20' | date: '%s' %}
{% assign nowTimestamp = 'now' | date: '%s' %}
{% assign elliotAge = nowTimestamp | minus: elliotBday | divided_by: 31536000 %}
{% assign zanderAge = nowTimestamp | minus: zanderBday | divided_by: 31536000 %}

Elliander Pictures is a UK-based production partnership between directing brothers Elliot Weaver ({{ elliotAge }}) and Zander Weaver ({{ zanderAge }}), producing both factual television and narrative dramatic content.

Since 2010 the company has produced over nine hours of factual programming for broadcasters including *Discovery*, *PBS*, *Canal+* and *UKTV* and have just completed production on the self-produced feature film, <a href= "https://ellianderpictures.co.uk/films/cosmos.html">COSMOS</a>.

The brothers plan to continue producing documentaries but shift their focus to directing feature films, where their passion lies.

*Please Note*: This website is currently under development. Missing video content can currently be found on <a href= "https://vimeo.com/ellianderpics" target="_blank">Vimeo</a>. More information on recent projects can be found on the <a href= "https://reeldealfilmschool.wordpress.com/projects/" target="_blank">company's blog</a>.
