---
layout: default
title: Family Fantasy Football
---
![Fantasy Football](/assets/fantasy_football.png)

<h2 align="center" >2019 Family Fantasy Football</h2>
Hope everyone's offseason was productive and we've learned a lot since letting the <a href="http://fantasy.espn.com/football/team?leagueId=215530&seasonId=2019&teamId=12" target="_blank">"Auto Draft King"</a> beat us in fantasy football.

I thought it would be fun to have a central place to document all the story lines, prizes, and history our time chasing fantasy glory.
### Here's the latest news
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>