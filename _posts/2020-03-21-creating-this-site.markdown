---
layout: post
title:  "Creating This Site!"
date:   2020-03-21 22:04:15 -0500
categories: about this site
---
When I set out to create this site, the main goal was not to create a nice looking site. It wasn't to display my personal information to strangers. The goal was to learn how to use the tools that make web development possible.

One of the first things that I learned is that if I did just want a good looking site, learning programing wasn't necessary. There are lots of platforms like wix or Squarespace that will make creating and hosting a site easy, and free up the end user to concentrate on the graphic and flow of the site. But I knew that that wasn't my goal.

In programing, the language that is used for a site can get a lot of attention. I have more experience with python than any other language, so I thought that it might be a good fit. I have made simple sites using the flask framework, such as the demo project that I created on repl [here](https://repl.it/@gib_jeffries/MGJ-SimpleFlask). The python+flask setup might be a good fit for some people on some projects, but it turned out not to be a great fit for me on this project. More on that in a minute.

After working on the flask project on repl.it for a while, I realized that the programming language was only part of the web development process. The code for a website can't do anything by itself. It has to be hosted by a server with the right programs and packages installed to run that piece of code, and has to be hooked up to a domain name to host that code to. More that that, for the site to be useful, it should be easy to modify and restore, which means that every bit of this process should be backed up and recoverable. In other words, it should be in version control!

Hosting this site through github pages using Jekyll was the natural conclusion to my new appreciation for version control, and my lack of enthusiasm for managing packages and programs on my local device. The workflow for locally testing out changes, pushing up those changes to a branch, and then pushing those changes to master when I am ready to deploy to production is very convenient. I've learned that sometimes the right language isn't as important as the right production tools.