# homework-1

For this homework assignment, I took the provided html in the class GitLab repository and refactored it to meet a list of Acceptance Criteria based on a User Story, both of which were provided in the assignement's Readme file, and copied again here: 

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
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Summary

In addition to following the requirements outlined here, I added comments throughout the index.html and style.css files to make it easier for future developers to edit the code (long term sustainability).

I used w3schools.com to help decide which semantic HTML elements to use. The specific page can be found here:  https://www.w3schools.com/html/html5_semantic_elements.asp

I made some changes to the use of id and class - since it seemed the original author wanted to use a unique identifier for each point on the page, I turned them all into ids. In some places both a class and id were indicated so it seemed like someone needed to make a decision on that.

I added alt attributes to all the images which were provided in the HTML. As the hero image was linked through the CSS page, I chose to edit the Title attribute of the hero section, following a suggestion from a user on stackoverflow: https://stackoverflow.com/questions/4216035/css-background-image-alt-attribute

I also updated the footer's header tag to follow the proceeding tags sequentially. I'm not entirely sure if that was necessary but the instructions made it seem like I had to change *something* so I chose to do that.

The HTML elements seemed to follow a logical structure so I left them alone - I did move around the CSS "chunks" (for lack of a better word - couldn't find how to explain this concept) in order to follow the flow of the HTML, which I believe makes it easier to go back and edit if necessary.
