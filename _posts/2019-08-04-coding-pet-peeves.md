---
layout: post
date: 2019-08-23
categories: development
---

<div class="blurb">
  <h1>Coding Pet Peeves</h1> 
</div>


## Where to Begin
We all have them. Those things we need to tolerate during our daily travels through the development landscape. Those things that hit us deep in the core of our very being. Those frustrating things that sometimes make our lives much, much harder. Ok, I'm being a bit dramatic. But seriously, we all have a list of coding pet peeves. In this post I will describe my biggest pet peeve, topped off with some venting.

## Variable Names
It bothers me when variable names are too succinct and not well thought out. I get why - it's faster to call something "a" instead of "appointment", or "appt" and we do a lot of typing so why not try to reduce some it, right? __Wrong.__ Wrong, wrong, wrong. This strategy might work fine for right now, but what if you have to revisit this code in two months because a Support representative is using your new feature and has a question about how it works? Are you 100% sure you're going to remember the intention behind naming that variable "a"? Are you 100% sure you won't have to search for the declaration of "a" to see what it's used for and why it was created? You are? Awesome. You're that much better than myself (I have a really bad memory). 

## The Juice *Is Not* Worth The Squeeze
Even if your memory is better than mine, chances are you won't remember the story behind that particular variable name which means you're costing your future self valuable time. Furthermore, you may have to provide some training to your peers or to a technical support team about how the feature works. Since you're not the only person reading your code its in everyones best interest for your code to be self documenting.

> Time is the most valuable asset you don’t own. You may or may not realize it yet, but how you use or don’t use your time is going to be the best indication of where your future is going to take you. - Mark Cuban

I put a lot of time into naming my variables - probably to a fault and I need to get better at that. I once read about a strategy to help with this. In summation, you quickly name the variable something just to get the logic down, but then you go back to rethink the name. Just like refactoring code, you refactor variable names. I should be able to tell exactly what the code is doing by reading the story outlined by the variable names and the simple flow of the code. 

> So long... partner. (Toy Story)

<br><br>
#### Works Cited:

*Toy Story 3.* Dir. Lee Unkrich.  Walt Disney Pictures, Pixar Animation Studios, 2010. Film.
