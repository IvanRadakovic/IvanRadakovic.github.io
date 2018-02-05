---
layout: post
title:  "Week Three"
date:   2018-02-04 18:00:00 -0600
categories: blog
---
![Ivan]({{"/assets/ivan.png" | absolute_url}}){:style="margin: 0 auto; display: block;"}


<h3>What did I do this past week?</h3>
In class, Downing started the week by talking about black box and white box testing. Another name for it is acceptance and unit testing respectively. We continued the lecture by talking about different types of caching such as lazy, eager, and meta caching. One of the most important things we learned that we should always catch exceptions by reference. We concluded the week by discussing c strings and seeing how they compare to char *.

<h3>What's in my way?</h3>
The biggest hurdle I had to overcome last week was a small bug that caused me to segfault when running the build on Travis. My code passed all the test cases on Hackerrank, but I had no idea why it was not working on Travis. I copied the code to ensure that it was identical to the one on Hackerrank, but it still kept segfaulting. There was no line number, no other error messages. Just segfault. I eventually went to office hours where Downing and I took steps to debug my program. We first tried to get the simplest case working, but we noticed that the program was overflowing the stack. I quickly realized that this was because I forgot to put the base case into my recursive function. I had the base case in the Hackerrank submission, but I forgot to copy it to my code.

<h3>What will I do next week?</h3>
I plan on reading the next couple chapters in the textbook, and getting an early start to the Voting project to give myself time in case I run into any really time-consuming bugs like I did with the last project. I also plan on working on the project with a partner because I found a lot of success in bouncing ideas off of other people in operating systems last semester.

<h3>What's my experience with the class?</h3>
This class is not as time-consuming as I first anticipated, but the projects still require quite a bit of work. However, the most challenging part of the previous project was getting the dev environment all set up. Now that I have experience with the workflow, the future projects should go by much smoother. That is if I can avoid dumb copy-paste errors.

<h3>What's my pick-of-the-week or tip-of-the-week?</h3>
If you ever need to work remotely off of the CS lab machines, but you want to use the programs on your personal computer to edit the files, there is a program called sshfs (SSH File Sharing). You can use it to mount a remote directory to your computer using ssh. The only downside is that you have to enter the full file path every time you used it. So to get around this I created a simple script that does this for me, and it even caches my previous mount.
