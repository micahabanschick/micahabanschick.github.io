---
layout: post
title:      " Sinatra Project: Acoustic Karma"
date:       2020-11-03 20:54:13 +0000
permalink:  sinatra_project_acoustic_karma
---


This is my mandatory blog post to record my thoughts and comments on my project. 

![thumbnail](https://document-export.canva.com/_LNgk/DAEMSq_LNgk/17/thumbnail/y_1GrbKgBGCF7LAQ35ynrw-0001-12565651679.png)
### Overview

I started my project with an idea that I might expand upon further down the road. That idea is a music-centric social-media platform. Think of Soundcloud have a love baby with Twitter. It was a very simple idea and was easy to implement especially for a Sinatra project. All I needed was a User, Song, Album, Genre, and Post model. I will create more complex models in the future, such as Comment, but I just wanted to focus on the requirements for this project. 

![homepage-with-url](https://media.giphy.com/media/Vy8i8M3PYlASn9bYM2/giphy.gif)
### Getting Started

This project was bug after bug AFTER BUG! Goddamn it I lost so much time going over stupid bugs that were resolved with a change of a character or change in the order or some other semantic BS. Although small bugs are always going to be a part of programming, I don't think I'll ever NOT get frustrated to all hell about it. The vast majority of the project took a very little amount of time to think over and code. Any significant amount of time only went towards tiny, TINY bugs.

One bug that I spent the most amount of time trying to figure out was a #require_all error. No matter what I seemed to do nothing worked. I even mimiced the formatting of previous Flatiron Sinatra lessons to narrow down the scope of errors. Eventually I noticed that few lessons had more than one controller, and the ones that did had controllers such as SongController or GenreController. I realized that I had an AlbumController which started with the letter "A." Therefore, myn AlbumController appeared before my ApplicationController. I didn't think order would have any influence on how it was run at all; it didn't even cross my mind. However, after relying on trial and error for any change that I could possibly think of, I tried adding "01_" to the beginning of the ApplicationController file name. That seemed to work.

![error-page](https://media.giphy.com/media/SnxetVXMeIfd6lK5wR/giphy.gif)
### Distractions

Over the course of this project there have been a few key distractions which have made consistent progress a bit more difficult. As I'm sure most of you are aware, a very important election is currently taking place. With every new story coming out, and tensions seeming to rise, I feel compelled to keep as much in the loop as passible. I hope that soon I can feel comfortable enough to ignore politics as a whole and go on with my normal life. Unfortunately, that is not the case right now. 

Also about a month ago my grandmother passed away. This took a big toll on the whole family. We all spent a lot of time with her and I would often spend my weekends staying over at her place to keep her company. However, the most affected person by far was my father. Right now time is the only remedy and he has been coping as much as possible, but our family as a whole and the atmosphere in the house has been fairly depressed. 

Ontop of that, the family has been pretty stressed and busy. My mom is busy and my dad hurt his knee recently so I've been picking up a bunch of errands throughout the day. It felt like almost every day I had to stop my work and take care of something family related for a while now.

![incredibles-sigh](https://media.giphy.com/media/ZmFRMf6hGMnf2/giphy.gif)
### Final Thoughts

I enjoy this level of complexity in programming and I likely will continue to enjoy progressively more complex levels of complexity to come in the future. This project was an interesting one. It more easily displayed how much closer I am to competing in the job market and I very much appreciate that. That being how programming often gives an immediate return value from what is made. Unlike a Biology major or an English major, I can pass through a module and clearly state what I can currently contribute in a real job with proof and experience of doing the work. 

In terms of my evaluation of this current project, I'd say that it displayed the requirements clearly and required use and knowledge of all the previous lessons in an effective way. In my personal opinion, the difficulty of the project was EXEEDINGLY easy. As long as the student retained knowledge from the lessons, the actual implementation of the different gems, models, databases, etc., was very easy to do and took very little time.

THAT SAID, I found myself getting caught up on various tiny genreal bugs which delayed my progress significantly. These are the type of bugs that I would be just as likely to get in any previous or future project, yet will probably become more managable with time and experience. I'm sure that I'll get used to being attentive to such detail over the years. However, I have not reached that level of competency as of yet, and so these bugs cause me a lot of trouble and frustration. Overall, I call it a victory if my troubles lie less with the focal material and more along peripheral details.

I am glad I finished this project and am looking forward to continuing onto Rails.

![puck-clapping](https://media.giphy.com/media/3o7buh8WbaZLupolXi/giphy.gif)

Thank you for reading!
