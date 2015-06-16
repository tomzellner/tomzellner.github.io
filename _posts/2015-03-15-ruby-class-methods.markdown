---
layout: post
title:  "Ruby Class Methods"
date:   2015-03-15 09:17:32
categories: jekyll update
---


The class method is pretty simple to understand actually. Essentially it is a method that can be called on any instance of a Class. I don't thing that I've covered Classes yet in this blog, but essentially a Class is a tool in Ruby that is used to encompass a group of methods that are related to one another, whether it be in their function, or with the objects that they are interacting with. That probably isn't the strongest definition that you can find, but its the best that I can currently articulate. Remember this is only my 4th week working in Ruby. There are many other resources you can find to help clear up any misunderstandings of Classes in Ruby.




So the Class method will allow itself to be called on any instance of a the Class. This is the opposite of a instance method, which will only work on a single instance of the class, as specified by the programmer or user. In order to define a class method as opposed to simply a instnace method, you must be sure to include a 'self.' before naming the method. OK, so time for an example I suppose

class Blog<br>
      def self.example_method<br>
        p "class methods are great!"<br>
      end<br>
end



So with this code, Blog.example_method could be used to return "class methods are great!"
If we had just used an instance method (left out the .self), we would have had to call Blog.new.example_method, to do the same thing. Obviously this becomes more and more convenient, the more complicated the entire piece of code becomes.

