# Naming as a Process

Naming is hard. Often it gets treated as a chore among the fun parts of programming. [In his article Naming as a Process](https://www.digdeeproots.com/articles/naming-process/) Arlo Belshee shows that it is more than a chore, but an important responsibility for creating readable and maintainable software. It takes effort, and is effort well spent. 

## Overview

The article begins with an explanation of the value of readable code: maintainability, sharability, and resistance to bugs. It continues by laying out the following seven stages for the evolution of a name, spending considerable energy detailing refactorings that evolve code from one stage to the next.

1. Missing or Misleading
1. Nonsense
1. Honest
1. Completely Honest
1. Right Thing
1. Intentful
1. Domain Abstraction

At each stage of the process, we evolve our names as we discover more about what the code does. Often missing or misleading names are the reasons code is hard to understand. Scanning is difficult or impossible.

We're reminded of the classic computer programming comic:

![WTF/minute is the only true measurement of code quality.](/assets/wtfpmin.png)

## The Process

### Analyze and Name

Belshee suggests we temporarily wrap obtuse blobs of code with a nonsense name. He argues that this is an improvement because it calls attention to the code’s clear lack of purpose. It must be improved. 

The process starts by applying an analysis technique he calls *expanding the known* and *narrowing the unknown*. This means incrementally identifying the code’s responsibilities, encapsulating them in its name, and finishing with an honest and complete name. At this point, the process creates wordy names like `parseXmlAndStoreFlightToDatabaseAndLocalCacheAndAddToScreenIfVisible()`.  That makes it clear that:

* The code does too much.
* We can do better.

Why would anybody intentionally choose that name? We’re preparing the code for refactoring.

Remember Kent Beck’s classic advice:

	Make the change easy, then make the easy change.

Now, it’s easy to see everything the code does, and where refactoring must happen.

### Iterate and Reveal

The final stages of Naming as a Process hunt for the code’s true purpose. Belshee details an iterative process that drives the code’s names towards a high purposes; one that reveals “Why?” not “What?”. The ultimate goal are new abstractions in the domain of the constructed software. 

This process is:
1. Analyze context
1. Refactor
1. Rename

`preLoad();` becomes `parseXmlAndStoreFlightToDatabaseAndLocalCacheAndAddToScreenIfVisible();` and eventually `screen.add(flight);`

**Perhaps most critically, code in this state begins to carry its own energy; attracting purposeful behavior and repelling hacks.**

## The Takeaway

Depending on the level of the reader, there is lots to unpack in this process and its stages.

* **New developers** will find many new roads to explore. They should spend extra time in each stage unpacking its refactoring, and incremental improvement techniques.
* **Experienced developers** can follow the process step-by-step, reflecting on each state's finer points, to hone their iterative design skills.
* **Advanced developers** will find many see an explicit process mapping for what they’ve been doing subconsciously. They may use this mapping to tweak and adjust – and perhaps better explain, their on processes to others.

Ultimately, this article does well tackling a thorny problem of software development. Driven through naming it lays out in great detail a useful process of analysis, refactoring, and incremental design; three important software development skills worthy of investing time and energy to learn. It should be considered recommended reading for any software developer that desires to improve their craft.
