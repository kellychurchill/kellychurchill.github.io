---
layout: post
title: "Site Refresh"
date: 2016-07-30
---
<p>I have finally launched a long overdue refresh of my personal site and blog.</p>
<p>A few years ago, I decided to set up my blog and because I am a) cheap and b) a lazy developer, I decided to use Google's Blogger tool. After all, I already had a Google account and it is free so why not?</p>
<p>Well that functioned well over the years but the look of it is somewhat lacking and since I am a developer, I can actually do something about that.</p>
<p>So this weekend, I started looking at my options for a refresh. First, I thought about standing up a Wordpress site. But then I had to figure out where to host it. I have a cloud hosting server for the Girl Scout cookie booth site I run but it is configured for PHP and runs the site in Laravel 5.1. So then I started looking at Laravel blog solutions. While those seemed pretty simple to get up and running, I didn't want to build in PHP since I already knew how to do that. I wanted to try something more modern and expose myself to some new front end technologies.</p>
<p>So then I thought about Github pages. I started looking at options there and discovered the Jekyll framework that Github is built on and how straightforward it can be to set up a blog using markdown and a prescribed site structure.</p>
<p>I found this article with a really great overview of how to set up your personal site on Github: Creating and Hosting a Personal Site on Github http://jmcglone.com/guide/github-pages</p>
<p>So I set about setting up my blog. But what to do about all of my 6 years of past blog posts? I found this great node module that converts a Blogger XML export file into markdown posts: Blogger to Jekyll http://blog.slaks.net/2013-05-31/migrating-from-blogger-to-jekyll/ and easily convered all of my blog posts. I had to do some updates but for the most part they came through in great shape.</p>
<p>In addition to my blog, though, I wanted pages for About me and my Resume and a place to put my recent presentation materials. I also wanted to avoid jQuery, make it responsive and to use SASS http://sass-lang.com/. I decided to use the Skeleton CSS boilerplate http://getskeleton.com/ for the CSS framework. It is very lightweight and takes care of a lot of the responsive concerns for me. </p>
<p>I still have some work to do but I was able to get the blog, resume and about pages up and running very quickly and I have a nice clean UI to start with. </p>
<h2>To Do:</h2>
<ul>
  <li>Point domain to github pages</li>
  <li>Better formatting for blog listing page - categorize by year?</li>
  <li>Better formatting for blog post template</li>
  <li>Headshot photo shoot and add to site</li>
</ul>
