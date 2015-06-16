---
layout: post
title:  "Ruby: Arrays vs Hashes"
date:   2015-02-22 09:17:32
categories: jekyll update
---


This week, the final week of my first Unit at Devbootcamp, we learned about the two different ways to store collections of data, most commonly objects, in Ruby. What that means is the both Arrays and Hash can store and organize data in one place, meaning you can keep relative information all in one place, and not have to worry about where it is or how you will find it.
 


I'll cover Arrays first, because that how we did it in DBC, and I think it'll make Hashes easier to explain later on. basically you name the array, generally pertaining to the kind of information or objects you plan on storing with in it, and follow it by an equals sign, and then the objects in question separated by commas, and all with in one squared bracket. so something like this: array_name = ['thing1', 'thing2', 'thing3']. Make sure that all strings are surrounded by quotes! Accessing the information inside is really simple too! everything inside of the array is automatically given a number that works like a key to the data. The only tricky thing you have to remember is that the key list starts at 0, not 1. so if we wanted to refer to thing2, we would simply have to type array_name[1]. you can even count backwards, so its almost like each object has two keys. array_name[-1] would refer to thing3 in our example.




Hashes are really cool because you get to generate the name of your key as well. essentially Hashes work pretty much the same way, but their syntax is a little different. There are a few different ways of starting a new Hash, but this is the way I learned it. Again you begin with the name of the new Hash followed by and equals sign, but this time its a squiggly bracket. Then proper syntax would be do hit enter and start a new line for the first piece of data. The name of the key comes first followed by and equals and a greater-than sign (making an arrow). Enter the object you wish to be stored followed by a comma Then hit enter and start the next piece of data on a new line. In the end it should look a little bit like this:<br>
hash_name = {<br>'key1' => 'object1<br>'key2' => 'object2'<br> 'key3' =>'object3'<br>}<br>
Learning about Arrays and Hashes was challenging, but totally rewarding, as I already found them very useful throughout this weeks challenges!
