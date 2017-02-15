---
title: another regex memo
date: 2017-02-16 01:12:58
tags: regex
---
for (xxx) => for xxx
```
replace(str, "for\s?\((.*?)\)", "for $1")
```
