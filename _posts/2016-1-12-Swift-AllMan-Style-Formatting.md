---
layout: post
title: Swift AllMan Style formatting
---

Recently i read this article from Erica Sadun:
[swift-bracing](http://ericasadun.com/2015/12/28/swift-bracing/)

I've always preferred Allman Style rather than 1TBS Style.

For objective-C i was using [BBUncrustify](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) to automatically format my code to Allman Style on save.

However, neither clang-format nor Uncrustify work at the moment for Swift langage.

I found this project called Swimat which does Swift Source code formatting.
I published a quick hack to support Allman Style:

Swimat fork with Allman style option: [https://github.com/giln/Swimat](https://github.com/giln/Swimat).

<!--more-->