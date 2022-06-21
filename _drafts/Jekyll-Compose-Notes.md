---
layout: post
title:Jekyll Compose Notes
date: 2022-06-21 12:00:00 -0600
categories: "[Category,Subcategory]"
tags: "[lowercase tags]"
---

See [here](https://github.com/jekyll/jekyll-compose) for more commands.

Create a new draft
```bash
bundle exec jekyll draft "My new draft"
```

Publish your draft (remember to use the date in the title)
```bash
bundle exec jekyll publish _drafts/my-new-draft.md
```

Rename post
```bash
bundle exec jekyll rename _posts/2014-01-24-my-new-draft.md "My New Post"
```