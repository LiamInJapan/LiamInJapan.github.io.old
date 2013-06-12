---
layout: page
title: Hello, World
tagline: 
---
{% include JB/setup %}

Hello and welcome to my blog. Here I hope to share with you some of my thoughts, ideas, concerns, notes and anything else that might pop into my head on my (very) long and winding path to programming mastery. 

At the moment I am primarily an iOS Developer, so my posts are likely to be related to Objective-C and the iOS platform. However, I have been known to be somewhat of a dabbler, and recent dabbling has also included plenty of C# and Python. I believe in the right tool for the job, and I believe a good programmer should understand and appreciate the wealth of languages and tools available to them out there, and understand where and when to apply them. I hope you enjoy!
    
## Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


