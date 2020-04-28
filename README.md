# What and When to Post on Hacker News for Best Interaction

[Hacker News](https://news.ycombinator.com/) is a site started by the startup incubator Y Combinator, where user-submitted stories, known as "posts," are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

There are two popular post types on Hacker News, Show HN and Ask HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting.

In this notebook I'll compare these two types of posts to determine the following:

- Do Ask HN or Show HN receive more comments on average?
- Do posts created at a certain time receive more comments on average?

## Data
You can find the original data set [here](https://www.kaggle.com/hacker-news/hacker-news-posts). The data I will be working with has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. It can be found in this repository. Below, I'll open the data, store it as a list of lists, and print the first few lists.

## Shoutouts
This notebook is based on a guided project from [Dataquest.io](https://www.dataquest.io/), an online platform to learn Data Analysis and Data Science. The learning goal of the project was to review working with strings, dates and times, and object-oriented programming.
