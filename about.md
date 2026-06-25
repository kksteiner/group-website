---
layout: default
title: About me
---

My name is Kate and I am a professor of music.

## Funders
These are people on our team

## Team
 {% for team_member in site.team_members %}
 - {{ team_member.name }}, role: {{ team_member.role }}
 {% endfor %}
