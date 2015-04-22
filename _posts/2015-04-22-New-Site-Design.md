---
layout: post
title: "Post 2.0: New Site Design"
author: William Stevens
date: 2015-04-22 12:00:00
categories: jekyll update
summary: Changes made and lessons learned from the site redesign.
---
# What's changed?
* I've added a new projects section to keep my project logs separate from day-to-day postings.
* I moved some elements of my portfolio site onto this site to give the site a more uniform look (the old version is at [portfolio.wastevensv.com](portfolio.wastevensv.com))
* The subdomains have changed. This site used to be blog.wastevensv.com, which is now www.wastevensv.com. www.wastevensv.com is now portfolio.wastevensv.com.
* I've also added links to my Google+ page and my Twitter account (both of which are rarely used).

# What didn't change?
My original plan for the redesign was to use a template from [HTML5 UP](html5up.net) and modify it to work with Jekyll. While I could have done that, it would have meant that I would be using code that I didn't fully know. The point of this site right now is to give me a way to learn how to manage a site and work with HTML on a large scale.

Also, to use one of those templates would have involved serving Javascript as a part of viewing the site. I plan to stick to plain HTML+CSS with this site. I have nothing against Javscript. For sites that need interactivity (like [ScoutNet](https://github.com/wastevensv/ScoutNet) or [MDEdit](http://www.wastevensv.com/MDEdit/)) it makes perfect sense to use Javascript. Its just not needed on a static site. 

In addition I had planned to use [namecheap.com](https://www.namecheap.com/) for a domain name and then only use [GitHub Pages](https://pages.github.com/) for static hosting. However it turns out that Namecheap does not allow the ALIAS or ANAME records to be configured. This would be needed to take advantage of the GitHub Pages load balancing network. So for now, I'm still using [NearlyFreeSpeech.net](https://www.nearlyfreespeech.net/) for hosting the domain name and my portfolio site and using GitHub pages for this blog.

I also wanted to add CSS transitions to some parts of the site, such as navigation bars and maybe the project gallery at the top. Eventually I got to the point where they were working separately, but I never integrated them into the site simply because I thought they were excessive. I might put them in later on if I find a way to do them right.

# Lessons Learned
When I had finally finished working on the code for this site, I wanted to get it up as soon as I could. This led to rushed decisions and some mistakes. When switching over subdomains, I had started with taking down my portfolio and my blog site. Now I realize I probably should have configured the new subdomains first, then removed the old ones to minimize downtime.

# Whats next?
Next, I plan to work on making [Godddard](http://jimmyneutron.wikia.com/wiki/Goddard). So far my plan is to use a gutted Roomba, an old cell phone, an Arduino with a motor sheild, and a headphone cable. More on that in a future part of the projects section.