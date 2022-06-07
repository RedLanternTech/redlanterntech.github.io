---
layout: post
title: Adding Copyright to Posts
---

So I actually had two articles for today but I decided to go with just one and post the other one at a later date.  Something I noticed on other blogs is a copyright (not copywrite as I am prone to type) notice.
I figured it might be a good idea to add one in.  Honestly I am ok with someone linking back to my blog and if it helps someone out with a project, I am all for that.
This blog is learning experience for me and allows me to share my projects with others.  

After reviewing the pages and other sites, I wanted to have it added to the end of every posts.  [Jekyll Now](https://github.com/barryclark/jekyll-now) is a great base
to go off of since the pages are simple to read and easy to modify.  That was one problem I had with Wordpress on my Raspberry Pi 3b, trying to make changes to the theme or to little things seemed like a task.  
Markdown, HTML, and Jekyll are just easier for me to understand.  If I ever meet Barry Clark, I am going to have to thank him for [Jekyll Now](https://github.com/barryclark/jekyll-now). 

So going though the site, I figured to best page to modify was post.html under the _layouts folder.  Its original code looks like this

![2021-10-13-Image1](/images/2021-10-13-Img1.png)

I figured I could just throw in a similar line right below it and be done with it.

![2021-10-13-Image2](/images/2021-10-13-Img2.png)

That did not end well.  I forgot to screenshot it but it just printed the percent sign.  

After some trial and error, some resulting in just utter strangeness, I figured it was just best to duplicate the whole section

![2021-10-13-Image3](/images/2021-10-13-Img3.png)

And that resulted in what I wanted, the Copyright notice with the year along with my name.  

I liked doing this project this evening as it allowed me to get more familiar with adding images into my Markdown Posts.  Also it tested me a little and had a good
result when I got it right.  My girlfriend was the one that caught my spelling mistakes.  That prompted me to add in a spell checker into Visual Studio Code (my preferred code write at the moment).  

Until the next time, thank you and 73's