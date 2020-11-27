---
title: "A Comment on Comments: Looking for a Complex Solution to a Simple Problem" # Post title. URL of post is filename.
date: 2020-11-27T14:18:45+10:30 # Date and time of posting
draft: false # Set this to false to publish the post
author: Sir Caleb # Author's display name. i.e. Sir Somebody
author-image: /img/team/sir-caleb.png # Relative link to authors image
---

Code comments. They’re a great way to keep little notes in your code so you know what does what, and even better for sharing code with other people! Good comments can encourage easy and open collaboration and make code easy to follow. There are times, where comments can go rogue!  

Today, the programming team was tasked with preparing the servo for the gauntlet arm on our robot, Joyeuse. While the build team were busy doing some hands-on work with the robot, Sir Brad and I got to work writing some code that allowed the robot operator to toggle the arm up and down. When the time came for us to get our hands on Joyeuse, we used a REV servo programmer to configure the left and rightmost points of movement for the servo.  

After this, we connected the servo to our control hub and…. Nothing! Thinking there was potentially an issue with using a REV servo programmer to configure a GoBilda servo, we spent around 10 minutes searching for our GoBilda servo programmer. After reprogramming the servo, again, nothing.   

We then spent a further 20 minutes bumbling around trying to figure out what was wrong. We checked connections, looked over hundreds of lines of code, but no matter what we did - we could not get the servo to work! After feeling like we had reached a dead end, I opened the configuration file and scrolled down to lines where the servos are added. The very line that we needed was commented out :(. Not good! After commenting it out, we found that the initial code that Sir Brad had written worked perfectly!  

While we could easily blame the programming team for a simple mistake, today proved a great learning exercise. Don’t assume that simple things (such as a configuration file) are working properly. Rather than trying to find a complex solution, look at the basic things first, is it plugged in? Is it on? Is it configured? If we had checked the configuration first, we would have saved about half an hour!
