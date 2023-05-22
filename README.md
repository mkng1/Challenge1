# Code Refactoring for Accessibility

## User Story

We are a Marketing Agency and we need to refactor our codebase to follow the established Accessibility Standards while retaining the original design.
This will also have the benefit of Search Engine Optimisation.

## Acceptance Criteria

There are multiple Acceptance Criteria for this challenge.
Original starter files accessed from GitLab
https://git.bootcampcontent.com/University-of-Sydney/USYD-VIRT-FSF-PT-05-2023-U-LOLC/-/tree/main/01-HTML-Git-CSS/02-Challenge

### Semantic HTML Elements
The Website should use Semantic HTML Elements instead of non-specific elements such as -div- or -span-.

applied

- header
- mark
- nav
- figure
- main
- article
- aside
- section
- footer

elements and replaced div or span where necessary

### Logical Structure
Elements on the webpage should follow a logical structure independent of styling and positioning

While working on Semantic HTML, the code was restructured logically.

Applied a little bit of tab space styling

### Accessible Alt Attributes
Alt Attributes should be added to relevant elements for accessibility

All image elements in the document are generic marketing images without the need for description.

Therefore null alt attributes have been added where necessary

### Sequential heading attributes
Heading attributes fall in sequential order

There is only one H1 inside the Header element.

There are four H2 elements. I have converted one into H3 element in the footer.

There are three H3 elements. After the above adjustment, there are four.

They are in sequential order as far as I can tell.

### Title Update
I need to have a concise descriptive title for the page.

I have updated the name of the title from "website" to "Horiseon Social Solution Services Official Website"

## Technical Acceptance Criteria
### Application's Links all function correctly
There is one link that is not functioning properly.

I have added the id to the article element to fix the broken link

### Application's CSS selectors and properties are consolidated and organised to follow semantic structure
Elements and classes and ids should be consolidated and organised to follow semantic structure.

consolidated and organised the classes and elements in the HTML as well as CSS

### Application's CSS file is properly commented
CSS needs to be properly commented

All the changes have been documented through /* */ comment

## Deployment Acceptance Criteria
### Application deployed at live URL
Application was deployed at 

https://mkng1.github.io/challenge1-horiseon-portfolio/

### Application loads with no errors

Attached file "Screenshot-1.png" to show there are no errors at the time of upload.
There is an error message with the lack of favicon through GitHub Pages but I believe it is outside the scope of this challenge.
https://mkng1.github.io/challenge1-horiseon-portfolio/screenshot-1.png

### Application GitHub URL Submitted
https://github.com/mkng1/challenge1-horiseon-portfolio/

### GitHub repository that contains application code
Same as above

## Application Quality Acceptance Criteria
### Application resembles (>=90%) screenshots provided in the Challenge instructions
Current version looks identical to original on Chrome latest version on macOS

## Repository Quality Acceptance Criteria
### Repository has a Unique Name
Repository name has been changed from Challenge1 to Challenge1-Horiseon-Portfolio, and then to challenge1-horiseon-portfolio

### Repository follows best practices for file structure and naming conventions
Used dash - delimiters instead of space for the files
Avoided special characters
Avoided capital letters

### Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
Followed all the best practices for class/id naming conventions, indentations, comments, etc.

### Repository contains multiple descriptive commit messages.
Made more than 10 commits with descriptions linking back to issues opened and closed for each requirement/task

### Repository contains a quality README file with description, screenshot, and link to deployed application.
All listed requirements has been listed in the repository issue #1 below
https://github.com/mkng1/challenge1-horiseon-portfolio/issues/1
Readme file includes all the issues that has been raised based on the requirements, and closed after each relevant commits.
