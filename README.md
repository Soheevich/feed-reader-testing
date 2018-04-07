# Testing Using Jasmine

The legend is: In this project I am given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included Jasmine and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where I come in.

## Tests

* _RSS Feeds_ — This suite is all about the RSS feeds definitions, the allFeeds variable in our application.

..* _are defined_ — It tests to make sure that the allFeeds variable has been defined and that it is not empty.

..* _urls are defined and not empty_ — This test loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.

..* _names are defined and not empty_ — This test loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

* _The menu_ — This suite is about the menu and its visibility.

..* _is hidden by default_ — This test ensures the menu element is hidden by default.

..* _changes visibility when the menu icon is clicked_ — This test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

* _Initial Entries_ — This suite is about initial entries.

..* _total amount is greater than 0_ — This test ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.

* _New Feed Selection_ — This suite is about the feed behavior.

..* _the content actually changes_ — This test ensures when a new feed is loaded by the loadFeed function that the content actually changes.

## Instructions

— Download or Clone this project and open index.html with your browser to see all tests.