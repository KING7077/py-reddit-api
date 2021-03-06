# CHANGELOG

## February 21, 2022

You can now specify the number of posts you want to fetch in Client.Subreddit() and AsyncClient.Subreddit().
For example:

```py
import reddit

subreddit = reddit.Client('agent', 'key').Subreddit('top', 'memes', 100) # To fetch 100 posts. If a limit is not specified, it defaults to 25
```

Similar for the Async Client

limit does not follow a zero index, but all the methods under Subreddit() follow zero index. This may be changed sooner or later

​- 1.1.4

## February 20, 2022

Bettered the asynchronous implementation of the project. Much faster now. Renamed Client.Subreddit.url to Client.Subreddit.post_url, the same change for the asynchronous client - 1.1.3

## February 19, 2022

Minor changes to the description of the project - 1.1.2

## February 19, 2022

Minor changes to the description of the project - 1.1.1

## February 19, 2022

The project actually works now - 1.1.0

## February 18, 2022

Minor changes to make the project more usuable - 1.0.6

## February 18, 2022

Minor changes to make the project more usuable - 1.0.5

## February 18, 2022

Minor changes to make the project more usuable - 1.0.4

## February 18, 2022

Minor changes to make the project more usuable - 1.0.3

## February 18, 2022

Minor changes to the description of the project - 1.0.2

## February 18, 2022

Initial release - 1.0.1
