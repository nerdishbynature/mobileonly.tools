---
layout: post
title: How we write this blog solely on iOS
twitter_username: pietbrauer
categories: blog
readtime: 4 min read
header_image: "/img/2016-10-13-Blog-on-iOS-Header.jpg"
---

__Seven articles into this blog journey I think it is time to talk about our setup. Most of you might not realize that everything on this blog was done on iOS devices, yes also on iPhone.__


My main goal for this blog was to encourage you to see the great value in iOS as a next generation mobile operating system and show ways on how to do things differently. This means laying the groundwork to get you up to speed using iOS more often. I knew this idea is very ambitious and would go out of scope of what I could blog on [Git2Go.com](http://git2go.com/blog.html).

## The blogging engine

Choosing what Content Management System (CMS) powers your blog or website is a key decision, as it is harder to switch later on. I went with [Jekyll](https://jekyllrb.com) for my blogging and host it on [GitHub Pages](https://pages.github.com/), this is a sophisticated setup but once you are familiar with it it means you have no servers or databases to maintain. If I were not a developer, I would have probably gone with [Wordpress](https://wordpress.com/) or [Medium](https://medium.com/). Both enjoy great support throughout iOS apps and are easy to maintain. The way you publish depends on the CMS you use. For me it means using [Git2Go](https://itunes.apple.com/us/app/git2go-git-client-you-always/id963577401?mt=8&at=1010lqa9) and [GitHub](https://github.com) to publish articles. If you chose Wordpress or Medium you can use the [Wordpress](https://itunes.apple.com/us/app/wordpress/id335703880?mt=8&at=1010lqa9) or [Medium app](https://itunes.apple.com/us/app/medium/id828256236?mt=8&at=1010lqa9).

## Coming up with topics

Before we write a new article, we have to brainstorm on articles and let them settle. To organize my ideas I use [Trello](https://itunes.apple.com/us/app/trello/id461504587?mt=8&at=1010lqa9). They have a great iOS app with offline support and optimized for every iOS device. I have 3 columns: *Articles*, *This Week*, *Done*. Future headlines go into *Articles*. They get prioritized in the list and I drag them into the *This Week* column when I do my planning Monday morning. After they are published they go into *Done* which I clean up every once in a while.
This approach enables me to add topics wherever I am, whichever device I am using. All cards and comments get synced with my other devices and I can attach links, lists, images, videos, etc.

## Writing

My goal is to write every single day of the week. Being able to do this mobile is not only the topic of this blog, but crucial to fulfill my writing goal. I am not only able to write mobile but also able to publish from mobile. I write all my articles in [Ulysses](https://itunes.apple.com/us/app/ulysses/id950335311?mt=8&at=1010lqa9) on my iPad Pro in full-screen with typewriter mode enabled. This gives me the great focus I love on iOS. Although the same is possible on their macOS app, I somehow get into the crunch mode when I use iOS. I think it is because apps always were full screen whereas macOS apps where always single windows, sometimes multiple on top of each other and I would rarely move into full screen mode. Somehow I feel like missing out on something when using it on the desktop.

## Publishing

Once I finished writing today's article I use [a Workflow](https://itunes.apple.com/us/app/ulysses/id950335311?mt=8) to send it to my Git app [Git2Go](https://itunes.apple.com/us/app/git2go-git-client-you-always/id963577401?mt=8&at=1010lqa9). From there I put the images into their folder and format the article with metadata so [Jekyll](https://jekyllrb.com) knows who wrote it and can sort the articles.
My girlfriend always proof reads my articles in form of [Pull Requests](https://developer.github.com/v3/pulls/) and once she finishes, I merge it into the `master` branch and GitHub will build the static site you are currently looking at.

## Conclusion

This process might sound complicated if you hear it for the first time but as all the parts are already at your disposal, it is easy to get started with it and publish more articles in less time using iOS. It took me around two to three days to get the site kup and running but you can use something like [Medium](https://medium.com) or [Wordpress](https://wordpress.com) to get up to speed faster. The only thing that matters about writing is the writing, not your blogging engine.