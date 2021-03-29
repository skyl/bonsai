---
layout: page
title: Incremental Change
nav_order: 8.5
---

# Incremental Change

Try to make an improvement to your production software at least every few
days. Some larger efforts may take a week or two. But, you should be able to
make the change or you should have more information to either abandon the
effort, change directions or otherwise arrive at the next state.

The ideal task size is "a couple of days". Try to break down things into
smaller deliverables that can be delivered in "a couple of days". Sometimes
these things may only take 30 minutes, sometimes over a week.

## Prefer a Working Proof of Concept Rather than a Spec

Start ["Getting Real"](https://basecamp.com/books/getting-real) as soon
as possible. See if you can produce a working prototype and discover
the next steps. Iterative improvement and incremental change are about
adapting to new information with _agility_. If you control the whole product
from planning to specifications, requirements, design and so forth, you can
decide to not _overproduce_ planning in the initial phases and instead
deliver updates to the plan _continuously_, _just-in-time_,
as more information _emerges_.
However, if you don't control the whole lifecycle of your software project
and are handed a rigid,exacting specification and a budget, Bonsai principles
can still help improve productivity.
In [waterfall](https://en.wikipedia.org/wiki/Waterfall_model),
the main difference is that, instead of a "voice of the customer"
that continually provides feedback as the software progresses,
the only feedback is the difference between the software and the initial spec.
You can still break down the steps into small increments and order them
by dependencies and priorities. You can incrementally discover the
implementation details and even continuously reorder the backlog
based on what you think you most need to know in the initial phases
to make better implementation decisions as the project progresses.

## Stay Close to the Trunk Version

An engineer should be able to sketch a working prototype and try it without
friction and without affecting the production.
One should be able to easily compare
the prototype version with the current production version.
Your development version should be constantly integrated
with the trunk version as the developer works. In this way merge conflicts
are avoided. Reconciling a long-running or stale branch can be painful
and should be avoided.
