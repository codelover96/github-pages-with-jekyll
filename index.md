---
title: "Welcome to my blog"
---
Hi I'm Costas Patsaras, software engineer and as my github name suggests, a code lover.

I'm glad you are here. I plan to talk about things i've built and learned while coding since 2014.
Feel free to copy and use any of the material in this blog.

Topics:
* Arduino
* Raspberry pi
* Python
* Machine Learning
* Pihole
* Pritunl
* Website development
* Privacy & Security

For educational porpuses
~codelover96

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
