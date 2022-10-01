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

Publish your draft
```bash
bundle exec jekyll publish _drafts/my-new-draft.md
```

Rename post
```bash
bundle exec jekyll rename _posts/2014-01-24-my-new-draft.md "My New Post"
```

Run a local copy of website ([available here](http://127.0.0.1.4000/))
```bash
bundle exec jekyll s
```
---
> Add Markdown syntax content to file `_tabs/about.md`{: .filepath } and it will show up on this page.
{: .prompt-tip }

---
Inserting a local picture
- max width scales it, and the below code is for a centered picture (using a deprecated HTML tag)

<p align="center">
    <img width="80%" img src="../images/TheoryOfPlannedBehavior.PNG" alt="Theory of Planned Behavior">
</p>

OR NON-CENTERED (just markdown)

![Theory of Planned Behavior](/images/TheoryOfPlannedBehavior.PNG =80%x)