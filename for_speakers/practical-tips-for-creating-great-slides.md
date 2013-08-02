---
layout: for_speakers
title: Practical tips for creating great slides
for_speakers: true
list_order: six
summary: Great slides can enhance your arguments. Awful slides can take away all of the focus from what you're saying.
---

# {{ page.title }}

Great slides can enhance your arguments, provide a compelling counter-point to your talk,
and help create dynamic tension.

Awful slides can take away all of the focus from what you're saying, bore your audience
into a stupor, or provide reading light while the audience checks their emails.

## Make it readable

That means big, big fonts, excellent contrast, and using the top half of the screen in
preference to the bottom half, since part of the audience might be sitting behind other parts
of the audience.

## Avoid bullets

No, really. If you need notes, put them on paper cards, or in the presenter view in your presenter software.
The audience will read ahead of you, and then will go straight to their email.

Instead, reduce the text on the slide to just the theme of what you are speaking about.
If you can get away with it, just use one word. Or even better, an image.

## Use code carefully

Code is tricky. It requires context. <!-- A point made in code generally requires a fair amount of it. -->

A few things to note:

* Use as big a font as you can get away with
* Go with dark text on light background
* Use syntax highlighting
* Simplify your sample until only the absolute minimum is left

If you take screenshots, make sure you can make the image large enough without getting fuzzy.
If you don't take screenshots, you're going to want to look into something that creates syntax highlighted
.rtf versions of your code.

The python library pygments is a good choice.
You'll need [a decent color schema](https://github.com/kytrinyx/talkode/blob/master/presentation.py).
That one is based off of github's syntax highlighting, and was used to create [these sample slides](http://www.slideshare.net/kytrinyx/code-slides).

If you're [emulating terminal output/commands](http://www.slideshare.net/kytrinyx/terminal-slides) a black background will work, but make sure that the font color is extremely bright.

## Resources

* [Better Presentation Slides (video)](http://www.youtube.com/watch?v=QO0cM48LliI)
A lightning talk by Shane Becker (@veganstraightedge)
* [Slide Design For Developers](http://zachholman.com/posts/slide-design-for-developers/)
A blog post by Zach Holman (@holman)
* [Improve Your Technical Slides](http://nubyonrails.com/articles/improve-your-technical-slides)
Excellent tips about colors, fonts, and using code.
* [5 Things Every Presenter Needs To Know About People](http://vimeo.com/44267609)
5 minute video by Dr. Weinschenk, including tips on how to use slides.
* Add your advice! [Make a pull request](https://github.com/janl/waaa)

