---
layout: post
title: "Get Product Name"
excerpt: "Programmatically determine the name of your Eclipse RCP product."
description: "Programmatically determine the name of your Eclipse RCP product."
categories: [Eclipse RCP, Java, blog]
tags: [rcp product]
author: kerner1000
comments: true
share: true
---


```java
public static String getProductName() {
        return Platform.getProduct().getName();
    }
```
