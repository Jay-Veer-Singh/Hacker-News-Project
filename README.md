# Hacker-News-Project

Here I build is a nicer version of Hacker News.

Programmer usually read Hacker News because it's a great way to stay up to date with the industry and just learn about general programming news.

They have some really, really nice articles here, and a lot of programmers use Hacker News as a way to stay up to date with the industry. This page has a ton of information.

As a matter of fact, every time you refresh, it's a new topic. New thing.

Now, in order for me not to get overwhelmed, I usually only like reading or checking out the stories that have over 100 points. That is, they've been upvoted by users.

So I build the tool using web scraping and find out all the stories that have over 100 points because those are the most popular ones, maybe the most important ones.

here I scrape this data and then I remove all the stories that have less than 100 points so that I can only focus on the important news articles.

In order for us to scrape this website, we want to use a tool called Beautiful Soup.

It's a library that we can use in Python to scrape websites.

first thing we're going to do is to actually import requests.

And the other thing is the beautiful soup.

Well, beautiful soup actually allows us to use the HTML and grab different data.

It enables you to extract data from HTML and XML files, making it easier to navigate, search, and modify the parse tree. Beautiful Soup provides a convenient way to extract information from web pages, particularly when combined with the requests module for downloading the HTML content

So it allows us to use that data that we've gathered to do whatever we want to it to scrape it

What beautiful soup allows us to do is to do something called Parse.

That is, we can use beautiful soup to convert a string to an actual object that we can manipulate and use.

we parse it, that is, we tell it, hey, this data needs to be modified into a HTML that we can actually use.

So the way we do that with beautiful soup is we simply say HTML.parser.

And this tells beautiful soup that, hey, this is HTML and I want you to parse it. So convert it from a string to something that we can actually use. And this creates what we call a soup object.

The requests module in Python is a powerful tool that allows you to send HTTP requests easily. It is commonly used for retrieving content from the web, such as downloading HTML, making API requests, and performing various other HTTP operations.
