---
title: SMU Reading Group 
subtitle: Topics in Applied Math and Data Science
author: Mason A. McCallum 
author-url: "https://wickstrom.tech"
date: 2024-08-28
lang: en
toc-title: Contents
version: v0.1.0
---

## Introduction

## The Basics

This document uses a few extra classes here and there, but mostly it's just markup.
This, for instance, is a regular paragraph.

Look at this horizontal break:

<hr>

## Schedule 
<table>
<thead>
  <tr>
    <th class="width-min">Topic</th>
    <th class="width-auto">Discussion Leader</th>
    <th class="width-min">date</th>
    <th class="width-auto">Supplementary Materials</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>ROM</td>
    <td>Mark devernon</td>
    <td>4/3/1988</td>
    <td>43°45'50.78"N 11°15'3.34"E</td>
  </tr>
  <tr>
    <td>ROM</td>
    <td>Mason McCallum</td>
    <td>4/3/2019</td>
    <td>43°45'50.78"N 11°15'3.34"E</td>
  </tr>
</tbody>
</table>

## ASCII Drawings

We can draw in `<pre>` tags using [box-drawing characters](https://en.wikipedia.org/wiki/Box-drawing_characters):

```
╭─────────────────╮
│ MONOSPACE ROCKS │
╰─────────────────╯
```

To have it stand out a bit more, we can wrap it in a `<figure>` tag, and why not also add a `<figcaption>`.

<figure>
<pre>
┌───────┐ ┌───────┐ ┌───────┐
│Actor 1│ │Actor 2│ │Actor 3│
└───┬───┘ └───┬───┘ └───┬───┘
    │         │         │    
    │         │  msg 1  │    
    │         │────────►│    
    │         │         │    
    │  msg 2  │         │    
    │────────►│         │    
┌───┴───┐ ┌───┴───┐ ┌───┴───┐
│Actor 1│ │Actor 2│ │Actor 3│
└───────┘ └───────┘ └───────┘</pre>
<figcaption>Example: Message passing.</figcaption>
</figure>

## Media
Media objects are supported, like images and video:

![A room in an old French castle (2024)](castle.jpg)

![[The Center of the Web (1914), Wikimedia](https://en.wikisource.org/wiki/Page:The_Center_of_the_Web_(1914).webm/11)](https://upload.wikimedia.org/wikipedia/commons/e/e0/The_Center_of_the_Web_%281914%29.webm)

They extend to the width of the page, and add appropriate padding in the bottom to maintain the monospace grid.


## Acknowledgments
I would like to acknologe Jimmie Adriazola for mentoring and guiding the formation of this reading group.
Marc Devernon for managing the webpage
This webpage is a fork of: https://github.com/owickstrom/the-monospace-web.git So much thanks to Oskar Wickstrom for the nice work
