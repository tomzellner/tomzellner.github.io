---
layout: post
title:  "Classes in Ruby"
date:   2015-03-8 09:17:32
categories: jekyll update
---


One of the most basic and important concepts to understand in Ruby, is the concept of the 'Class'. Now technically, most of the 'puzzle-pieces' in Ruby that I have learned so far at DBC are actually one of the pre-loaded classes that Ruby naturally understands. Now I didn't realize this at the time, but thats just because I hadn't learned what exactly a class was or what that they even existed yet! More simply put, objects like Integers, Strings, Arrays, and Hashes are all examples of pre-made classes that Ruby naturally understands, but this week I learned how to make my own.    
 
When You create a new class, you get to assign instance variables and instance methods that will apply to everything that is included inside of the newly created class, something that is extremely useful, especially in terms of writing code efficiently. I think the easiest way for me to describe this will be to show you how to create a new class along with instance variables and methods that will be associated with it, in proper syntax of course. So here we go:

<br>Class NewClass
 <br> def class_method
  <br>  @new_variable == [1,2,3,4,5]
 <br> end
<br>
  <br>second_method
  <br>  p @new_variable[2]
  <br>end
<br>end 

    

Now this is of course an oversimplification of what would likely be 'real-world' code, but I think it will do for the purposes of explaining the functionality of custom classes and thier instance variables/methods. The custom class made here is called NewClass, and it encompasses two instance methods, class_method and second_method. These methods can be run on any new object that is classified as under NewClass. @new_variable is an example of an instance variable. These things are really cool. Basically you can use an instance variable anywhere in the class once it is defined. With out this tool we would have to type out the array of integers in created in the class_method anytime we wanted to use this array. It may not seem very useful in this simple example, but once things started getting even just a little more complicated, it can really save some time. The things is its way more useful than just as a shortcut. Instance variables can be used both destructively and non-destructively, so the variable can actually change over time through out the construction of a class, or in some cases, even with in a specific variable method


Hopefully this simple description of classes in Ruby has peaked your curiosity enough to dig a little deeper and learn more. I know the materials I covered this week had a similar effect on me, and since I know there is a lot more out there for me to understand, even in regards to the very specific subject of Classes in Ruby, I can not wait to learn even more.
