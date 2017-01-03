---
layout: post
title: "Become a Runtime Constraint Issue Debugging Jedi"
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2017-01-03T08:08:50-04:00
---

Autolayout issues can be a pain. We’ve all seen those familiar error messages at runtime in our Xcode console, but hesitate to change anything in our storyboards or nibs, because seriously, who wants to open that can of worms? Well, here are a few simple tricks that might ease your reluctance to open those dreaded files, and hopefully also save you from digging endlessly through the IBHaystack to find the offending element.

Take a look at this typical example of a runtime constraint issue in Xcode:

## Usage

To enable MathJax support be sure Kramdown is your Markdown flavor of choice and MathJax is set to true in your `_config.yml` file.

```yaml
markdown: kramdown
mathjax: true
```

```
Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]
```

Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]

The only thing to look out for is the escaping of the backslash when using markdown, so the delimiters become `\\[ ... \\]` and `\\( ... \\)` for inline and block maths respectively.
