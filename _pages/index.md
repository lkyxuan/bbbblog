---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 🌱

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">


  欢迎你来到 0xmiracle的博客，这是一个敞开大门的车库，充满了故事，笑声，以及对科技未来的梦想。他的旅程从最平凡的地方开始。他并非生来就拥有金钥匙，也没有任何特权，他只是一个满怀好奇、热爱科技的普通人。<span style="font-weight: bold">[[Content Index]]</span> Let's go !
  Take a look at <span style="font-weight: bold">[[Content Index]]</span> Let's go !

  
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
