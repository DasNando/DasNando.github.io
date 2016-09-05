---
layout: post
title: Week Two!
---

<b>Here</b> we, <b>go</b> again.
<br>

<b>What did you do this week?:</b>
<br>Hupupupup. This week in class we went over some useful details about the increment operator (something that's easy to take for granted) and some more Collatz optimizations and we even got a fun little checklist for the project. Good times. As for what I did, I actually spent quite some time nerding out over the possible patterns in a collatz function with a hard limit. I had a fun time writing down all the ways that 333,333 is the highest possible odd number we'd be asked by UVA to deal with in any sequence and sketching some fun visuals explaining why, for odd numbers between 333,333 and 250,000, all secondary roots are unattainable in our given range.
<br> It's probably important (but probably not) to note that this was in almost no way useful. Knowing that 5/6 of all evens from 1,000,000 to 500,000 will <b>always</b> show up strictly as the first number in a given input sequence didn't help my runtime but it sure was incredibly fun to think about. In the end, I did get a fast working solution submitted to UVA, and now all I have to do is write my tests and clean up my Travis and Make files and I should be good to go.<br>

<b>What's in your way?</b>
<br>Travis is yet again a stumbling block. I'll need to go to lab this week to talk to a TA about whether or not what I'm doing with it is correct. My tests aren't failing, they're stopping the entire test on Travis.com. In fact, even the given tests exhibit this behavior. The tests run fine with the wrong answers (1) but implode when testing for any other answer. I'll look into it and hopefully get it sorted before bringing it to the TAs.<br>

<b>What will you do next week?</b>
<br>Next week, I'll be finishing up this project. Before we get assigned our next project, I'd like to get this Travis thing sorted out so I can be a little bit more sure of myself in the next project. I feel like I'm doing fine, however, so I'm not stressing just yet.<br>
<br>
Unfortunately, it's been an academics-filled week and I haven't really been actively looking for fun, useful tools to give. Instead I'll just kind of point out an oldy but goody. If you've never used PuTTY, it's a lightweight SSH client. I use Windows 90% of the time and PuTTY is a clean way of connecting to the lab machines via SSH. Thanks to Docker, it isn't particularly necessary in this class, but it's useful nonetheless and I'd think about installing it.
<br>Ah well. Not a very insightful blog post tonight, but maybe next time.
<br>Until then, dear reader.
