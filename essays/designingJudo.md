---
layout: essay
type: essay
title: Designing Judo
# All dates must be YYYY-MM-DD format!
date: 2022-04-28
labels:
  - Design Patterns
  - Learning
  - Judo
---

# Designing Judo
In the creation of judo, there were many things that Dr. Jigoro Kano considered. From the purpose to the application of it as a martial art and as a sport. His primary goal was to ensure the legacy of Jiu Jitsu was continued in a world increasingly hostile to martial arts. Thus, he created Judo; a gentler and more sporting version of Jiu Jitsu that focused primarily on throws. It is in the design of these throws that I found similarities to programming.

## The Design of Judo
Imagine an opponent walking or running towards you, what should you do in this situation? This is a common, and altogether standard situation in judo, thus a design pattern emerged. That being the "seoi" line of throws, the first being dubbed "Ipponseoinage". Seen in many a hollywood blockbuster, the standard shoulder throw is a template for many others. "Moroteseoinage", "Seoitoshi", and more. 

![enter image description here](http://cmac-judo.com/_Media/ippon-seoi-nage_med_hr.jpeg)

Or, if you are the aggressor and are running towards an opponent, what then? Here there are a number of options; but the idea is to get the opponents weight onto one leg then take that leg out from under them, thus forcing them to the ground. The most basic version is "Osotogari". 

This is allegorical of design patterns in programming. Dr. Kano observed common scenario in sparring and combat, he then created templates that can be the basis of the way we deal with them. To surmise, a design pattern in programming is the recognition of a commonly occurring situation as well as a template to remedy said situation.

## Template Usage
Just as in Judo, where one will usually focus on learning and mastering a single or a few specific techniques. One being your favorite, and the rest being supplementary for the flaws in the main technique. So too is my philosophy in programming. 

### What I Use (I don't know any names so I'll just describe the designs)
I started out programming with the desire to make games. To do this, I chose the Unity game engine, which uses C# as its main language. Thus, my style of programming starts and grows from there. When designing a game, there are a number of checks that must occur every frame to maintain the semblence of an every evolving game world. Thus, a favorite tactic of mine was to use a switch statement as an event listener and handler. If an enemy takes damage, they broadcast that event to the listener which then tells all the other systems in place how to respond. 
Naturally I used a Factory type of design for the creation and instantiation of objects.
I recently implemented the Singleton design pattern into my programs after being taught it in ICS 369; prior to it, I went through a convoluted and tedious accessing of each file, so the Singleton was game-changing for me.. pun intended.
I most likely use a number of other design patterns, but these are the ones that stand out as my favorite, and most basic ones respectively. 
##  Sono Mama
As we can see, design patterns (at least the design pattern of design patterns) are applicable outside of programming. They help to focus ones thought process and solve problems. Be it my favorite switch statement, or my favorite "Moroteseoinage", my style revolves around a central idea, then builds out to shore up any holes in it.  