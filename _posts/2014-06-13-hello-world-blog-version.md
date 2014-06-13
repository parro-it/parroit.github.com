---
layout: post
title: "Hello world, blog version"
description: "This is the universally present hello world, in blog version"
category: blog
tags: [about-blog]
---
{% include JB/setup %}

# Hello world, blog version

### TL;DR

    Hi people, this the first post of my new blog.
    I named it `Hello world`, because I'm basically using it to 
    try [jekyllbootstrap](http://jekyllbootstrap.com/) features.

## What I'm doing in this post

I'm writing this post while I improve the blog status, so I'll include:

* some review of _jekyllbootstrap_ (JB from now) and the step I'm doing to configure it
* some explanation of what I'll write in this blog
* some presentation about myself

So, start with the first point...

## About JB:

I start following [the quick-start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html) step by step.
It was really easy to get started, the tutorial promise 3 minutes to be up and running, but it's been
really a question of some seconds...

### But...

Some minutes later, I received an e-mail from GH, stating this:

    The page build completed successfully, but returned the following warning:

    Your site is using Maruku, the default Markdown interpreter. Maruku is now obsolete and may cause builds to fail for sites with invalid Markdown or HTML. See https://help.github.com/articles/migrating-your-pages-site-from-maruku for more information on upgrading to a newer Markdown interpreter. 

    For information on troubleshooting Jekyll see:

      https://help.github.com/articles/using-jekyll-with-pages#troubleshooting

    If you have any questions please contact us at https://github.com/contact.

And gosh... I receive the same e-mail each time I publish a change to the post...

So I now start to migrate my-pages-site-from-maruku as suggested.

The upgrade appear to be very simple: 

I just changed _config.yml file, adding following line at the root level:

```
markdown: kramdown
```

and I'm now no more receiving e-mails as I push changes...

## Interlude: about me

I'm not an english native speaker, so please pardon my english if it'll 
become to error prone...

By the way:

1. I hope to improve it by writing this blog
2. I hope to that JB has a way to setup a grammatical correction tool

## Back to JB

### Ok, let's continue improving the basic blog layout

Second step: I wish to improve the layout, because there is by default an annoyng 
_AROUND THE WEB_ section above my post.


