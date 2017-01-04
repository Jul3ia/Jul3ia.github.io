---
layout: post
headline: "Become a Runtime Constraint Issue Debugging Jedi"title: or, How to keep from throwing yourself out a window over Autolayout issues with just a few easy Xcode debugger console commands
categories: blog
tags: [xcode, runtime issues, Autolayout, Interface Builder, UIViewAlertForUnsatisfiableConstraints, storyboard, nib, xib, constraints]
---

Autolayout issues can be a pain. We’ve all seen those familiar error messages at runtime in our Xcode console, but hesitate to change anything in our storyboards or nibs, because seriously, who wants to open *that* can of worms? Well, here are a few simple tricks that might ease your reluctance to open those dreaded files, and hopefully also save you from digging endlessly through the IBHaystack to find the offending element.

Take a look at this typical example of a runtime constraint issue in Xcode:
