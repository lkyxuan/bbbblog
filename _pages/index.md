---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to 0xmiracle's blog 🌱

<p style="padding: 1em 1em; background: #ffffff; border-radius: 4px;">


 A garage with its doors wide open, filled with stories, laughter, and dreams of a technological future. He was not born with a silver spoon, nor any privileges.  Just an ordinary individual, filled with curiosity and a passion for technology.
</p>
<p style="padding: 4em 4em; background: #000000; border-radius: 20px;">
<span style="font-weight: bold">[[Content Index|Let's fucking go]]</span> 
</p>
<p style="padding: 3em 1em; background: #ffffff; border-radius: 4px;">
You'll realize that each ordinary individual has the capacity to alter the world. Provided that you harbor a love for technology, are open to learning, and dare to embark on risks, everyone can be the hero of their own story.
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
