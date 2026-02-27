---
layout: default
---

<h1>A Statistical Physics Perspective on Machine Learning</h1>

<p>
Draft chapters and lecture notes by  
<strong>Florent Krzakala, Bruno Loureiro,  Antoine Maillard and Lenka Zdeborová</strong>.
</p>

<hr>

<h2>Chapters</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
