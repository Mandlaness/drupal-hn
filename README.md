# Hacker News Web App

## Task

In this assessment, we are going to build a Hacker News clone.

You will be required to write a custom site that periodically fetches the latest news items using the hacker news API.

The documentation for the API can be found here: https://github.com/HackerNews/API

## Your application should:

* Fetch the news items periodically for top stories, new stories and best stories.
* Create and store the news item in a SQL database
* You should also fetch all the comments associated with the news item and store them in the database
* Create a view that displays the content as per the hacker news site with the associated detail page that includes the item's comments.
* MVC/ similar architecture is encouraged.
* You may use any PHP framework of your choice. Drupal 8 is preferred however use what you are most familiar with. I used Drupal.
* Styling, documentation and design will award bonus points, as the core focus of the assessment will be the quality of the code.

### Bonus

* Style your site to look like the hacker news site.
* Any technical design documentation and specs.
* Database design (if applicable).


### Considerations

* Your site should only fetch the top 500 stories and build from there, there is no need to go much further than that.

### Submission
* You can submit your Database and/or code via Dropbox, Wetransfer, GitHub Repo or any other online storage provider you prefer, simply add the link to the file to the end of the readme of your forked repo.


## Quick Start

Clone repository

Run `composer install` to install Drupal and dependencies.

### PHP Server setup

```
 cd web

 php -S localhost:8080
```

Visit http://localhost:8080 and install Drupal to begin.

Admin: mandla / P@ssw0rd@2020

DB: https://we.tl/t-BKOma3hXOd
