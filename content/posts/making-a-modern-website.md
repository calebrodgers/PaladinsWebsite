---
title: "Making a Modern Website That's Blazing Fast and Secure Using the JAMstack"
date: 2020-09-08T12:00:00+09:30
draft: false
author: Caleb Rodgers
featured_image: "post-content/jam_image.png" # Relative to cloudinary. i.e. post-content/image.jpg
---

A little while ago, I had decided that I wanted to create a new personal website. As I've got skills in traditional web languages (HTML, CSS, JS, etc), I wanted to get my hands dirty and write a website from scratch with completely custom code, allowing me to have a completely bespoke website, unique to my brand without using some cheap template that 100's of other have. On the other hand, though, I also wanted a solution whereby I could easily manage my website's content without having to manage many files (with mostly repeated code) and so I was looking into various CMSs (WordPress, Drupal, etc). For about a year, I had settled on running my old website, [calebjrodgers.com](https://go.calebrodgers.com/OldWebsite) with WordPress on the cheapest web host I could find. While this *worked*, I was unhappy with the flexibility to control every aspect of my site and was also concerned about the potential security risks of running a website with 'many moving parts'. In addition to all of this, my website was *slow*.... really slow, achieving a [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) score of only 54 on mobile!

> I needed a solution. I wanted to run my own code, but I also wanted a flexible and fast website, so I started digging, and it was at this point I discovered the *JAMstack*.

# The JAMstack...
**JAM.** Not just something to spread on toast, but an acronym for **J**avaScript, **A**PIs, and **M**arkdown. The core focus of the JAMstack is to move away from running a whole site off of a complicated server that generates pages each time a user visits it, but instead, creating a static site, that is only built once and the same files can be served to many users, drastically increasing performance. Although the site is 'static' it can still have functionality thanks to the use of JavaScript and APIs. Markdown is a portable language where plain text can be formatted with special syntax, that software can convert into rich text. Markdown can be used to write documents, notes, books, and is supported by GitHub and Reddit. In the JAMStack, markdown can be used to efficiently write content that can later be converted into HTML files at build time. This very post is written in markdown!

# Go, Hugo!
JAMStack sites are built around a static site generator (SSG). The role of the SSG is to take all of a site's content (Markdown, etc) and use a predefined template to generate HTML files for every page. This is only done once per build. There are many SSGS to choose from, such as [Jekyll](https://jekyllrb.com/) and [Gatsby](https://www.gatsbyjs.org/). However, after much testing, I chose to settle with [Hugo](https://gohugo.io/). Built off of the [Go Programming Language](https://golang.org/), Hugo is blazing fast, taking only around a few milliseconds per page to build. I find Hugo very well structured and easy to work with. Designing your own custom themes is an absolute breeze, however, Hugo also has a [huge library of free themes](https://themes.gohugo.io/) if you want to set up a website quickly (see [A New Hugo Site in Under 2 Minutes](https://www.youtube.com/watch?v=w7Ft2ymGmfc)).

# Netlify? Nice!
After the website has been built, it still needs a place to live on the web. In order to actually host the website, I still had to choose a service that would host all of the static files for the site, and in a very short time, I discovered [Netlify](https://netlify.com). It was love at first sight. I could go on for ages, but I'll just list a few of the many benefits Netlify provides.

* Netlify connects to GitHub, and automatically rebuilds the site whenever there is a change.
* Netlify deploys to a *global CDN*, so the website is blazing fast 
* Netlify allows you to use your own custom domain, at no extra cost! (They do sell domains, however, you can use your own for free)

Sound good? It gets better! Netlify is completely *free!* While, they do offer paid account options, with extra bandwidth and functionality, most people will be able to get away with running a simple (or complex) website free of charge!
