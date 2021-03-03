# Week 01 Project - HTML, CSS, and Git: Code Refactor

## Objective 

The objective of the the first week's assignment is to  **refactor** existing code  to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. 

## Quick Links

 * [Github code repository](https://github.com/macoovacany/Wk1-CSS_Refactoring)
 * [Published page - (relative link from markdown file)](./docs/index.html)

## Scenario

For this particular homework assignment, a marketing agency has hired you to refactor an existing site to make it more accessible. Web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

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

## Compliance Table

| **Requirement** | **Compliance Statement** |
| --- | ----|
| Structure of html semantic elements is logical | Using the layout of [W3 schools](https://www.w3schools.com/html/html5_semantic_elements.asp#:~:text=A%20semantic%20element%20clearly%20describes,%3E%20%2D%20Clearly%20defines%20its%20content) for header nave, article, section, aside and footer. <br> - divs  class header and footer changed to semantic element header  |
| All image elements have alt tags | all images, except for the background div class="hero" bakcground-image,  have alt tags. |
| headings are in sequential order | h1 heading reserved for entire document, <br> h2 headings used for content and benefits sections. |
| Title is a concise and desciptive | Title changed to "Horiseon Social Solution Services" |
| optimised CSS selectors |  consolidated common styling deinfitions as css list selectors. |
| all the applications links work correctly |  updated navigation link to work correctly |
| Application's CSS selectors and properties are consolidated and organized to follow semantic structure. | There are three ways the CSS selectors are consolidated<br> 1. items in the content section are decoupled by interoducing another class "content-items" <br> 2. used hte universal selector for sub items of benefits class <br> 3. used the css comma to apply style to multiple classes |
| Application's CSS file is properly commented. | CSS file is commented |
| Application deployed at live URL. | [Published page](https://macoovacany.github.io/Wk1-CSS_Refactoring) |
| Application loads with no errors. | TODO |
| Application GitHub URL submitted. | [Github code repository](https://github.com/macoovacany/Wk1-CSS_Refactoring) |
| GitHub repository contains application code. | TODO  |
| Application resembles mock-up provided in the homework instructions (at least 90%). | yes, note that the footer is cut-off in teh sample image in the assets folder.  |
| Repository has a unique name. | certainly unique. |
| Repository follows best practices for file structure and naming conventions. | TODO |
| Repository follows best practices for class/id naming conventions, indentation, quality comments, etc. | TODO |
| Repository contains multiple descriptive commit messages. | yes. |
| Repository contains quality README file with description, screenshot, and link to deployed application. | yes |
| The URL of the deployed application. | [Published page](https://macoovacany.github.io/Wk1-CSS_Refactoring) |
| The URL of the GitHub repository, with a unique name and a README that describes the project. | [Github code repository](https://github.com/macoovacany/Wk1-CSS_Refactoring) |

