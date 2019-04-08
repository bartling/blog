---
title: RQDA on Mac High Sierra
author: ''
date: '2019-04-07'
slug: rqda-on-mac-high-sierra
categories:
  - R
tags: []
comments: no
---

For analyzing qualitative data, I have been trying to take advantage of the flexibility and versitility of R by using the [RQDA](http://rqda.r-forge.r-project.org/) package. It is a useful tool that allows you bring in textual data and develop and implement coding schemes, categorizations and organize multiple files for analysis.

Unlike most R packages, RQDA employs a GUI environment. As such it needs extra dependencies as it is built on the GTK toolkit. I was recently issued a Mac and encountered issues getting RQDA properly working. It boiled down to getting the R package that binds to GTK to properly installed.  This guide from Sebastian Kopf was very helpful in case someone stumbles on this post looking for assistance: [https://gist.github.com/sebkopf/9405675](https://gist.github.com/sebkopf/9405675)

On Mac 10.13.4 I had to use the macports directions he gives. Now it is working like a charm!