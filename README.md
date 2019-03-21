# Jekyll
> Just playing with Jekyll

##  Install dependencies
```sh
$ sudo bundle
```
## Run
```sh
$ bundle exec jekyll serve
```
## Add post

```sh
$ bundle exec jekyll post
```
## Front Matter
if you look at `_posts/<post>.md`

you'll see this yaml snippet
```
---
layout: post
title: hello world
date: 2019-03-17 02:53 -0400
category: personal 
tags: fun
---
```
This is called the  `front matter` and contains metadata about the post 