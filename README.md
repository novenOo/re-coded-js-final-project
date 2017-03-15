# Re:Coded Final Project

For your final project, you will be creating a personal website that showcases everything you have learned in the HTML, CSS, and JavaScript sections of the course.

At a minimum, the site must have the following pages:
 - **Homepage**
   + Should load well-styled content even if the browser has JavaScript disabled.
   + Should have links to all other pages.
 - **About**
   + Who are you?
     * One paragraph about your life before Re:Coded.
     * One paragraph about why you joined Re:Coded.
     * One paragraph about what you want to do after Re:Coded.
       - What your dreams are, both immediately and long-term.
 - **Projects**
   + A page with two navigational buttons or tabs, `Current` and `Favorite`:
     * Clicking the `Current` button will make an AJAX request to the GitHub API and display information about your 5 most recent GitHub repositories.
     * Clicking the `Favorite` button will make an AJAX request to grab the current Pinned Repositories from your GitHub profile.
       - Note that this information is *not* accessible via the GitHub API. We will be loading our GitHub profile page via AJAX and grabbing the information straight off of it — we're web scraping again! Remember, you can load a full HTML page via an AJAX GET request. There's even a special jQuery method for only loading a *section* of a page. That would be perfect!
 - **Skills**
   + A page showcasing the skills that you have learned in Re:Coded (for example, CSS, HTML, JavaScript, jQuery, AJAX, Ruby, web scraping (with Nokogiri and now with JavaScript), Pry (for Ruby development), RSpec (for Ruby testing), Git (with remotes stored on GitHub), etc.
     * The skills should be stored in a JSON file that gets loaded via an AJAX request.
 - **Your choice!**
   + You must create at least one additional page that displays data retrieved via an AJAX call to an API *other than GitHub*. For example:
     * Create a [GoodReads](https://www.goodreads.com/) account with your favorite books and load that data via AJAX requests to the [GoodReads API](https://www.goodreads.com/api).
       - Create a YouTube playlist of your favorite coding videos and load the playlist via AJAX requests to the [YouTube API](https://developers.google.com/youtube/).
       - Create a `Tech News` page and load the latest stories from the [Hacker News API](https://github.com/HackerNews/API).
       - Be creative! We would love to see what you can dream up!

## Notes
 - The project should have a clear Git commit history with many (ideally 50+) small commits and **NO** large, unwieldy commits. Your commit history should read like a bunch of short actions that, together, create a narrative of how your project came into existence.
 - As much as possible, your code should be organized into small, logically coherent pieces that all fit together within the overall structure.
   + Every function you write should have **one** job.
   + If you have a function that's doing more than one thing — for example, making an AJAX request **and** displaying the returned data on the page — split it up! Have one function make the AJAX request and a separate function display the returned data.

## Links
 - Twitter Bootstrap (for basic site styling and layout).
   + [How to include Bootstrap in your project](http://getbootstrap.com/getting-started/).
   + [How to take advantage of Bootstrap's grid system to for organizing your pages](http://getbootstrap.com/css/#grid).
   + [Download and play around with Bootstrap's examples](http://getbootstrap.com/getting-started/#examples) or start with [a blank, basic template](http://getbootstrap.com/getting-started/#template).
 - [GitHub API documentation](https://developer.github.com/v3/).
 - [Code organization guide from jQuery](https://learn.jquery.com/code-organization/).
