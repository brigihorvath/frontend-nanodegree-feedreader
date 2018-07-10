# Feed Reader Testing Project
 ===============================

A Udacity Front-End Developer Scholarship Project - 2018


In this project I was given a web-based application that reads RSS feeds. They've already included [Jasmine](http://jasmine.github.io/) and even started writing the first suite, so I had to write the following tests:
*  A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
*  A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
*  A test that ensures the menu element is hidden by default.
*  A test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
*  A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. loadFeed() is asynchronous so this test requires the use of Jasmine's beforeEach and asynchronous done() function.
*  A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. loadFeed() is asynchronous so this test requires the use of Jasmine's beforeEach and asynchronous done() function.

## Table of Contents

* [Running the Feed](#RunningTheFeed)
* [Dependencies](#dependencies)
* [Contributing](#contributing)

## Running the Feed
If you want to load the game locally,  you should first clone the repository and open index.html in the browser.

## Dependencies
For using the project, you should be able to reach the following:

- Google Fonts (http://fonts.googleapis.com/css?family=Roboto:400,100,300,700)
- JQuery (http://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js)
- Handlebars (http://cdn.jsdelivr.net/handlebarsjs/2.0.0/handlebars.min.js)
- JSAPI (http://google.com/jsapi)


## Contributing

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).
