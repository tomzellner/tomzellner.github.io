---
layout: post
title:  "The count Method in Ruby"
date:   2015-03-01 09:17:32
categories: jekyll update
---



Today I am going to talk about the Ruby Enumerable method .count. It is actually simple enough to understand, but in order to do so first we need to understand what exactly an Enurmerable method is in the first place! Basically for a class to be able to use an enurable method it must be able to define an #each method. Most of the classes that can do this turn out to be data collection classes, which for most beginiers like us means Arrays and Hashes. For classes that fall into this catagory, their are a number of methods called Enumerable methods that will work for each one.
 
.count turns out to be one of these Enumerable methods. In its most basic use, it does exactly what you would expect it to do; it counts the number of data points in the array or hash. for example if you have array=[1,2,3,4,3,2,1], array.count would return #= 7.



The count method can do more than just that however. It can also count the number of times a single data point is repeated. Using the same array from our previous example, array.count(3) would return #=2, since the object 3 occurs twice in the array.


The .count method has one more trick up its sleeve. If .count is given and object and a block, it will return the number of times that the argument comes back as true. For example, when using the same array example, array.count {|x| x%2==0} would return #=3, since their are 3 instances where the remainder of x/2 is equil to 0 (2, 4, and the second 2)

Enumerator methods can be extremely useful, as they generally have a number of important uses. One thing that makes them particularly common to use in ruby is the fact that they apply to a number of different classes that are themselves used frequently in ruby, like Hashes and Arrays.

