---
layout: post
title: "Get Product Version"
excerpt: "Programmatically determine the version of your Eclipse RCP product."
description: "Programmatically determine the version of your Eclipse RCP product."
categories: [Eclipse RCP, Java, blog]
tags: [rcp product]
author: kerner1000
comments: true
share: true
---


```java
public static String getProductVersion() {
        final IProduct product = Platform.getProduct();
        final Bundle bundle = product.getDefiningBundle();
        final Version v = bundle.getVersion();
        return v.toString();
    }
```
