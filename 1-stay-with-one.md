---
layout: page
title: Stay with One
nav_order: 2
---

# Stay with One

Now that you've decided that some software absolutely must be built,
let's continue to keep it as minimal as possible. Zero is the best number.
The next best number is one. Don't have multiple ways to do things.
Don't maintain multiple copies of the same code. Don't have two databases.
Don't create multiple silos. Don't have different workflows for developers.

## One Source of Truth

What defines the software that your developers are working on?
What is the canonical data that supports your applications in production?
Reduce the cognitive overhead of constructing the system.
The entire state of your system should be able to be constructed with a
version identifier and a few variables. There is one version of the code
and there is one version of the data.
