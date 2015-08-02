---
layout: page
title: Contributing
description: "How to contribute to these pages"
permalink: /contributing/
categories: [meta]
---

## General

This site is built on GitHub [Pages](https://pages.github.com/)
hosting solution, and uses [Jekyll](http://jekyllrb.com/).

Jekyll is a static website generator. It is a somewhat complex piece
of software with its own
[comprehensive documentation](http://jekyllrb.com/docs/home/).

GitHub Pages has great documentation, the most relevant of which to
this site is probably
["Using Jekyll with Pages"](https://help.github.com/articles/using-jekyll-with-pages/).

## Local setup

You need some Ruby basics. There's a million ways to do this, but in
general you must:

* Install Ruby >= 2.0.0
* Install the Bundler gem
* Run `bundle install`

If you use RVM or rbenv, there are `.ruby-version` and `.ruby-gemset`
files in the project root.

To compile and view the site locally, run

    bundle exec jekyll serve

then view the site at
[localhost:4000/community-docs](http://localhost:4000/community-docs).

## Guidelines

* Fork the [repository][repo], check out the gh-pages branch, edit,
  commit, push, and issue a PR!
* The front matter YAML section is required.
* Think about page URLs and use the `permalink` setting in the front
  matter if the default URL isn't appropriate.
* [Den of Clojure](https://github.com/denofclojure) members have
  commit rights for the repository. If you are not a member of the
  group please just contact [one of the owners][owners], who will add
  you.

[owners]: https://github.com/orgs/denofclojure/teams/owners
[repo]: https://github.com/denofclojure/community-docs
