---
layout: post
title: 'Startup Instructions for RCP Plug-in'
description: 'Defining startup instructions inside the Plug-in itself.'
excerpt: 'Defining startup instructions inside the Plug-in itself.'
categories: [Java, Eclipse RCP, blog]
tags: [startup, start level]
author: kerner1000
comments: true
share: true
---

---


RCP Plug-in start levels can be defined via a product configuration.

![RCP product configuration](/images/rcp-product-configuration.png)

this is not the best way to do it, if a plug-in is optinal, and not neccesarily part of the product (which is of course natural for a plug-in).

You can define start levels as well inside the plug-in iteself:

Create a file:

`META-INF/p2.inf`

Content:

`instructions.configure=setStartLevel(startLevel:4);markStarted(started: true);`