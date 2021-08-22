---
layout: post
title: "Setup Github pages with Jekyll"
subtitle: "because they are awesome"
date: '2021-08-22 17:06:15'
background: '/img/bg-about.jpg'
---

## Background
Setting up blog using Github pages and Jekyll

## Installation:
* Pick a Jekyll theme from :  <https://jekyllthemes.io/>
* Fork the repo:  <https://github.com/StartBootstrap/startbootstrap-clean-blog>
* Change the name of the forked repo to `yourgithubhandle.github.io`
* Pull repo down to run locally (ref: <https://jekyllrb.com/>)
  * Install Jekyll on local machine: `gem install jekyll bundler`
  * From the cloned github repo, run:  `bundle install` to restore project
  * Start jekyll server: `bundle exec jekyll serve` 

* Clean up:
  * Update `_config.yml` file with your details and delete unrelated content.
  * Delete all default post from `_posts.` folder.

## Write Post
* From `_posts/` folder, add mardown file following `year/month/date/post-title` convention
* Add the following details to top of the markdown file:
```
---
layout: post
title: "Setup Github pages with Jekyll"
subtitle: "because they are awesome"
date: '2021-08-22 17:06:15'
background: '/img/bg-about.jpg'
---
```