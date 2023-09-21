---
layout: essay
type: essay
title: "Who is This Lint Guy Bossing Me Around Anyway?"
# All dates must be YYYY-MM-DD format!
date: 2023-09-20
published: true
labels:
  - Coding Standards
  - ICS 314
---

## I Need Space...
<p>
When I first started coding, I could not help but be fascinated by how the stuff I typed was laid out on the computer screen. I remember immediately exploring different theme extensions for Atom (a text editor) to customize how my code looks on the screen. Apart from that, I was also very meticulous about the spacing between each line at the time and preferred having tons of whitespace between each line that does different things; that way, I could read my code better. I carried this habit over when I took ICS 111 (Intro to Computer Science I) class, as seen in my <a href="https://github.com/aaron-ancheta/ics111-hw2/blob/main/Assignment02.java" target="_blank">homework 2 code</a>. I was not introduced to specific rules about spacing, so I did not care how much space I put in between each line of my code as long as I could read it easily.
</p>

## What's This @param Thing Doing Here?
<p>
<img width="200px" class="rounded float-end pe-4" src="img/essay-photos/param.png">
As a person who quickly forgets things, I typically jot down as many details as possible and make notes like "This Thing A performs Action B." This helped me a lot to get through my Biology classes in senior high school. As we got deeper into ICS 111, we were introduced to commenting, a principle in programming that aims to describe individual parts of a code (methods or functions, classes, etc.) to make it easier for others to understand what that particular block of code or function does. As someone who likes to be detailed when noting things, I studied how to properly make comments in Java and applied it to my homework projects despite it not being a requirement. Of course, I would still often make comments that do not adhere to the "standards," but I at least ensure that it would serve as a helpful guide when reading my code. 
</p>

## According to Lint, You Should...
<p>
Upon taking the ICS 314 (Software Engineering I) class, I encountered a new programming concept extending the commenting practice I mentioned above, described as "Coding Standards." Beforehand, I did not even know that people make software analysis tools dedicated to identifying programmatic or syntactic inconsistencies in a source code, which they like to call Lint or Linter. Linters like <a href="https://eslint.org/" target="_blank">ESLint</a> (what we use in class) not only flag programming errors but also give prompts when they find stylistic inconsistency in your code, like adding unnecessary indentation or lacking one, having no space before or after a curly brace, and, of course, missing a semicolon, to name a few. These linter programs are designed to help implement coding standards, which turns out to be just as important as making sure your code works. Why did they establish coding standards anyway? Apparently, following coding standards is vital in software development because it assures uniformity, promotes collaboration, and improves code quality, resulting in more maintainable and stable software programs. Just like in citation formats (APA, MLA, etc.), where established rules help identify a citation technique and differentiate it from others, linters automatically implement that "rule" in your code to ensure your code sticks with what is standard.
</p>

## Assistance or Distraction?
<p>
Considering all that, Linters does not seem so bad, right? With my limited usage time at the time of writing, ESLint and I have established a love-and-hate relationship. I love that it always keeps me in check while coding to ensure my way of writing code does not stray from the coding standards. However, sometimes, having someone tell you you are doing something wrong while, at the same time, knowing you are not done yet is definitely irritating. Whenever I write a function, it makes these squiggly lines under the function name, indicating that I have not put the function in use. It often serves as a reminder, but sometimes, seeing those red lines in my code gets distracting. Nonetheless, I am okay with using Linters in general, as it made me aware of when I actually need a space...
</p>