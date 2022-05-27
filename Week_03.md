---
title: "Week 3"
tags: [week-by-week]
sidebar: home_sidebar
permalink: Week_03.html
toc: false
week_num: 3
series: "Week-by-week series"
weight: 0.3
---

# Week 3: {{site.wk03_mon_date | date: '%b %d' }} - {{site.wk03_fri_date | date: '%b %d' }}

{% include custom/series_week_by_week.html %}

## Overview for Week {{page.week_num}}

* Writing shell scripts
* Using git and github.com for version control and collaboration
* Flow control: conditionals and loops

## What's due by the end of the week?

* **Problem Set 1 is due {{site.ps_1_due}}.**
* Quiz 2 will be available Monday. It is due {{site.quiz_2_due}}
  * Quiz 2 covers using: `cat`, `cut`, `sort`, `uniq`, and `paste`; as well as recognizing the meaning of the commands `if`, `for`, `while`, `break`, `continue`, `else`, `git add`, `git commit`, `git pull`.

## For Monday

{% include image.html file='monday.png' alt="Calendar icon with Monday" position="right" max-width=75 %}

<ul id="MondayTabs" class="nav nav-tabs">
    <li class="active"><a href="#MonBefore" data-toggle="tab">Before Class</a></li>
    <li><a href="#MonDuring" data-toggle="tab">During Class</a></li>
</ul>
<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="MonBefore">
      <ol>
        <li><a href="LinkedInLearningLinux.html">Watch Learn the Linux Command Line</a></li>
        <li><a href="github_account.html">Register for github.com account</a></li>
        <li><a href="TLCL_4.html">Read TLCL Ch 24 - 26</a></li>
      </ol>
    </div>
    <div role="tabpanel" class="tab-pane" id="MonDuring">
        <ol>
          <li>Zoom meeting for class: {{site.class_zoom_link}}</li>
          <li>Hands-on with github use in writing scripts</li>
        </ol>
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
      Get caught up.
    </div>
    <div role="tabpanel" class="tab-pane" id="WedDuring">
        <ol>
          <li>Zoom meeting for class: {{site.class_zoom_link}}</li>
          <li><a href="github_branches.html">Github Branching exercise</a></li>
        </ol>
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
        <ol>
          <li><a href="TLCL_5.html">Read TLCL Ch 27, 29 & 33</a></li>
        </ol>
    </div>
    <div role="tabpanel" class="tab-pane" id="FriDuring">
        <ol>
          <li>Zoom meeting for class: {{site.class_zoom_link}}</li>
          </li>Practice with flow control: `if`, `while`, `until`, `for`</li>
        </ol>
    </div>
</div>

## By the end of this week you should

{% include image.html file='checkmark.png' alt="Check mark icon" position="right" max-width=75 %}
1. Have a github.com account
1. Have watched the LinkedIn Learning Linux Command Line class
1. Be comfortable writing bash scripts to accomplish more complex tasks
1. Understand how to use git and github to:
   * Create a branch
   * Modify code
   * Add modified code to stage the changes
   * Commit the modified code
   * Push the modified code to github remote repository
   * Merge the branch into the main branch
1. Be comfortable with loops and conditionals.

{% include custom/office_hours.html %}

{% include custom/series_week_by_week_next.html %}