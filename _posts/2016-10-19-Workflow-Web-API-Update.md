---
layout: post
title: New Workflow Update with Web API Feature
twitter_username: pietbrauer
categories: blog
readtime: 2 min read
header_image: "/img/2016-10-19-Workflow-Web-API-Header.jpg"
---

__Workflow is one of my most loved apps on my iPad and iPhone. A thing I was missing was being able to interact with Web APIs and this is now resolved in the new update. Let us dive in and see what's possible.__


Sometimes the simplest app is one that logs you in to a web service and uploads some text, image or video you created. In a [previous post](https://mobileonly.tools/blog/2016/10/06/Introduction-to-Share-Action-Extensions.html) we discussed Share and Action Extensions in iOS. So why not replace the app with a simple [Workflow](https://itunes.apple.com/de/app/workflow-powerful-automation/id915249334?l=en&mt=8&at=1010lqa9)? Well, now you can do exactly this.

A new Workflow version is now available in the AppStore and extends the familiar *Get Contents of URL* with two more HTTP method options: *POST* and *PUT*. Along with the new methods you also get access to the request headers and body. This gives you nearly endless possibilities.

If you are not familiar what Web Application Interfaces (API) are it will take some time getting used to it. Think of it as a automated way to interact with websites directly. There are APIs for almost every web page or app: [Slack](https://itunes.apple.com/de/app/slack-team-communication/id618783545?l=en&mt=8&at=1010lqa9), [Trello](https://itunes.apple.com/de/app/trello/id461504587?l=en&mt=8&at=1010lqa9), [Mailchimp](https://mailchimp.com/) etc.

I recently wanted to get started with our new online courses and had the desire to write them offline using [Ulysses](https://itunes.apple.com/de/app/ulysses/id950335311?l=en&mt=8&at=1010lqa9) and export them to Mailchimp Campaigns later. This gives me the advantage to track changes made to the campaigns rather then storing them in Mailchimp itself. You can export HTML from Ulysses and I needed a simple action extension that let me upload it to Mailchimp. And almost set off to build a small app for it. I am glad I didn't.

As soon as I heard of the update yesterday I tried it out and was able to accomplish my goal from last week in thirty minutes. It resulted in a workflow that takes Rich Text exported from Ulysses, creates a new campaign in Mailchimp and uploads the HTML to it. All in a matter of seconds.

*Note: To use the workflow you will need a Mailchimp account and an API token from their website.*

![](/img/2016-10-19-Workflow-Web-API-0.jpg)


[__Get the workflow__](https://workflow.is/workflows/253d05fd2e754e56bfeedcc5ce5598f7)

## Conclusion

Having worked with many web APIs in the past, I think Workflow has made it very easy to interact with almost any API that you will find on the web. It is easy to use even for novices. It is extremely powerful in the way it lets you express HTTP requests.
