---
layout: default
title: About
permalink: /about/
---

{% include button.html %}

pronouns: **she/her/hers**

I'm a newly turned user interface and user experience designer. 

I strive to create **appealing visual solutions**, using form as the tool that establishes a **connection between user and content**.


## Work experience

{% for item in site.data.cvwork %}
### {{ item.title }} 
#### {{ item.institution }}
{{ item.description }} 
##### {{ item.time }}
{% endfor %}


## Education

{% for item in site.data.cvschool %}
### {{ item.title }} 
#### {{ item.institution }} 
{{ item.description }} 
##### {{ item.time }}
{% endfor %}

## Tools
### Figma
### Adobe suite
Indesign, Photoshop, Illustrator, XD, Lightroom, AfterEffects
### HTML/CSS

## Languages
### Portuguese
Native

### English
Fluent (C2)

## Workshops and Exhibitions
### Processing Community day @FBAUP
Showcasing of projects created using Processing.
##### february 2019

### Type design for complete begginers: experimenting with variable fonts
#### FBAUP, I2ADS, ID+
10 hour workshop of variable font design and implementation.
##### june 2018