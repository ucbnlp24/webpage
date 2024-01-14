---
layout: home
title: Home
nav_order: 0
permalink: /:path/
description: >-
    Course policies and information.
---

# Natural Language Processing 
{: .mb-2 .text-purple-dk-200}
Spring 2024, Mon/Wed, 6:30-8:00 PM, Dwinelle 145
{: .mb-2 .fs-6 .text-purple-dk-000}


---
Welcome to Natural Language Processing (NLP)!
This course introduces students to NLP and exposes them to the variety of methods available for reasoning about text in computational systems. NLP is deeply interdisciplinary, drawing on both linguistics and computer science, and helps drive much contemporary work in text analysis. We will focus on major algorithms used in NLP for various applications (text classification, parsing, question answering, machine translation, etc.) and on the linguistic phenomena those algorithms attempt to model. Students will implement algorithms and create linguistically annotated data on which those algorithms depend*.

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}

*Major parts of course design and contents have been drawn from its earlier offerings by Prof. David Bamman. 