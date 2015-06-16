---
layout: post
title:  "Git and GitHub Through the Eyes of a Beginner"
date:   2015-02-06 09:17:32
categories: jekyll update
---
Version Control Systems maybe the most helpful tool that many outsiders of the programming community have never heard of, or at least have not realized they already know they understand. The concept is easy enough; a Version Control System, or simply VCS, is a tool that is used during project management in order to keep track of specific 'checkpoints' through out the life of a project. This simple concept provides its users a number of useful benefits, though in my eyes the most useful of these is the sense of security it provides as a safety net. In programming and web development it means that you don't have to feel worried about making a mistake by trying something new or possibly innovative, because if you mess up too badly, you can always go back to something that worked. It allows you to document each 'checkpoint' every step of the way, ensuring you always know how you got where you are.

Git is the VCS I learned this week, which specifically helps manage changes on a local terminal. It does this through a system of 'checkpoints' it calls commits. With each new commit, you are required to submit a commit message, helping document what has changed with each official 'save'. Git makes it easy to view these commits as well as the commit message assigned to it. Rather than have numerous different versions of the same project, git works by having one master file that can be branched off and worked on while the master copy remains untouched. When its time to commit to the next checkpoint, it is simple enough to merge the new branch with the master file. No need for 100 different file versions.

GitHub works (and sounds!) very similarly to git, but fulfills a different need. If git is a VCS for locally working on files, then GitHub is for operates as a VCS for the shared aspects of a project. GitHub is simply put a website for collaborative work between programmers and developers. It allows individuals to work independently on branched copy of a master file that is shared by everyone on the project. It is an incredibly useful and easy way to ensure that everyone is working on the most up-to-date 'checkpoint'. It also allows its users to send their work to other project members for review before it is officially merged with the master file.

These descriptions of VCS, git, and GitHub is merely the reflection of a beginner hoping to explain these things in layman's terms, so please forgive me for any unintentional ignorance.


<!-- {% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].
 -->
[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
