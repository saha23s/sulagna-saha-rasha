---
layout: post
title: "Behind the Code: Developing a Gem Library for Wikidata Analysis"
date: 2023-06-26T8:26:40+6:00
authors: ["Sulagna Saha"]
categories: ["Open Source"]
tags: ["Writing"]
description: What I have learnt last month
---

### **What my project is about**

Before jumping into the point of struggle in development, I want to give a short introduction to the project I am working on. I am working on creating a Ruby Gem Library from scratch for analyzing Wikidata edits. **Wikidata** acts as central storage for the structured data of its Wikimedia sister projects including Wikipedia, Wikivoyage, Wiktionary, Wikisource, and others.

When I first read my project goal, I never knew about gem libraries in detail and how to create one. In short, if you have a project working with Wikidata, you can install the gem I am creating with `gem install` command. Basically, you will give an array of revision ids to analyze and the functions in Gem are responsible to provide you with correct statistics of every revision compared to its parent revision. When a Wikidata item is edited, you can add, remove or change a lot of things. My job is comparing the JSON representations of the edits and writing code to detect the differences, count the total number of changes, and return the statistics to you.

### **What I am excited for**

I look forward to integrating the gem I am creating into Wikieducation Dashboard, if integrated, my code will run against lots of courses to generate reliable statistics eventually helping thousands of students and teachers to use the correct stats.

On the other hand, millions of users who use Wikidata on a daily basis either through wiki projects or contributing to edits will have the opportunity to use my gem for analyzing them.

That’s very exciting for me. The code written and contributed by me having an impact, however big or small that is, is something I look forward to. Specifically, Wikidata items are an open education to the world - so it’s really exciting to work in my team contributing to something big scale.

### **Lessons Learnt in past weeks**

**Asking Questions, Effective Questions**

I love asking questions. The struggle is asking effective questions. When I look back to my previous meetings and the questions asked, sometimes I mix up two questions or keep asking for a long time. I am so grateful for Sage to listen to me and still answer all my questions.

I understand that our discussions could be more succinct and comprehensible if my questions were better structured. Though I usually prepare my questions ahead of time, I often find new ideas cropping up as I start talking. Going forward, I aim to stay focused on one topic before transitioning to the next.

**Debugging is hard**

In this project, I am the only person who is responsible for creating the whole codebase. So, when I started coding, I was not too serious about optimal coding habits and organization. Ahh.. a mistake. I had to deal with a lot of examples of Wikidata edits that had HTML and JSON representations links. While testing different examples, I was not keeping track of which revision (such as printing it out) in the console. When I faced an error, I was lost. I have this bad habit of skipping commenting while I am coding through. After 2 or 3 hours of work, I felt so lazy to go back and comment all the stuff back in. So, commenting, print statements, and logical questions are helping me debug better. I am yet to learn more about it.

**Being stuck in a loop of searching and making it WORK**

Okay, this is annoying. When grappling with a new concept, my goal is to understand all facets of it. However, when a bug surfaces, I tend to get caught up in the cycle of search-and-fix, sometimes losing sight of the learning process.

I've noticed that I tend to prioritize "making the code work" so much that I lose track of the different solutions I've tried. This approach can hinder my learning, particularly when I have to continue working on the same bug after a break.

To combat this, I've begun to keep a log of my actions, which has proven to be challenging but helpful in the long run. By putting more effort into understanding the existing codebase, I find it easier to write new code on top of it.

**The Power of Retrospectives - Fridays**

In the initial weeks, I struggled to clarify my daily and weekly tasks. This lack of clarity led to procrastination and demotivation. While the project has a clear ultimate goal, breaking it down into actionable daily steps was necessary, considering the flexibility of my focus.

I realized that it's not just about working on a project; periodic retrospection and planning are equally essential. Now, every Friday, I reflect on my progress during the week and plan for the following week. I use Fridays to write or read blogs and make decisions. Setting aside a day for these activities has noticeably boosted my productivity. Besides, reading the proposal and thinking about big picture also makes me appreciate my efforts.

In sum, while there's still much to learn and many ways to refine my learning process, writing about these points has given me a greater understanding of my missteps and has motivated me to keep moving forward.
