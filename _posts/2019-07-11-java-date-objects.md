---
layout: post
date: 2019-07-11
---

<div class="blurb">
  <h1>Java Date Objects</h1> 
</div>

Why is it that Java has been around for so long, but using date objects is still so difficult? Surely improvements have been made to make our lives easier when working with this object, right? Perhaps the Calendar object will help! Not. 

```java
Calendar cal = Calendar.getInstance();
System.out.println(cal.getTime()); //Thu Jul 11 21:26:47 EDT 2019
```

Great, now I have an object that represents right now. Let's say I want to add a few days to this object. Should I use:
```java
cal.add(Calendar.DATE, 3);
```

Or..
```java
cal.add(Calendar.DAY_OF_MONTH, 3);
```

Both calendar fields produce the __same__ result - *Sun Jul 14 21:26:47 EDT 2019*. So why do both exist? Can we be sure that `Calendar.DAY_OF_MONTH` will roll over to the next month or would it just stop incrementing the day when it hit the end of the month set on the object? Apparently, they both work the same - so one should be deprecated!

> Why so serious?
> -- Heath Ledger

I just feel that manipulating the date or time should be a lot quicker and abstracted from the developer. Thanks to __AlBlue__ on StackOverflow for describing the 5 main problems with dates in Java (Refer to [AlBlue's full response on SO](https://stackoverflow.com/questions/1969442/whats-wrong-with-java-date-time-api) explaining each of the points below in more detail):

```
Years are rated as two digits
Months are indexed with 0
They're mutable and can be changed if not properly protected
They don't work well with SQL
They are not representative of a timezone
```

*Fast forward to Java 8* - enter the new [Date/Time API](https://www.baeldung.com/java-8-date-time-intro). Although I have not been able to work with that API yet, this still seems like too much effort.  

> So long... partner.
> -- Tom Hanks
