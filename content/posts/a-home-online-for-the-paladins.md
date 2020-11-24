---
title: "A home online for the Paladins" # Post title. URL of post is filename.
date: 2020-11-23T14:18:45+10:30 # Date and time of posting
draft: false # Set this to false to publish the post
author: Sir Caleb # Author's display name. i.e. Sir Somebody
author-image: /img/team/sir-caleb.png # Relative link to authors image
---

A few days ago, it was decided that setting up a team website was a priority as we are approaching the nationals. Unwilling to settle with a basic Wix or Weebly website, I worked through the night of Friday, the 20th of November and into the early morning of Saturday the 21st, coding up a brand new website from scratch with HTML and CSS.  

While a simple HTML website is cool and can look good, the team decided that the website would be a great platform for outreach with the opportunity to publish some of our team content such as journal entries. Another piece of criteria was the website be open-sourced on GitHub, just like our robot code, to inspire and help other teams. These two needs were able to be solved as one, thanks to a little bit of software called Hugo.  

Hugo is an open-source static site generator. A static site generator allows for all of our content and the layout HTML to display that content to be stored in a folder (in our case, a Git repo) and every time a commit is made to either the content or design of the website, Hugo goes through and automatically assembles all of the necessary files and builds a completed website, which for us, is hosted on a free service called Netlify.  

This is an efficient way of running a website, as all of our team members can write and publish content as Markdown files through GitHub, and the website can, in real-time, respond to such changes and adapt accordingly. All this without having to worry about clunky and slow content management software, or heaps of  HTML files for each post, which can get very messy, very quickly.
