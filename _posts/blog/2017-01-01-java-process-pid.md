---
layout: post
title: "PID for Java Application"
excerpt: "Get the PID for a Java Application"
description: "Get the PID for a Java Application."
categories: [Java, blog]
tags: [PID]
author: kerner1000
comments: true
share: true
---


If you have multiple Java processes running, your task manager will show them all as a ‘java’ process and there is no way to distinguish them properly (This makes sense, since your application is running inside the JVM which shows up as a ‘java’ process).

Since **Java7**, there is a very handy tool which can give you the information you really want to know:


```bash
$ jcmd
7717 hello-world-0.0.1-SNAPSHOT.jar
32108 sun.tools.jcmd.JCmd

```

A simple table containing the PID and the corresponding jar file.