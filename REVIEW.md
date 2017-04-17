# Re:Coded Final Project Review Checklist

**Name of project developer**: 
Ali Dyiab
**Link to project's GitHub repository**: 
https://github.com/alidiyab/My-final-project.github.io
## Function
### AJAX Requests
- [x] All AJAX requests work properly.
- [ ] Large images, videos, and other media — anything that would significantly slow down the user's browsing experience — are loaded via AJAX requests.

### JavaScript Style
- [x] Each page has its own JavaScript file that contains JavaScript written specifically for that page.
- [x] All functions have exactly **ONE** responsibility. No functions do more than one thing, like make an AJAX request *and* add the returned data to the DOM.
  + **List any functions that have more than a single responsibility**: 

## Form
### Pages
#### Homepage
- [x] Project has a homepage.
- [x] Homepage loads well-styled content even when JavaScript is disabled.
- [x] Homepage contains links to all other pages.
- [x] Homepage makes the website's purpose clear (who owns the site / what we can expect to find within).

#### About
- [x] Project has an About page.
- [x] Contains one paragraph about the student's life before Re:Coded.
- [x] Contains one paragraph about why the student joined Re:Coded.
- [x] Contains one paragraph about what the student wants to do after Re:Coded, both short- and long-term.

#### Projects
- [x] Project has a Projects page.
- [x] Projects page contains two navigational buttons or tabs, `Current` and `Favorite`.
- [x] Clicking the `Current` button makes an AJAX request to the GitHub API and displays information about the student's 5 most recent GitHub repositories.
- [ ] Clicking the `Favorite` button makes an AJAX request and displays a list of GitHub repositories (that the student created or contributed to) that the student is especially proud of.
#### Skills
- [x] Project has a Skills page.
- [x] Skills page displays information about all of the student's programming skills.
- [x] Information about student's skills is stored in a JSON file in the project directory.
  + **Name of file**: 
- [x] Skills are added to the page by loading the JSON file via an AJAX request.

#### Student's Choice
- [x] Project contains at least one more page that displays data from an API *other than GitHub*.
  + **Which API**: 
- [x] Page loads data via an AJAX call to the appropriate API.

## Style
### Overall
- [x] Website looks professional.
  + **Why? Describe it**: 
- [x] Website does not feel cluttered.
- [x] Spacing between similar elements is consistent across all pages. (For example, the amount of space between the navbar and the page's content is identical on every page.)
- [x] Sizing of similar elements is consistent across all pages. (For example, the navbar links on each page are identical.)
- [x] All text is readable. For example, there isn't black text on top of a dark image or green text on a red background.
- [x] Website has a uniform color scheme. Aside from images, the same base colors are used on every page of the site.
- [x] Website has a uniform style / layout. It should feel like one cohesive site and not just a random collection of pages thrown together.

### Code
- [x] JavaScript functions and variables have descriptive names.
  + Good: `var favoriteProjects = ...`
  + Bad: `function a (b, c, d) { ... }`
- [x] JavaScript functions and variables that are composed of English words are spelled correctly.
  + Good: `function sendRequestToGitHub (address, data, token) { ... }`
  + Bad: `function sndreqestGithub (adres, data, tokin) { ... }`
- [x] HTML elements and attributes (for example, IDs and classes) have descriptive names.
  + Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
  + Bad: `<pj id="p1" class="ps fps">`
- [x] HTML elements and attributes that are composed of English words are spelled correctly.
  + Good: `<project id="favoriteProject1" class="projects favoriteProjects">`
  + Bad: `<projet id="favritProjet1" class="projets favritProjets">`
  
### Content
- [x] There are no spelling or grammar errors in the site's textual content (including headings, navigational links, and other small elements).

### Pages
#### Student's Choice
- [ ] Student used one of the examples given in the [final project guidelines](https://github.com/gj/re-coded-js-final-project/blob/master/README.md).
  + **List example**: 
- [x] Student came up with their own, creative idea.
  + **List idea**: 
  
## Linters
- [x] I ran the student's JavaScript code through [JSLint](http://jslint.com/) and told them about any JavaScript issues.
- [ ] I ran the student's HTML code through [the W3C's HTML validator](https://validator.w3.org/nu/) and told them about any HTML issues.
- [ ] I ran the student's CSS code through [CSS Lint](http://csslint.net/) and told them about any CSS issues.

**Name of reviewer**: 
ِNoven Temer