# We Are All Awesome

A blog with the intention of motivating, encouraging, and helping women and other minorities to begin speaking at conferences.

The site contains/will contain links to great talks, advice on generating getting ideas and writing proposals, conferences with open CFPs, etc.

## Contribute

1. Fork the repository
2. `gem install jekyll`
3. Make your changes
4. Submit a pull request

### Text format

If you're not familiar with markdown, check out [Daring Fireball's syntax guide](http://daringfireball.net/projects/markdown/syntax).


### Adding a blog post

Posts go in the `_posts` directory, and should be named `YYYY-MM-DD-the-title-of-the-post.md`

Start it off with the following:

    ---
    layout: main
    title: The Title of the Post
    ---

    # {{ page.title }}

(where you'd swap out `The Title of the Post` with the actual title, obviously).

Then add whatever content you want below this.

### Eyeballing Your Changes

In the root of the project, run `jekyll` to generate the html files.
Then go to the `_site` directory and run the server.

    cd _site
    jekyll --server

When you run `jekyll --server` you'll probably see webrick start up. Look for the port number.

    [2012-06-23 14:02:42] INFO  WEBrick::HTTPServer#start: pid=3642 port=4000

Here it started on port 4000. That means that I can go see the actual site at (localhost:4000)[http://localhost:4000/]

## If you're still confused, ask Uncle Google

Actual conversation (with typos corrected) from #stationx on freenode about how I need to write a README

```
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
```

station x (cc)
