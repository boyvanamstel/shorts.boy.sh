---
layout: post
title: ''
date: 2018-12-14 13:13:41.000000000 +01:00
---
There's a reason why I'm super explicit with `Flags` and `Preprocessor Macros`. If I need to distuinguish between an app target build for the Mac App Store and a non-MAS build, there's a `MAS` flag and a `NONMAS` flag. Just so I can check for `#if MAS` and `#if NONMAS`.

I just figured out a method wasn't being called because I was checking `#ifndef APPSTORE` instead of `ifdef APPSTORE` (notice the missing `n`) in an older app where I wasn't so particular about flags yet. That's an hour wasted. 😑
