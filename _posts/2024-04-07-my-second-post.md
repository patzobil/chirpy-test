---
layout: post
title: My Second Post
date: '2024-04-07 03:07:53 +0200'
categories:
- Diagrams
- Mermaid
tags:
- sys
- jekyll
- swimminglanes
- mermaid
pin: false
authors:
- Bill
- Grig
toc: true
comments: true
mermaid: true
---
```mermaid
sequenceDiagram
    Alice ->> Bob: Hello Bob, how are you?
    Bob--x Alice: I am good thanks!

    Bob-->>John: How about you John?
    Bob-x John: I am good also, thanks!

    Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    Alice-->Bob: Checking with John...
    Alice->John: Yes... John, how are you?
```