---
sidebar_position: 1
---

# 1 - Introduction

## Course overview

- Resource ref: https://github.com/pravn27/typescript-learning-journey/blob/master/courses/from-colt-steele/ref-pdf-notes/TypeScript%2BSlides.pdf

## Join the Community

> The course videos and exercises are only a part of the experience. In-person bootcamps foster a strong sense of community, and we've tried to replicate that here. To get the most out of the course, we highly recommend you participate in at least some of the following places:

- Use the course Q&A discussion boards here on Udemy. Zarko (our TA) and I frequently check for new questions. Participate both as an "asker" and "answerer".

- Join the Discord chat - it's a very active community with thousands of students.

  - https://www.coltsteele.com/discord

- Subscribe to the YouTube channel for additional content, live streams, AMAs with me, and more!

  - https://www.youtube.com/channel/UCrqAGUPPMOdo0jfQ6grikZw

## What is Typescript and its purpose ?

- **Typescript is Javascript with Types**

- TypeScript is a language that is **built on top of JavaScript with the purpose of helping us avoid the common pitfalls and bugs that arise in JavaScript**. And it seeks to improve the experience of writing JavaScript.

- **Typescript is superset of Javascript, Meaning that all JavaScript code is considered valid TypeScript**.The difference is that TypeScript adds on this type system. It adds in these special checks, these special enhancements to the JavaScript syntax, that make it a much better development experience. And hopefully help us avoid bugs.

## Typescript Overview

- **Static checking**

  - **Typescript detects errors in our code without running / executing it (before run time), this is called Static checking**

- Type checking

  - Typescript does this error checking on the basis of the **kinds of data** in our program AKA types, like code base which has somethings is an string, numbers, array or objects. It does all of these type checks before run time / executing

- Why Types and Typescript's type system ?

  - Helps us find errors!, before our code runs
  - Analyses our code as we type
  - only exists in development phase

- **Typescript is there for better development purpose then its compiled to Javascript**, what ever TS you written at the end it will compiled down to normal Javascript files

- Typescript playground

  - https://www.typescriptlang.org/play/

- **It's a superset of JavaScript, meaning that everything in JavaScript is valid in TypeScript plus a bunch of extra syntax that is TypeScript-specific that has to do with types.**

## Installation & Setup

- Typescript installation

  - https://www.typescriptlang.org/download/

- using npm, for under projects directory

  - `npm install typescript --save-dev`

- Globally Installing TypeScript in your machine

  - `npm install -g typescript`
  - check by running `tsc -v` in terminal

- Typescript playground in online, explore with Examples, TS Config & play it instantly

  - https://www.typescriptlang.org/play/

- How we use Typescript ?
  - lets create sample TS file `basics.ts`, add some TS code base.
  - How to run TS file ?
    - using tsc cmd `tsc basics.ts`, which compiled down TS file to respective JS file
