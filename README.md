# MTM1544 Week 1 Starter: Mountain Trail Guide

The starting point for **Week 1 Assignment: Styling the Starter Page** in MTM1544 (Web Styles).

## What to do

1. Click **Use this template**, then **Create a new repository**. Give it a name you will
   recognise later and make it public.
2. In your new repository, go to **Settings**, then **Pages**, and set the source to the `main`
   branch. Creating the repository does not turn Pages on for you.
3. Clone it, open it in VS Code, and start writing CSS in `css/styles.css`.
4. Submit the live GitHub Pages URL in Brightspace.

## What is here

- `index.html`, the page you are styling. You are not expected to change it.
- `css/styles.css`, empty apart from a comment. Everything you are marked on goes in this file.

The page has four `h2` headings, one paragraph carrying `class="intro"`, and one heading carrying
`id="summit"`. Those are the hooks the assignment asks you to target.

## For instructors

This repository is a GitHub template, so each student ends up owning their own copy with a Pages
URL of their own. It pairs with `mtm1544/assignments/week-01-styling-the-starter-page.md` in the
assessments repository. If the course moves to a different account or organisation, move this
repository with it and update the link in that assignment and in immac's README.

## Copied from Brightspace
Deliverable
The starter page styled via a linked external stylesheet, using **element, class, and ID selectors, with one cascade conflict shown and confirmed.**

Released after: Week 1 quiz scored 9/10 or better.

Instructions
1. Start from the starter index.html and confirm the css/styles.css link works (change body's background-color and watch it update on save).
2. Style every paragraph and every h2 with element selectors (colour + line-height on paragraphs, a colour on headings).
3. Group two element types into one rule using a comma.
4. Style the .intro paragraph differently from the rest using a class selector.
5. Style the #summit heading using an ID selector.
6. Add a CSS comment above each rule explaining what it does.
7. Add a second rule targeting the same element type further down the file with a different colour, and confirm in dev tools that the later rule wins.
8. Push and confirm the live Pages URL shows the styling.

Technical Requirements
- css/styles.css exists and is linked from <head> with <link rel="stylesheet">
- At least one element selector rule with more than one declaration
- One rule using grouped selectors (comma-separated)
- .intro styled via a class selector
- #summit styled via an ID selector
- A comment above each rule
- A cascade conflict, shown and confirmed (two rules, same specificity, later one visibly wins)
- Zero CSS syntax errors (missing semicolons, unclosed braces)

AI Compatibility
No. This checks whether the student can write and reason about basic selectors and the cascade themselves. That's the whole point of Week 1.

Submission
GitHub Pages link to the styled page.