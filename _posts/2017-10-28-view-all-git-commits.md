---
layout: post
title: "How to view git commits across branches"
date: 2017-10-28
categories: git
tags: git
image_path: "2017-10-28-view-all-git-commits"
---
When I was starting out with git, I would wonder where is Feature Branch A in relation to master or where is Feature Branch B in relation to Feature Branch A. I came across this useful command, and have given it an alias in my .bashrc because I use it so much.
{% highlight bash %} 
    git log --graph --all --decorate=full --oneline
{% endhighlight %}

<div>
{% include image name="graphit.png" caption="Example output from the command" %}
</div>