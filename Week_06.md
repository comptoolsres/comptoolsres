---
title: "Week 6"
tags: [week-by-week]
sidebar: home_sidebar
permalink: Week_06.html
toc: false
week_num: 6
series: "Week-by-week series"
weight: 0.6
---

# Week 6: {{site.wk06_mon_date | date: '%b %d' }} - {{site.wk06_fri_date | date: '%b %d' }}

{% include custom/series_week_by_week.html %}

## Overview for Week {{page.week_num}}

* Getting started in Python
* Using Python on the command line
* Using Python in Jupyter notebooks
* Python flow control (contitionals and loops)
* Functions
* Iteration
* `try/except`
* Strings and string manipulation
* File I/O

## What's due by the end of the week?

* Nothing is due this week
* Problem Set 3 will be available Monday. It is due {{site.ps_3_due | date: '%A, %B %d' }}
* Quiz 3 will be available on Monday. It is due {{site.quiz_3_due | date: '%A, %B %d' }}

## For Monday

{% include image.html file='monday.png' alt="Calendar icon with Monday" position="right" max-width=75 %}

<ul id="MondayTabs" class="nav nav-tabs">
    <li class="active"><a href="#MonBefore" data-toggle="tab">Before Class</a></li>
    <li><a href="#MonDuring" data-toggle="tab">During Class</a></li>
</ul>
<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="MonBefore">
        {% include day/013_before.html %}
    </div>
    <div role="tabpanel" class="tab-pane" id="MonDuring">
        {% include day/013_during.html %}
    </div>
</div>

## For Wednesday

{% include image.html file='wednesday.png' alt="Calendar icon with Wednesday" position="right" max-width=75 %}

<ul id="WednesdayTabs" class="nav nav-tabs">
    <li class="active"><a href="#WedBefore" data-toggle="tab">Before Class</a></li>
    <li><a href="#WedDuring" data-toggle="tab">During Class</a></li>
</ul>
<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="WedBefore">
        {% include day/014_before.html %}
    </div>
    <div role="tabpanel" class="tab-pane" id="WedDuring">
        {% include day/014_during.html %}
    </div>
</div>

## For Friday

{% include image.html file='friday.png' alt="Calendar icon with Friday" position="right" max-width=75 %}

<ul id="FridayTabs" class="nav nav-tabs">
    <li class="active"><a href="#FriBefore" data-toggle="tab">Before Class</a></li>
    <li><a href="#FriDuring" data-toggle="tab">During Class</a></li>
</ul>
<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="FriBefore">
        {% include day/015_before.html %}
    </div>
    <div role="tabpanel" class="tab-pane" id="FriDuring">
        {% include day/015_during.html %}
    </div>
</div>

## By the end of this week you should

{% include image.html file='checkmark.png' alt="Check mark icon" position="right" max-width=75 %}

1. Be starting to feel comfortable in Python
1. Understand loops and conditionals in Python and how they are similar to the same ideas in Bash
1. Be able to work with strings, manipulating them, printing them, etc.
1. Be able to open a file for reading or writing

{% include custom/office_hours.html %}

{% include custom/series_week_by_week_next.html %}