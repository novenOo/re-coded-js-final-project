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
     * Clicking the `Favorite` button will display a list of GitHub repositories (that you have created or contributed to) that you are especially proud of. There are a number of ways you can load this data via AJAX; for example, you could create a new file in your project directory that contains static links to the repositories, or you could add the GitHub projects to your LinkedIn profile and make an AJAX request to the LinkedIn API.
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
 - We want the focus to be on your own work. If you want to incorporate GIFs, videos, and artwork created by others, that's fine, but they shouldn't dominate your pages. Show off your skills! It doesn't take much effort to set the background image of a page to a GIF. It's a lot more impressive to create some well-styled CSS or interactive JavaScript elements on your own. Your website should be about YOU — you aren't creating an online gallery for someone else's work. :-)
 - Remember, readability is of utmost importance. If you have a black background, don't use dark gray text. If you have a GIF behind some text, make sure the text is still clearly visible. We've been preaching it all along, but, once again: keep things simple! Simple, clean, elegant, refined, understated, and so on. This project isn't testing your web design skills — it's testing your HTML, CSS, and JavaScript skills. That being said, we want a final product that looks polished and professional. Keep everything simple, and go for readability and functionality first and design second. Especially if that design involves tons of clashing colors, images, fonts, and so on. Look at Google.com, the most popular website in the entire world. It could not be simpler: 90% of the page is whitespace. Baidu, Twitter, Facebook, Wikipedia, Instagram, etc. all follow the same model. For less popular examples, I searched for "clean, professional websites", and this was the first [link](https://www.awwwards.com/websites/clean/). It contains tons of example sites, and it also has this little note at the top, entitled 'White space is key in clean websites':
   > Cleanness is essential for a good web design. People often mistake cleanness for minimalism. While both styles have common traits, do not be confused. They are not the same. Minimal design is more about using the bare essentials - less is more. Clean design focuses on the careful and precise positioning of the important elements throughout the site - a place for everything and everything in its place. The website can be considered quite busy with lots of elements to consider, but as long as the design is kept clean, the website will work. Clean website design conveys elegance.
 - If you use images, especially large ones, please load them via AJAX requests. Otherwise, users will be left waiting while their browser downloads everything, causing an unacceptable delay.

## Links
 - Twitter Bootstrap (for basic site styling and layout).
   + [How to include Bootstrap in your project](http://getbootstrap.com/getting-started/).
   + [How to take advantage of Bootstrap's grid system to for organizing your pages](http://getbootstrap.com/css/#grid).
   + [Download and play around with Bootstrap's examples](http://getbootstrap.com/getting-started/#examples) or start with [a blank, basic template](http://getbootstrap.com/getting-started/#template).
 - [Basscss](http://basscss.com/) (for even more basic site styling and layout).
 - [GitHub API documentation](https://developer.github.com/v3/).
 - [Code organization guide from jQuery](https://learn.jquery.com/code-organization/).
 - [Some examples of well-done, clean, professional websites](https://www.awwwards.com/websites/clean/).
 - [Some examples of **bad** web design. Use these as examples of what **not** to do](http://www.webpagesthatsuck.com/bad-web-design.html).
 - [![Awesome](http://i.imgur.com/S7qSVFP.png)](https://github.com/sindresorhus/awesome) Links
   + [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript)
   + [Awesome jQuery](https://github.com/petk/awesome-jquery)
   + [Awesome HTML5](https://github.com/diegocard/awesome-html5)
   + [Awesome CSS](https://github.com/sotayamashita/awesome-css)
   + [Awesome Web Design](https://github.com/nicolesaidy/awesome-web-design)
