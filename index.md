---
layout: default
title: Family Fantasy Football
---
<img class="center" src="/assets/fantasy_football.png" alt="Fantasy Football">
<h1 align="center" >2019 Family Fantasy Football</h1>
Hope everyone's offseason was productive and we've learned a lot since letting the <a href="http://fantasy.espn.com/football/team?leagueId=215530&seasonId=2019&teamId=12" target="_blank">"Auto Draft King"</a> beat us in fantasy football.

Can it really be true that Jeremy is a 3-time Defending Champ? Be sure to jump over the the [Hall of Fame](https://sportsfamily.club/gallery) to review.

I thought it would be fun to have a central place to document all the story lines, prizes, and history our time chasing fantasy glory.

### Here's the latest posts:
----
<ul>
  {% for post in site.posts limit:4 %}
    <li>
      {{ post.date | date: "%m/%d"}} | <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>