---
layout: post
title: Setting up a new Jekyll Blog
date: 2022-06-14 12:00:00 -0600
categories: [General,Blog]
tags: [blog,Jekyll]
---
Knowing for a while now that I'd eventually need a website to showcase research, I've been on the lookout for solutions.  I currently use [Obsidian](https://obsidian.md) for a notes solution -- and I like it quite a bit.  It's introduced me to [Markdown](https://www.markdownguide.org/basic-syntax/), which has been very quick to learn.  Additionally, Obsidian allows for LaTeX-like math using [MathJax](https://www.mathjax.org) and has a great option for embedding code.  Did I mention it's free?  What isn't free however is Obsidian Publishing, which currently is $20 a month -- more than I pay for 2TB of cloud storage from Google.  This seems excessive for hosting what are essentially just text files (Obsidian files are stored as markdown files).

I'd seen [other PhD students](http://jhamrick.github.io/quals/) use markdown sites hosted on Github for material related to comprehensive exams and thought that looked like a good idea.  Additionally, GitHub Pages uses markdown, which would allow for easy cross-posting of my Obsidian notes (since they're already Markdown).

Unfortunately, someone already owned the URL for my name (thanks a lot [Dane](https://www.danecannon.com) - just kidding, he's actually a really nice guy!), so I bought PhDane.com and went about configuring the Github page as a custom domain.  Turns out there is a great static site generator - [Jekyll](https://jekyllrb.com/) - which is widely used and has a large number of open-source themes available for use.  I opted for using the excellent [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, which also allows for MathJax and even Mermaid diagrams.  It integrates some Google Analytics features that I might jump into in the future.  I have no experience with Ruby (Jekyll is based on Ruby) or HTML/CSS and little experience with Github, but figured it out after a couple days.  If you're trying to do this too, I'd suggest this video...

<iframe width="560" height="315" src="https://www.youtube.com/embed/F8iOU1ci19Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

And here's the [issue that hung me up for a bit...](https://github.com/cotes2020/jekyll-theme-chirpy/issues/502)

