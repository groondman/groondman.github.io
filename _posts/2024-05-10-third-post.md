---
layout: post
title: third post
date: 2024-05-09 17:00:00
description: updates + blog development
tags: planning updates
categories: development
---

#### Third post!
Going to probably make these less frequent and not daily.

Updated working list:
- Blog ideas:
  - primary post (about page)
  - singular china vacation blog
  - mahjong (given it's a current interest)
  - biking
  - cat blog?
- Fix up the main page
- go to _themes.scss and set my own color theme
  - change the color of the footer. It's too bright.
  - change the accent color. Blue is alright but I could do orange or something else.
- set up some of the previous "projects" i've done
- create a "school" section where I can make a collection
- set up an archive of more private posts
- set up a CV
- figure out how the "check for broken links" workflow keeps breaking. It has something to do with `demo.html` in the default template's blog post `distill.md`.

Here's a bit of a test on including some photos in the blog. Consider the current screenshots of the developing blog as a test on how I'll include images in the future.
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2024-05-10-third-post/about.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2024-05-10-third-post/blog.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2024-05-10-third-post/secondpost.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2024-05-10-third-post/projects.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/2024-05-10-third-post/school.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>