---
layout: post
date: 2019-08-04
categories: development
---

<div class="blurb">
  <h1>Coding Pet Peeves</h1> 
</div>


## Where to Begin
We all have them. Those things we need to deal with during our daily travels through the development landscape. Those things that hit us deep in the core of our very being. Those frustrating things that sometimes make our lives much, much harder. Ok, I'm being a bit dramatic. But seriously, we all have a list of coding pet peeves. Here's a few of mine topped off with some venting.

## Variable Names
I think this one might be at the top of my list. It bothers me when variable names are too succinct and not well thought out. I get why - it's faster to call something "a" instead of "appointment", or "appt" and we do a lot of typing so we not try to reduce some it, right? __Wrong.__ Wrong, wrong, wrong. This strategy might work fine for right now. But what if you have to come back to this code in two months because a Support representative is using your new feature and has a question about how it works. Are you 100% sure you're going to remember the intention behind naming that variable "a"? Are you 100% sure you won't have to search for the declaration of "a" to see what it's used for and why it was created? You are? Awesome. You're that much better myself (I have a really bad memory). 

But, chances are you won't remember which means you're costing your future self valuable time. Plus, you'll have to provide some training to your peers or to a technical support team about how the feature works which means you're not the only person reading your code. 

> Time is the most valuable asset you don’t own. You may or may not realize it yet, but how you use or don’t use your time is going to be the best indication of where your future is going to take you. - Mark Cuban

I put a lot of time into naming my variables - probably to a fault and I need to get better at that. I once read about a strategy to help with this. In summation, you quickly name the variable something just to get the logic down, but then you go back to rethink the name. Just like refactoring code, you refactor variable names. I should be able to tell exactly what the code is doing by reading the story outlined by the variable names and the simple flow of the code. 


doing too much in a stream
not enough logging
bad comments
not updating comments as development goes along
no unit tests

> So long... partner. (Toy Story)

<br><br>
#### Works Cited:
*Toy Story 3.* Dir. Lee Unkrich.  Walt Disney Pictures, Pixar Animation Studios, 2010. Film.
