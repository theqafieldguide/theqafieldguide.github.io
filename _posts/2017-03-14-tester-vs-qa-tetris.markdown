---
layout: post
title:  "Tester vs QA: Tetris"
date:   2017-03-14 01:00:00
last_modified_at:  2017-01-25 01:00:00
excerpt: "Comparing the typical waterfall tester to the agile QA in a battle of the blocks"
categories: tester
tags:  tester
image:
  feature: tetris.jpg
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
Source: [image](https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=0ahUKEwjWp4C719bSAhWE64MKHc3RDugQjhwIBQ&url=http%3A%2F%2Fwallpaperstock.net%2Ffullscreen-tetris_wallpapers_34849_1440x900_1.html&psig=AFQjCNG-UTpAo_19NZUsHygj6e21o9JO3w&ust=1489604320460655)

I find myself getting asked the question of what is the difference between a tester and a QA. “Don’t QA’s just test things?” Yes, but that’s not all... The thought of <b>Tetris</b> comes to mind when comparing these two entities.

Imagine yourself traveling back to playing the classic retro Tetris and picture this to emulate software development in a very obscure way. In this 8-bit development cycle, the developer is the one in control of moving and dropping the different shaped blocks. Their goal is to develop "rows" or features of the application in different iterations or “rounds”. With this in mind, let’s take a look at the “Tester."

#### Tester

Let’s say a developer is dropping blocks (implementing a feature) and time runs out and the round (or iteration) is over. It is my interpretation to think of a tester as someone who takes a look and critiques the laid blocks to ensure they are meeting all the business requirements as well as searching for bugs.

<br><center>
<img src="{{site.baseurl_posts_img}}drmario.png"/>
</center>

It is only after the fact that the tester assesses the work the developer is done. As you may remember in Tetris, after a round is finished, once the blocks are placed, there is not much you can do in that moment. There is a much longer feedback loop in the sense that even though the tester identifies defects, it is difficult for the developer to go back and attempt to fix what's already been played.

#### QA

The QA takes a more holistic approach to providing value to delivery. During gameplay, a window displayed on the right side of the screen labeled "NEXT" was there to notify the player what block is coming up next. A QA would be working with the developer during the iteration to analyze the current feature implementation and finding issues as well as calling out risks that might be coming up "next" or could affect future implementation.

<br><center>
<img src="{{site.baseurl_posts_img}}tetris_upNext.jpg"/>
</center>

In our Tetris software lifecycle, the QA is "testing" during the entire round (not just the end) and constantly checking if there are two things happening:
<br>
1. Are we building the <u>correct</u> thing?
2. Are we building it <u>correctly</u>. <a href="https://www.thoughtworks.com/insights/blog/qa-role-what-it-really">[1]</a>

Because QA has the word "quality" in it's name, it's so easy to overload the term. Since we all have such different definitions and interpretations of quality, it's a lot more difficult to focus the scope of our goal. Kenny Cruden goes in depth to this as well as a great overview of <a href="https://www.thoughtworks.com/insights/blog/qa-role-what-it-really">what a QA is</a>. This is definitely just a small part of what a QA is taking on throughout the iteration.

<blockquote class="largeQuote">"All QAs are testers, but not all testers are QAs."</blockquote>

It goes without saying that the reason there is some confusion between a QA and a tester is because there is some overlap. A good QA will also take their take to check out post-development and proceed to conduct exploratory testing on the dev-finished work and provide that same feedback that a tester would. The role and responsibilities of a tester are encapsulated in QA.
