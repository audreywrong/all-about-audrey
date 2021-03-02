---
title: Introduction to Node + Mocha + TypeScript
date: 2021-03-21 20:21:00 +0300
description: # Add post description (optional)
img: ../../assets/node.png
tags: [node, mocha, typescript, coding, learn to code] # add tag
---

### Node JS + Mocha + TypeScript Intro

Recently I have been wanting to dip my toe into back-end topics and more in depth debugging and error prevention. This article will cover my introduction to Node, the Mocha JavaScript library and TypeScript!
I wrote this article for an audience assumed to be familiar with the topics already. If you would like a more specific and basic breakdown of what each of these are, sent me a tweet or message me on LinkedIn, and I will do my best to write those specific articles.

### Node JS

Node JS is something I have been aware of since I started learning how to code but did not quite understand what is was or used for. Breaking it down into layman's terms helped to keep the topic simple and able to be built upon as I continue to learn more.

"NODE JS: CROSS-PLATFORM FOR SERVER-SIDE PROGRAMMING THAT ALLOWS USERS TO BUILD SCALABLE NETWORK APPLICATIONS QUICKLY"

I wrote a simple "Hello World!" program that logged the aforementioned phrase to the command line as my first go at writing a node program. It was easy, and it worked! Two things that do not often go together when learning a new programming topic. I also learned the importance of explicitly writing scripts in order to remove guesswork or human error when compiling and testing code.

### Mocha

The next step was to install Mocha and learn how to write some simple tests. I ran an example test to play around with the syntax, make some changes of my own, and get a feel for how it worked. Additionally, I learned how to write node scripts with mocha commands. Great -- we are getting somewhere!

### TypeScript

The final piece of this learning puzzle was to implement TypeScript into a simple project to see how Node, Mocha and TypeScript came together to prevent bugs in a project in a simple, clean way.
I wrote a TypeScript program that made a math equation factory for addition and subtraction. This program took in an equation type and two numbers and returned a value based upon whether the numbers were added or subtracted. Super simple and easy to test!

In this sample program I was able to see how TypeScript was able to check not only primitive types with my number argument, but user-defined types as well with my "equationType" (add or subtract) argument.

With all of these pieces in place and everything looking good (after some compiling troubleshooting, of course) I was able to run my first meta expectation (???) on a sample program of my own!

### Takeaways

What was cool about starting my learning journey on these topics? 1. Errors are COOL and HELPFUL! Errors are your friend. You would not want your code to be full of bugs and not tell you, right? How else would you know what to fix? You would be staring at a screen not knowing where to start even if the errors being thrown are not the exact root of the issue all of the time. 2. More practice in debugging! This goes hand-in-hand with point one, but I am of the mindset that "more is more" with debugging and error handling. In a professional setting with projects being shipped and often a lot on the line, it is crucial to have not only great googling skills, but confidence in debugging. You can only obtain this from practice and not being afraid of red, squiggles, or messages "yelling" at you. 3. It was WAY EASIER THAN I EXPECTED. I have a tendency to get in my head about new topics. Learning to code has been instrumental of my learning how to get over this and being excited to crack a new topic. Learning Node, using Mocha and implementing TypeScript was no different. It was fun, straight forward and pretty easy. I am excited to write tests for larger projects and see this all in action even more!

### What's Next?

I could write a book to answer this question, but I'll do my best to keep it simple!
First I would like to implement TSLint into this example project in order to play around with how it works and add further error handling to a program.
I would like to write tests in Jest with my React-built projects to have practice with some more complex applications than my simple equation builder.
Finally more complicated Node projects and introducing Express servers has to make the cut.

I am motivated and excited to learn more about these above topics and see how they're used in practice!
What are you excited to learn next? What are you currently working on? I want to hear from you! Please feel free to share any resources you are finding valuable and helpful.
