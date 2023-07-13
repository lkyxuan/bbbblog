---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 🌱

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">


  Welcome to 0xmiracle's blog, a garage with its doors wide open, filled with stories, laughter, and dreams of a technological future. His journey began in the most ordinary of places. He was not born with a silver spoon, nor any privileges. He is just an ordinary individual, filled with curiosity and a passion for technology."<span style="font-weight: bold">[[Content Index]]</span> You'll realize that each ordinary individual has the capacity to alter the world. Provided that you harbor a love for technology, are open to learning, and dare to embark on risks, everyone can be the hero of their own story.
 <span style="font-weight: bold">[[Content Index]]</span> Let's go !

  
</p>



<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
