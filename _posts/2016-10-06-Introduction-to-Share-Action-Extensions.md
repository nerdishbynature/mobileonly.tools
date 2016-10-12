---
layout: post
title: Introduction to Share and Action Extensions
twitter_username: pietbrauer
categories: blog
readtime: 4 min read
header_image: "/img/2016-10-11-Share-Action-Extensions-Header.jpg"
---

__Share and action extensions are invaluable when working on iOS and you may not even know that you have used them. We will go over the basic concepts of extensions and highlight a few great ones in this article.__


There are two types of extensions present in iOS apps: share and action extensions. Both are valuable in your daily workflows and developers created unique ways to interact with them. Use share extensions are to share text, images or videos to social networks or other apps. Think of it as *leaving the current app and continuing in another*. Use action extensions to *modify content in place without leaving the app*. Examples of share extensions are:

- Share to (Facebook, Twitter, Reminders, Notes etc.)
- Import with (Dropbox, Mailchimp, PDF Expert etc.)

![](/img/2016-10-11-Share-Action-Extensions-0.jpg)

While these examples look straight forward, everything that does not fit into the above list should be an action extension:

- Print
- Copy
- Run Workflow
- Save Image

![](/img/2016-10-11-Share-Action-Extensions-1.jpg)

They can be application specific. A developer can decide if his action extension is only available in their app only or in any other. The only way to get it out of their apps is to talk to them and ask them to make it available.

## Share Extensions

Any action in a share extension will take the selected content and send it to another app by either leaving the current app or by displaying a share sheet:

![](/img/2016-10-11-Share-Action-Extensions-2.jpg)

Developers can provide custom UI, like Notes, or use the standard look and feel, like Twitter.

There is a third kind of share extensions that gets automatically added when a developer supports certain types of files. These follow the naming scheme *Copy to…* (before iOS 10) and *Import with…* (iOS 10). They take the selected file and copy them into the selected app. This is similar to document providers discussed in our [Introduction to Document Providers](http://mobileonly.tools/blog/2016/10/06/Introduction-to-Document-Providers.html) article.

![](/img/2016-10-11-Share-Action-Extensions-3.jpg)

## Action Extensions

Share extensions follow some kind of order but with action extensions, it feels like the wild west. Developers can add application specific action extensions, some action extensions should have been share extensions, some leave the app, some stay within the app. But with great chaos come great possibilities.

Examples of application wide action extensions are *Print* by Apple and *Run Workflow* by [Workflow](https://itunes.apple.com/us/app/workflow-powerful-automation/id915249334?mt=8), let us see what they can do for us.

### Print

Apple introduced AirPrint in iOS 4.2 along with the iPad. Users coming from macOS will miss a function called "Print as PDF" known from the print dialogue. Until iOS 10 developers had to build it themselves, but now Apple integrated it into the standard AirPrint action extension.

You can try it out yourself by going to notes and select the share icon (Square box with an upwards facing arrow) and tapping *Print* this will give you the print dialogue and you could select a network printer. Now pinch on the preview of the page and it will open a QuickLook window where you select the share icon again and you can export or email a PDF from iOS.

![](/img/2016-10-11-Share-Action-Extensions-4.jpg)

### Run Workflow

Workflow is an app that lets you build small apps yourself and use them anywhere in iOS by running as an action extension. We showed you [7 Workflows we cannot live without](http://mobileonly.tools/blog/2016/06/08/7-Workflows-we-cannot-live-without.html) in a previous article.

A workflow I use when writing this blog is the [Screenshot Builder Action](http://mobileonly.tools/blog/2016/06/08/7-Workflows-we-cannot-live-without.html) which takes a screenshot and posts the device frame around it so it looks beautiful.

Action extensions not only work on files, but on urls and text as well. An interesting workflow is to [tweet the currently selected text in a Safari Webpage](https://workflow.is/workflows/3d6d2b5d4ce746ed87bc97ef2ea6cfc9).

![](/img/2016-10-11-Share-Action-Extensions-5.jpg)

## Conclusion

As you see, share and action extensions are great ways to take advantage of system functionality or even extend them using Workflow. One important thing to note is that action extensions provided by other apps are not displayed automatically. Tap on the more Icon in the list and enable them. Once you enabled them you will see them all around iOS and it will help you accomplish your daily tasks even faster.


