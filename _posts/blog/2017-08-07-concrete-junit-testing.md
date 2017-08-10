---
layout: post
title: 'Failure-Driven JUnit Testing'
description: 'Some concrete adivces on how to efficiently do JUnit testing.'
excerpt: 'Some concrete adivces on how to efficiently do JUnit testing.'
categories: [Java, blog]
tags: [testing, junit, unit]
author: kerner1000
comments: true
share: true
---

---
> Unit testing is as time consuming as it is time saving.

* **Do not just write random tests.** Start prototyping, use your app and only test if you run into problems (which usually happens immediately). Failures will tell you what to test, which is why every single test you write will fail first and will address a real world problem. Only one exception: Always test identity (`hashCode()` & `equals()`) right at the beginning. If identity calculation of your types is erroneous you are lost!
* **If you have already some type hierarchy, start at the bottom, not the top**. This will save you some duplicate testing. If a type at the bottom has some failing tests, try to test the same thing for the super type and so on. Only if you cannot map the failure to the next type up the hierarchy, you need to find the problem right there.