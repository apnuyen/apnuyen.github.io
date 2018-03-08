---
layout: post
title:      "CLI Data Gem Project"
date:       2018-03-08 01:44:23 +0000
permalink:  cli_data_gem_project
---


*Write a blog post about the project and process.*
The concept of my first portfolio project is fairly simple - pull a list of the top 10 best books from last year, according to the New York Times and allow users to select a book to find more info on. 

It took a few tries to get the setup right. At first, I tried following closely along to the videos provided in the following lessons, namely the ones on the "daily-deal" gem. This helped a lot in terms of understanding the general setup process and hearing Avi walk through the thought process for where to start, etc. But when my code wasn't working out the way I wanted, I realized I needed something that would scrape data and sort it into an array, which the specific example I was following wasn't doing. 

After working through how to do that (i.e. redoing almost all the code I set up), I got it to work and display the list of books but some empty artifacts kept coming up. I couldn't figure out where they were coming from but their existence messed up the count, so instead of 10 books, I got a list of 14 (with 4 empty array objects). A quick google helped to eliminate those empty objects. From there it was a bit easier to manage. 

I'm having some trouble right now, just turning the thing into an actual gem, but the app itself works and it's a huge milestone for me! I need to record the walkthrough bit and I'm nervous about that just because it's so simple, I'm not sure how much needs to be talked through.  

If you fancy checking it out and giving some pointers: https://github.com/apnuyen/nuyen-cli-data-gem-project/tree/master/best-books 
