# Quiz 04: Project Design And Management

Choose *one* of the following scenarios and email Kevin a PDF your answer. The text should be double-spaced and in a 10-point serif font, no longer than 1 page. Your submission is due before the end of the scheduled finals period for this class. No late submissions will be accepted.

## Scenario A

The US federal government is redesigning the country's health care (and insurance) system substantially enough that they have hired you to direct the development of a new website that will replace healthcare.gov. However, they are worried that the project will run into similar problems that the previous website launch faced. Explain how you propose to develop the new website, including your plans for:

* What is your plan for deploying the new website for the general public?
* How will you track and report progress to ensure adherence to the deployment plan?
* If the progress falls behind early in the project, how will you respond?

## Scenario B

You have recently joined a team that has already begun a software project for a system that uses a proprietary Object-Oriented Programming language that is supposed to be the next evolutionary step in OOP. They have already implemented a standard library and included basic, generic data structures including: arrays, linked lists, stacks, queues, and binary trees. However, in building the compiler for the system, the team wants to implement a new data structure called *piles*. As they describe it to you, *piles* are last-in-first-out (LIFO) data structures but what makes them special is that you can place an entire pile (containing one or more elements) into an existing pile, while maintaining the order as they are added. For example, if pile **A** has: `<<1,2,3>>` (where `3` was the latest element added) and pile **B** has: `<<4,5,6>>` (where `6` was the latest element added), you can add **B** into **A** so that **A** would then have: `<<1,2,3,4,5,6>>`.

The team wants your advice on how to design the *pile* library. Do not provide any code (remember: this is in a *new* language), but describe using plain English (and language-agnostic software design/engineering terms) how to design the library. Provide a rationale *why* you chose this design.
