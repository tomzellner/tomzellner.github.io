---
layout: post
title:  "CSS: Inline vs Block-Inline"
date:   2015-02-17 09:17:32
categories: jekyll update
---


When I first went over my DBC lessons this week covering CSS display properties, I was worried I would never grasp the concepts. Particularly confusing to me was what the heck display: inline was doing to HTML. Before I grasped the concept, I was already supposed to be learning a new property, display: block-inline. The display property essentially controls how (or if) the HTML element it is styling is displayed on the page. After poking around the Internet, I found the easiest way to describe how inline styles an element is that it places it next to the element directly before on your HTML map. That is to say, it places it INLINE with what ever comes before it. What tripped me up at first however is that if an object is set to display inline, its size can not be altered to anything bigger or smaller than to display the content that is is made of. That means if you set a single word <p> inline, it will appear as only that one word on the same line as the object that came before it. This is useful sometimes, but other times you need to the size and/or borders/margins/padding to be displayed as well.
  



As I found out, that is where block-inline comes out to shine. Block-inline does too things; first it makes sure to display the HTML element as a block display (think text box or image). This means that the object maintains what ever changes in size and or border/margin/padding have been made to it using other CSS properties. THEN it puts the object inline with the element that comes before it in the HTML tree. 




TL;DR
display: inline is used to place an object 'inline' with the object that comes before it, forgoing any changes to the objects size
display: box-inline is used to place an object 'inline' but allows you keep any changes to the objects size


Again, this is my basic understanding of these concepts, and I am still a beginner, so I apologize for any unintended mistakes!
