---
layout: post
title: IAP setting greyed out on developer.apple.com
date: 2018-12-05 12:05:33.000000000 +01:00
---
I'm trying to enable In-App Purchases for [Relax](https://www.dangercove.com/relax), so I can implement the Tip Jar featured in the non-Mac App Store version. 🛠

It's not working though. The setting that allows IAPs to be used is greyed out. I've accepted every agreement there is and have had paid apps on the store for a while now. The only reference I can find about it online is [this StackOverflow post](https://stackoverflow.com/a/41676097). Apparently the issue resolved itself after uploading a build.

![Screenshot of the IAP setting being greyed out](/uploads/2018/93ec424eb9.jpg)

I've done just that, hoping in two days I can update this post. I'm curious about the underlying cause though. 🤔

_Update: I turned "Automatically manage signing" off and on again, and voilà the In-App Purchase feature is enabled. Odd._
