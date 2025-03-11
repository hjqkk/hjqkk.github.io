---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science and Technology, Shaoguang University, 2024 

Work experience
======
* Spring 2024: Spring-based flower system
  * Project Introduction : The system enables a convenient flower ordering service app, compatible with WeChat mini-programs and web pages, through which users can browse nearby florists, view products, place orders and pay for orders, and track the status of orders.
  * Technical aspects : The sales of flower products and the management of users include the management side and the user side, the backend is built using Java language and Spring framework, the front-end project is run based on nginx, and the database uses MD5 encryption to encrypt the plaintext password in order to ensure the security of the user.
  * Achieve results : It improves the convenience and efficiency of the user experience, and supports self-pickup and takeaway delivery options to meet the needs of different users.

* Fall 2022: Design mini-game based on Unity3D
  * Project Introduction : The project uses the C# language to implement a shooting game from a third-person perspective, the game characters are divided into the protagonist and NPC players (three forms), the protagonist can follow the mouse or keyboard buttons to move, by triggering the key keys to achieve the protagonist's shooting animation and have damage value for the player who hits the NPC, and the protagonist will also appear in three forms (full health, injury, death) with the increase of the NPC player's damage value
  * Responsible work : Character and scene design, requirements review and requirements document writing, player operation design, NPC interaction and appearance animation trigger design, functional framework design

* Winter 2021: Python web crawler
  * Project Introduction : The project enables a quick retrieval of a user's microblog posts over a period of time and appropriate measures to circumvent the restrictions
  * Project process : Analyze the structure of the target page, determine the scope of data to be captured, filter unwanted information, parse HTML documents, set functions to extract the required data, store it in the database, and visualize the output display.
  * Achieve results : Crawl the user's non-private information and output valid information
  
Skills
======
* English proficiencyCET-4(521)
* programming language
  * C/C++
  * Python
  * Java
  * *Proficient in using common commands of Linux and Git
* Proficient in prototyping with Axure software and Blue Lake plug-ins

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
