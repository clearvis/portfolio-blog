---
layout: post
title: "Generate Blog Using Jekyll"
description: "This post is an explanation of how I came about using a Ruby Gem called Jekyll to generate my blog"
categories: 
 - development
 - ruby
tags: [ruby,jekyll]
imageURL: jekyll-post.jpg
published: true
---

Installing Jekyll 
=========

Jekyll can be installed easily as a [Rubg Gem](http://rubygems.org/ "Official download page") from the source using your terminal window. Full instructions explain how it's [installed](http://jekyllrb.com/docs/installation/ "External link to Jekyll Instructions"), with a link provided if you need to install on a Windows OS.

Advantages Using Jekyll and Ruby over CMS 
-----------

  - Pure HTML 
  - Compiled from simple markdown files
  - No database dependencies
   
### Available Features

* Pagination
* Comments Using Discus
* 404 Error Page
* Social Sharing
* Publish Files With Github

What convinced me to go about using Jekyll to create my blog was being able to accomplish it without the need for WordPress, and its heavy dependence on a database, and reliance on media libraries. My inspiration came from an artcle wriiten by [Donovan Hutchinson](http://hop.ie/blog/your-own-blog-1/ "Your Own Blog Part 1") that gave step by step instructions on how to create the layout.

To get started on the project I downloaded the template [Jekyll boilerplate by Necolas](https://github.com/necolas/jekyll-boilerplate "Available on Github") that includes a **README** file explaining the layout, and configuration files.

Once your Markdown files are placed into the *_posts* folder, you can run `jekyll build`, which will compile the files into the *_site* folder. Deployment to your live website can be accomplished by using FTP, or easily using [Github Pages](http://jekyllrb.com/docs/github-pages/ "Direct your site to Github"). 
