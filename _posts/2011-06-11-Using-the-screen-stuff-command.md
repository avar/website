---
title: Using the screen(1) `stuff` command
layout: post
tags: Unix, GNU, screen
---

I use [GNU screen](http://www.gnu.org/software/screen/) a lot to
manage pretty much everything I run on my computer, and everything I
run on remote systems (well, aside from cron).

When I go into work I spawn a screen which in turns connects to other
machines which are also using screen. I didn't know about the `stuff`
command until recently, but now I don't have to manually run
e.g. `screen -rx` to connect to these nested screens, or cd to some
directory.

See
[this commit to my dotfiles.git](https://github.com/avar/dotfiles/commit/28da7b7ddceb32cde0b7b6642af5df9f6e4efdec)
for the small change I made.

It's really handy.
