---
layout: post
title: On Learning How to Program
date: '2017-04-23 22:04:26'
comments: true
tags:
- programming
---

This morning I saw a tweet on my twitter feed that surprised me.  I thought at first that it was supposed to be taken as a joke, but as I read the replies it became apparent that was not the case.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Young programmers are better off not starting with the theoretical foundations of CS, but by eagerly writing crappy programs.</p>&mdash; Paul Graham (@paulg) <a href="https://twitter.com/paulg/status/855343017993043969">April 21, 2017</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

### Some History

I got my start in programming at a fairly young age.  When I was 11 years old I got my first computer and I had very little interaction with computers before that time.  I was extremely interested in how they worked and quickly broke it (we had to take it back to the store and exchange it for another one because Windows 3.1 would no longer start).  Shortly after that I got a copy of the [Slackware Linux Unleashed](https://www.amazon.com/Slackware-Linux-Unleashed-Tim-Parker/dp/0672310120) book and learned how to install and run a Linux system.  My first programming experience was not actually on the computer but on a TI-82 calculator.  I had several of these over the years, a TI-82, TI-83, TI-85, and TI-89.  I would program video games on my calculators that were very simple.  First a basketball game and later a [Tele Arena](http://breakintochat.com/wiki/Tele-Arena) clone.  My friends soon wanted to have their own copies of these games on their calculators and so I started to re-program the games into their devices (I didn't have any money to buy a transfer cable at the time).  Of course that helped me a lot because as I wrote these games over I would inevitably improve them.

By the time I got to college I had a fair amount of computer experience under my belt.  I first started programming in a class that was required for my major (Geomatics Engineering at the time) and ended up loving it.  Because of that I eventually switched my major to Computer Science.  The introduction to data structures course that I took first was far more difficult than the previous programming course I had taken.  Linked lists were a foreign concept to me.  In any case I started doing well and in fact on my first exam I got back the professor told me "they might want to stone you" as he handed me my paper.  I guess I had gotten the highest grade in the class.

### Back to Twitter

So what does this all mean about the Tweet above, if anything?  In some sense I guess it's true, that you have to just start writing code at some point, but I still find that until I understood theory I really didn't have much of an understanding of what I was doing.  For those who don't have a Computer Science background a computer can seem like a black box.  Yes, maybe you're able to write some code and you figured out how to make things work -- that by giving certain inputs you receive certain outputs.  But you really don't have a clue what's going on inside that black box.  How can you make good choices for data structures if you haven't been taught them?  How can you reason about time complexity?  How can you really understand memory allocation?  We've solved all that by having highly optimized compilers, dynamically typed languages, and efficient garbage collectors.  There, now you don't need to understand any of those things!  Just hack away at your code and hopefully it works.

This is an absolute recipe for disaster in the world we live in today.  We are no longer writing simple programs that run on a single computer disconnected from the rest of the world.  Most software that is written is available in the form of a web or phone application and as long as the application has a nice looking interface we assume that it is also well written and secure.  Engineers (or those aspiring to be) should be held to a higher standard.  People trust us to write good software and also to respect their privacy.  There is enough broken software loaded down with technical debt in the world.  We shouldn't be encouraging programmers to continue this trend.

### Parting Words

Programming and theory are both of great importance in becoming a programmer.  You can't have one without the other.  Deficiency in either area will not make you a well-rounded engineer.  I would recommend to anyone who is interested in beginning to program to learn the theory _first_ and then apply what they learn in code.  This should be the pattern: constantly read and apply.  I would liken programming without theory and study to learning to play the guitar without understanding the basics.  How can you learn to play a guitar without first understanding some music theory, notes, and chords?  Sure, you can make some noise and maybe sometimes it accidentally sounds okay, but it's never going to be good music.  The worst part is that you will learn some very bad habits that will solidify over time.  Eventually you'll learn you are holding your guitar the wrong way and strumming it the wrong way and now you have to unlearn all that muscle memory.  It's the same way with programming.  Learn it right from the beginning and build great software.  Stay as far away from the sites like StackOverflow as you can as they'll just make you dependent on using other people's ideas and hard won wisdom.  And of course, enjoy yourself!