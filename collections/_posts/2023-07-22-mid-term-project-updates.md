---
layout: post
title: "Unpacking My Experiences with an Open Source Project"
date: 2023-07-22T11:26:40+6:00
authors: ["Sulagna Saha"]
categories: ["Open Source"]
tags: ["Writing"]
description: Lessons I am carrying with me from my project
---

**Writing almost 2000 Lines of Code**

I never had thought of estimating how many lines of code I have contributed until I was asked in an interview. This project provided me with the opportunity to have an experience to mention in an interview that "Yeah, see, I have coded a lot!"

Jokes apart, this was a new experience for me and taught me two important lessons:

- _Sticking to a routine_: Writing code every day and keeping the patience to slowly improve it is important for such tasks.
- _Keeping things organized_: By arranging files neatly, the code becomes easier for others to understand, which can help with teamwork.

**Learning About Test Driven Development (TDD)**

Before this summer, I only knew a little about JUnit test cases from my classes. But after using RSpec Testcases for Ruby, I now understand how valuable they are.

These test cases are essential when working on a live project. They make sure that changing the code won't break anything that's already working. Plus, I learned about Continuous Integration (CI) on GitHub. The green tick, yellow dot, and red cross are more than just symbols; they tell you the status of your CI. By using test cases, I set up a system that checks the code whenever I make changes. This is a great tool for managing code in real time.

**Handling Large Batches of Operations**

At first, I just wanted my code to run smoothly and do things in order. I didn't think much about optimizing for large numbers of operations.

But, learning about optimization showed me how real apps work and why I shouldn't send too many API requests at once. I had to learn more about the MediaWiki API, choose the best API urls for my project, and arrange my code in the right way.

**Improving My GitHub Skills**

Have you ever forgotten to pull and fetch from the correct branches before making a commit, only to end up with divergent branches? Or accidentally made your password public in your codebase? While handling these, I got to use:

- **git stash**: Temporarily saves changes that you don't want to commit yet.
- **git rebase**: Integrates changes from one branch into another, keeping a clean project history.
- **git cherry-pick**: Applies changes from specific commits onto the current working branch.

**Going Through Code Reviews**

I still need more experience with this, but here's what I've learned so far:

- Writing clear commit messages
- Documenting the code well
- Keeping the PR description clear
- Following the coding habits of the existing codebase

These skills help communicate more quickly and cut down on work in the long run.

**Publishing a Gem Library**

I've used gems in my projects before, but creating a gem myself was new to me. I learned a few things in the process:

- Understand the rules of the platform where you're publishing (for me, rubygems.org)
- Think about the users and how to make things easy for them
- Write helpful documentation with examples and guidelines
- Test it as a user would before publishing (and remove unnecessary debug messages)
- Learn about versioning of gems and how to maintain that

**Refactoring and Organizing Code**

Good names for files, classes, variables, and functions make debugging easier. Refactoring codes to make them short, efficient, and helpful to understand had been a challenge for me - sometimes required more time, research, and clarity than finishing the task itself.

Planning and designing become extremely important as well while I tried to organize code. Keeping the end goal in mind, I asked questions repeatedly that what the edge cases my code needs to handle. Running through a lot of real-life examples help me discover lots of new bugs I did not have any idea about.

**Learning to Delete Code I Spent Hours Writing for a Better Idea**

Sometimes I had to delete code I spent a lot of time on because I found a better way to do things. This was hard to do but that’s the way to improve.

**Adding to a 10-Year-Old Codebase (WikiEducation Dashboard)**

The main part of my project was not working on an existing codebase - instead of building it from scratch. But now I am focusing on the integration of my gem to WikiEducation Dashboard where I am learning more to understand code and add onto it than writing all by myself. This is a different skill I look forward to learning.
