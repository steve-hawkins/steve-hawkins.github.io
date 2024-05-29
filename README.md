# Waste is a Thief blog

My findings and thoughts on the sustainability of software products.

## Development

There is a .devcontainer file in the repository and I recommend using [GitHub Codespaces](https://github.com/features/codespaces).

This is a [Jekyll](https://jekyllrb.com/) blog hosted on [GitHub Pages](https://pages.github.com/).

Once in vscode make your desired changes and in the terminal run `cd docs/` and then `bundle install` and one of the following to build the site locally:

- `bundle exec jekyll serve` to build as is
- `bundle exec jekyll serve --drafts` to build and show draft posts
- `bundle exec jekyll serve --future` to build and show future dated posts

This will have created a live editing site to browse as you create articles.

To create new articles create a new markdown file in either the `_drafts` or `_posts` directory using the `YYYY-MM-DD-[article-name].md` file name format.

The top few lines of the articles markdown file should include the following:

```cd
---
layout: post
title: "post title"
date: 2024-05-21
tags: tag_here tag_there
---
```

Tags are used to help people search posts as well as update the [tags](https://wiat.io/tags/) page.
