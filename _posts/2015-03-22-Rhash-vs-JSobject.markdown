---
layout: post
title:  "The Ruby Hash vs the JavaScript Object"
date:   2015-03-22 09:17:32
categories: jekyll update
---

This week at DBC we jumped into the world of JavaScript, and just as I was getting used to working in Ruby! Oh well, I'm just glad they keep us on our toes! While going over the basics of JS I tried to 'translate' what any given structure in JS was to its Ruby counterpart. That is, if it had one. The JS object (not to be confused with objects in ruby!) so much like Hashes in Ruby, its almost like one was modeled after the other!! (hint hint, wink wink)


First of all the purposes of Hashes(Ruby) and Objects(JS) are essentially the same; storing and organizing data, correlating each unit of Data to a key. I went briefly went over Hashes (ruby) in a <a class="bloglink" href="#"> previous blog </a>. 


Luckily the syntax and structure of these two are super similar as well. This similarity presented itself as a double edged sword for me this week. One one hand it made it easy to remember how to set up my JS objects, but on the other hand I accidently wrote them like I would a Ruby Hash. Woops! any ways the syntax looks a little bit like this:<br>
Ruby Hash:
<br>
hash = {:key1 => item1, :key2 =>item2}<br>
JS Object:
<br>
var object = {key1: "item1", key2: "item2"}<br>
As you can see, very similar with some subtle differences!