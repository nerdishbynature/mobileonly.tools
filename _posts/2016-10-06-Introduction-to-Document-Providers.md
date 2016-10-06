---
layout: post
title: iOS has no file system? Introduction to Document Providers
twitter_username: pietbrauer
categories: blog
readtime: 3 min read
header_image: "/img/2016-10-06-Introduction-Document-Providers-Header.jpg"
---

__Many people believe iOS has no file system like a Mac or PC. But as always it is just different than what you are used to. Join me on a small journey into the files and folders of iOS. After that you will be delighted how great iOS is at handling files.__


Files are essential to your daily work and entertainment. It is important for a modern operating system to handle all file types well and let users interact them in all ways possible. Of course iOS is no different here. Files were on the first iPhone and the latest iPad pro. What is missing from iOS is a central app that lets you browse all files on your storage. macOS has the Finder, Windows the Explorer and iOS? Document Providers.

## Overview

The way iOS handles files is revolutionizing and different from what you are used to. Until iOS 8 you could barely exchange files between apps but thankfully that changed.
Document Providers where introduced in 2014 to help apps like Dropbox and Google Drive bring the file you have in the cloud to your local device and your apps. Document Providers support four different modes of interaction: Import, Export, Open and Move. This may be hard to grasp, but I will give you an example for each of them:

- __Import__: Import a photo you stored in Dropbox into [Pixelmator](https://itunes.apple.com/en/app/pixelmator/id924695435?mt=8)
- __Export__: Export a photo from [Pixelmator](https://itunes.apple.com/en/app/pixelmator/id924695435?mt=8) to Google Drive
- __Open__: Open a markdown file from [Documents](https://itunes.apple.com/us/app/documents-5-file-manager-pdf/id364901807?mt=8) in [Ulysses](https://itunes.apple.com/us/app/ulysses/id950335311?mt=8) and edit the contents in place
- __Move__: Move a text file from [Ulysses](https://itunes.apple.com/us/app/ulysses/id950335311?mt=8) to [Documents](https://itunes.apple.com/us/app/documents-5-file-manager-pdf/id364901807?mt=8) (this will delete the file in Ulysses)

As you can see, you can do any operation you want using document providers. Unfortunately they aren't unified and it depends on the app you are using which operations they support and how they are implemented. But lets dive into the examples.
For most of our articles I need to take screenshots, alter them in different ways and import them into Ulysses. To do so, I use iCloud Drive, Workflow and Pixelmator.

## Export Pictures to iCloud Drive

For this article I made screenshots to show you the different actions. I took the screenshots, framed them using [Workflow](https://workflow.is/workflows/ffd63c38cfc94b2c888cf4f15d0f9f22) and exported put them into a folder in Photos. After I annotated them, I export them into iCloud Drive and organize them into my folder structure.

![](/img/2016-10-06-Document-Provider-1.PNG)
![](/img/2016-10-06-Document-Provider-0.PNG)

## Edit in Pixelmator

Now that all my photos framed and named, I can edit them in Pixelmator to blur off parts of the screenshot. To do that import them from iCloud Drive using the `Add` icon in the upper left corner and choose `iCloud Drive`. After I have done my edits, I choose the `Share` icon in the navigation bar and choose `Send to iCloud Drive` and export the image as JPEG file to iCloud Drive.

![](/img/2016-10-06-Document-Provider-4.PNG)

## Conclusion

This is a small introduction on working with Document Providers and I am sure you will notice them from now on if you haven't already. One hint: they are often labeled as `iCloud Drive` even if other apps offer the same Document Provider features. You can switch between them using the `Locations` button in the navigation bar.

![](/img/2016-10-06-Document-Provider-5.PNG)