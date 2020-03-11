---
layout: post
title:      "My First Programming Initiative: Anilector"
date:       2020-03-11 19:52:58 +0000
permalink:  my_first_programming_initiative_anilector
---


Wow, I finally did it! And what an "it" it was. As of today, my first portfolio project for Flatiron as well as my first programming project PERIOD, is complete. If I'm being honest, it's been complete for the past 4-5 days, ..but I got a little nitpicky here and stuck in some details there and sometimes pushed incomplete commits that I realized needed more edits afterwards (I ended up with ~50 commits...).

Although the gem is nothing I'd gladly show an employer, my most troublesome pieces had little to do with the actual coding. In fact, the biggest, most frustrating, step in my process was setting up git on my local environment. I remember troubleshooting through it from 8 am to 5 pm. I used git installation instructions from multiple sources and kept getting errors. I used Google, Stack Overflow, Github, Youtube, and nothing I found seemed to work. I tried using ssh (after creating a new set of ssh keys on my computer) and after that didn't work I tried using https and that also didn't work. Then, suddenly, it worked. I still don't know why or how or what I did but I wasn't in the mood to be picky about it. I am very much glad to be past that step.

![](https://i.imgflip.com/3s7639.jpg)

Now that I could start with my actual project I immediately hit my second most frustrating step in the process: planning. It took two seconds flat to decide exactly what I wanted my gem to accomplish, but much more time to plan how to go about doing it. I knew that I wanted to create an application that would ask the user some questions and use the answers to pick anime to recommend to the user to watch. But, how? Believe it or not, I initially started with three sites to scrape: MyAnimeList, IMDb, and GoodReads. I decided to stick with only the first (and even still my program's Nokogiri methods are too slow). Beleve it or not I planned my whole project off of scraping info from all sites that would influence what to recommend the user. It wasn't very detailed but I took my plan to paper for about 5 days (I have a LOT of trouble with planning). And then I scrapped it and start anew.

Once I completed the setup and basic plans, I started with three classes: User, Scraper, and CLI. At once I decided I didn't like my class-name to have all-caps so I changed CLI to Interface, which sounds much smoother. By the end I watched a video suggesting gem-class-names to be namespaced according to the gem-name in order to prevent confusion around multiple classes with the same names, so I created a new module called Anilector and renamed my classes Anilector::User, Anilector::Scraper, and Anilector::Interface. In retrospect, Anilector::User is practically useless in function compared to the others..

My only othe problem in my proccess had to do with testing. I installed rspec and tried to create tests and sometimes they did what I wanted, but I had no idea what I was doing. Even now, I don't know how to get my tests to do what I want them to do. One of them matches up with my action method perfectly EXCEPT that the test doesn't convert special characters such as /n or /t into their viewable counterpart whereas it does for the test version. WHY! 

![](https://media.giphy.com/media/naiatn5LxTOsU/giphy.gif)

I tried writing tests with an rspec cheatsheet on another window but it made little difference. Eventually, I gave up on the tests and simply executed my files to see whether it worked. It did.

This next issue is something I don't, as a newbie programmer, know how to fix: the execution speed is SLOW! Inside my README.md file I mention that Anilector is a quick solution to finding anime...but the run-time is over two minutes. I almost feel like I should let people know "Hey! If the terminal cursor is unable to move or change its behavior at all, it's OK. It's supposed to do that. Just wait and by the time it would take for you to do the research yourself, it'll resolve itself."

Eh..

It's a work in progress. Although this is my submission for the project review, as soon as I become a little more experienced I'll greatly revise Anilector so that I could actually be proud to show it to a prospective-employer.

Meeks out!

![](https://media.giphy.com/media/eSwGh3YK54JKU/giphy.gif)


