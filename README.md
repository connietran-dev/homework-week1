# homework-week1: 01 HTML CSS Git: Code Refactor

**The live page can be viewed here:** https://connietran-dev.github.io/homework-week1/


We were tasked with optimizing an existing site for search engine optimization and ADA accessibility while maintaining the same look-and-feel of the UI. 

Here are some **highlights** of changes I made:

* Changed `<div>` elements to semantic HTML elements, such as `<header>`, `<nav>`, `<main>`, `<footer>`.
* In addition to above, removed classes from HTML elements to optimize and simplify the CSS selectors. The previous CSS selectors were redundant and repetitive, making potential future changes tedious.
* Added metadata such as `<meta name>` for SEO.
* Added `alt` to images `<img>` for accessibility.
* Modified the color contrast of the `<aside>` for accessibility.
* Re-ordered CSS selectors to mimic the order of the elements in the HTML document.


Below are the instructions we had from a homework activity from week 1. 

I've added notes on how I've addressed each of the acceptance criteria.


# Class Instructions for - 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria


* GIVEN a webpage meets accessibility standards
* WHEN I view the source code
* THEN I find semantic HTML elements **(*added header, nav, main, footer HTML elements*)**
* WHEN I view the structure of the HTML elements
* THEN I find that the elements follow a logical structure independent of styling and positioning **(*kept h1, h2, h3 headings. modified HTML elements to be semantic. modified HTML elements to optimize for CSS selectors. changed order of CSS selectors to be in same order as elements in HTML*)**
* WHEN I view the image elements
* THEN I find accessible alt attributes **(*added*)**
* WHEN I view the heading attributes
* THEN they fall in sequential order **(*headings are in sequential order*)**
* WHEN I view the title element
* THEN I find a concise, descriptive title **(*added*)**

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
