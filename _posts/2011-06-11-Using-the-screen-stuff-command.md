---
title: Using the screen(1) stuff command
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

It's really handy.
