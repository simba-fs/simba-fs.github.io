---
title: Bash Snippet
date: 2023-02-25T15:40:41+08:00
tags: 
  - bash
  - snippet
  - command
  - cli
categories: 
  - linux
  - bash
image: 
---

# Bash Snippet
## Clear broken symlinks
```
 $ find . -type l ! -exec test -e {} \; -exec sudo rm {}  \;
```
