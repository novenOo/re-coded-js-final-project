# Re:Coded Final Project Review Checklist

## Function
### AJAX Requests
- [ ] All AJAX requests work properly.
- [ ] Large images, videos, and other media — anything that would significantly slow down the user's browsing experience — are loaded via AJAX requests.

### JavaScript Style
- [ ] Each page has its own JavaScript file that contains JavaScript written specifically for that page.
- [ ] All functions have exactly **ONE** responsibility. No functions do more than one thing, like make an AJAX request *and* add the returned data to the DOM.

## Form
### Pages
#### Homepage
- [ ] Project has a homepage.
- [ ] Homepage loads well-styled content even when JavaScript is disabled.
- [ ] Homepage contains links to all other pages.
- [ ] Homepage makes the website's purpose clear (who owns the site / what we can expect to find within).

#### About
- [ ] Project has an About page.
- [ ] Contains one paragraph about the student's life before Re:Coded.
- [ ] Contains one paragraph about why the student joined Re:Coded.
- [ ] Contains one paragraph about what the student wants to do after Re:Coded, both short- and long-term.

#### Projects
- [ ] Project has a Projects page.
- [ ] Projects page contains two navigational buttons or tabs, `Current` and `Favorite`.
- [ ] Clicking the `Current` button makes an AJAX request to the GitHub API and displays information about the student's 5 most recent GitHub repositories.
- [ ] Clicking the `Favorite` button makes an AJAX request and displays a list of GitHub repositories (that the student created or contributed to) that the student is especially proud of.

#### Skills
- [ ] Project has a Skills page.
- [ ] Skills page displays information about all of the student's programming skills.
- [ ] Information about student's skills is stored in a JSON file in the project directory.
- [ ] Skills are added to the page by loading the JSON file via an AJAX request.

#### Student's Choice
- [ ] Project contains at least one more page that displays data from an API *other than GitHub*.
- [ ] Page loads data via an AJAX call to the appropriate API.

## Style
### Overall
- [ ] Website looks professional.
- [ ] Website does not feel cluttered.
- [ ] Spacing between similar elements is consistent across all pages. (For example, the amount of space between the navbar and the page's content is identical on every page.)
- [ ] Sizing of similar elements is consistent across all pages. (For example, the navbar links on each page are identical.)
- [ ] All text is readable. For example, there isn't black text on top of a dark image or green text on a red background.
- [ ] Website has a uniform color scheme. Aside from images, the same base colors are used on every page of the site.
- [ ] Website has a uniform style / layout. It should feel like one cohesive site and not just a random collection of pages thrown together.

### Pages
#### Student's Choice
- [ ] Student used one of the examples given in the [final project guidelines](https://github.com/gj/re-coded-js-final-project/blob/master/README.md).
- [ ] Student came up with their own, creative idea.
