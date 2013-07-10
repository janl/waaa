# We Are All Awesome

A blog with the intention of motivating, encouraging, and helping people begin speaking at conferences.

The site contains/will contain advice on generating ideas and writing proposals, links to great talks, conferences with open CFPs, etc.

## How Contribute

1. [Fork the repository](https://help.github.com/articles/fork-a-repo)
2. Make your changes
3. [Submit a pull request](https://help.github.com/articles/using-pull-requests)

### Powered with Github Pages + Jekyll

This blog is powered with [Github Pages](https://help.github.com/articles/using-jekyll-with-pages), which is powered with [Jekyll](https://github.com/mojombo/jekyll/blob/master/README.markdown).

The magic: If your repository has a branch named gh-pages, Github automatically creates Github Pages for the repo. If you want to have a blog, you can have *just* a branch called gh-pages. Ta da!

### Text format

All the posts are written in markdown. If you're not familiar with markdown, check out [Daring Fireball's syntax guide](http://daringfireball.net/projects/markdown/syntax).

### Adding a blog post

Posts go in the `_posts` directory, and must be named `YYYY-MM-DD-the-title-of-the-post.md`

Start it off with the following:

```
---
layout: main
title: The Title of the Post
---

# {{ page.title }}
```

(where you'd swap out `The Title of the Post` with the actual title, obviously).

Then add whatever content you want below this header. Write your post in [markdown](http://daringfireball.net/projects/markdown/syntax).

### Eyeballing Your Changes

For small changes, you can safely make a pull request without previewing the changes.

To preview your changes to the site on your machine, you must use [Jekyll](https://github.com/mojombo/jekyll/blob/master/README.textile) to build the HTML version and serve the files.

First, be sure you have Jekyll installed:

    gem install jekyll

Second, in the root of the project, run `jekyll --server` to generate the HTML files, and start the server:

    jekyll --server --auto

`--auto` enables live reload so you don't need to restart the server to see your changes.

When you run `jekyll --server` you'll probably see webrick start up. Look for the port number:

    [2012-06-23 14:02:42] INFO  WEBrick::HTTPServer#start: pid=3642 port=4000

Here it started on port 4000, which is usual. That means that you can see your preview of the site at [localhost:4000](http://localhost:4000/)

## If you have further questions, ask Uncle Google

Actual conversation (with typos corrected) from #stationx on freenode about how I need to write a README

    theophani: so the key thing to google is "jekyll github pages"
    theophani: I had never heard of it before either
    theophani: and spent 2.5 hours being super frustrated that I could not figure out how
               to edit the site after @janl set it up for me.
    theophani: he would have helped, if I'd asked.
    theophani: warning: the actual github pages help are not helpful.
    fnords:    i will use my google-fu to figure it out
    theophani: intro: https://help.github.com/articles/using-jekyll-with-pages
    theophani: actual help: https://github.com/mojombo/jekyll/blob/master/README.textile
    theophani: premise: if you have a branch named gh-pages, you automatically create
               github pages for the repo. if you want to have a blog, you can have JUST
               a branch called gh-pages
    fnords:    aha!
    ln2v:      oh, so they don't actually go into master?
    theophani: exactly
    theophani: I should copy and paste this conversation as the readme :D
    ln2v:      feel free! ;)

station x (cc)
