---
layout: post
title:  "Assignment 1"
date:   2015-11-16
comments: true
categories: jekyll update
---

##What do you think of pre-compiling your CSS?
* ####Compare to regular CSS?
* ####Which techniques did you use?
* ####Pros and cons?

I think that pre-compiling your CSS is a great way to optimize the language when you get used to it. It enables you to use nestling which i believe
makes the code a lot more logical and easier to read. To be able to divide your CSS into smaller files is also neat, not having to scroll trough one file with x-rows of code to find what you want.
Not needing to repeat yourself using variables is also a great thing, the same goes for small calculations and mixins.
 I tried out using nestling and variables in my code. Mixins are used for the media-querys
but thats the standard code that came with jekyll. Using CSS preprocessors has a few downsides as well. The code becomes
more complex and harder to debug. You will need more tools for it to work and the building time of the site will increase.



##What do you think of static site generators?
* ####What type of projects are they suitable for?

I think site generators are great, not having to repeat the same code over and over again is awesome! From other experiences
 I can say that it was the most unnecessary and time consuming thing ever. So to have the possibility to use partials/includes for
 the header, head and footer is great. Using markdown was a new experience for me but now that I'm more used to it I really like
 it and I think its a great tool that comes with the SSG that we are using. The static site generators are suitable for sites
 where you don't have dynamic content and just want to post information about an association or a blog for example.


##What is robots.txt and how have you configure it for your site?
Robots.txt is a file where you give instructions about the site to web-robots, such as search engines like google.
In the robots.txt file you declare what content you want the web-robots to index or have access to. I have configured my file so that no
content should be available for the robots, but this does not guarantee that robots still goes through your site.

##What is humans.txt and how have you configure it for your site?
Humans.txt is a file where you list the people who developed the website and other people who contributed.
You can also add the tools you've used during the development and so on.
In my Humans.txt i have information about myelf and a few tools that i've used to develop this site.

##How did you implements comments to blog posts?
I used the recommended service Disqus which is free of charge. I had to create an account on their website and then
 they generated unicode which i used in my layout for the posts on my site. I can use comments anywhere i want on the site
 by using the code i got and add a front-matter "comments: true". But for now I'm satisfied with people only commenting on my blog posts.

##What is Open Graph and how do you make use of it?
The open graph is a way to turn a web page into a graph object by simply adding a few meta-tags to your html code.
By doing this you can choose how your page will be represented when linked into social media for example.
I've choose to only add the four standard meta-tags title, type, url and image.


