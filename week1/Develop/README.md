
## <h1>Week 1 - Horiseon Website Refactoring</h1>

<p>This project required us to refactor the existing code for the Horiseon website homepage. the goal here was to make the code more accessible, comprehensible, efficient and practical. Also these changes should make this page more accessable for search engines. </p>

---
## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title


```

## Code Changes
* Title changed from website to Horiseon Marketing.
* changed all divs to sections and navs
* Changed the header div to header element 
* Added alt texts to all img lines for users using the windows narrator or similiar programs to read text aloud, or on browsers that may not be supported
* Added HTML descriptions for the code on both HTML + CSS pages
* Consolidated CSS .benefit-lead + benefit-brand + .benefit-cost into one command line to benefit-sidebar
* Consolidated benefits H3 elements on CSS by adding same class to all 3
* Consolidated benefit images on CSS by adding same class to all 3
* Added class to p element on html and targetted that class instead
* Formatted HTML code better, added spacing between lines
* Fixed errors using WAVE evaluation tool
* Consolidated div h2 subheadings in CSS
* Removed footer div and changed to proper footer element
* Fixed search engine optimization link to focus on content below

---

## Technologies used
-HTML
-CSS
-WAVE evaluation tool

* [Link to deployed Website]
* [Link to github Repositiry]



