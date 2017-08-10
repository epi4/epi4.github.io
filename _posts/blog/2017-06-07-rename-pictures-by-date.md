---
layout: post
title: "Rename Pictures by Date"
excerpt: ""
description: ""
categories: [Unix, blog]
tags: [files and folders, rename, pictures]
author: kerner1000
comments: true
share: true
---

---
```bash
exiv2 rename -Fk *
```

+ `-F`: Do not override files. Append '_1' ('_2', ...) to the name of the new file.
+ `-k`: Preserve file timestampls.