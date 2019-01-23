---
layout: post
title: ''
date: 2018-11-28 13:09:07.000000000 +01:00
---
_Always_ test your brand new app with all its defaults removed before you launch it. 💡

Here's how to do that:

* Quit the app.
* Run this terminal command:

```$ defaults delete [bundle id]```

So for my new app Relax it's:

```$ defaults delete com.dangercove.Relax.Mac```