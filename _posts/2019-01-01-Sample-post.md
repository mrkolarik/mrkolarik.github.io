---
layout: post
title: "Sample post"
author: "Martin Kolarik"
categories: journal
tags: [documentation,sample]
image: forest.jpg
---

## Headings

Sometimes it is useful to have different levels of headings to structure your documents. Start lines with `#` to create headings. Multiple `##` in a row denote smaller heading size. The following demonstrate the full range of heading sizes:

# Heading One (h1)

## Heading Two (h2)

### Heading Three (h3)

[the demo site](https://lenpaul.github.io/Lagrange/).

![alt text](https://user-images.githubusercontent.com/8409329/32631384-17107870-c56e-11e7-932f-deeb7c12e4db.png "Lagrange Demo Image")


## Table of Contents

1. [Introduction](#introduction)
   1. [What is Jekyll](#what-is-jekyll)
   2. [Never Used Jeykll Before?](#never-used-jekyll-before)
2. [Installation](#installation)
   1. [GitHub Pages Installation](#github-pages-installation)
   2. [Local Installation](#local-installation)
   3. [Directory Structure](#directory-structure)
   4. [Starting From Scratch](#starting-from-scratch)


## Example of folder tree structures

```bash
Lagrange/
├── _data                      # Data files
|  └── settings.yml            # Theme settings and custom text
├── _includes                  # Theme includes
├── _layouts                   # Theme layouts (see below for details)
├── _posts                     # Where all your posts will go
├── assets                     # Style sheets and images are found here
|  ├── css                     # Style sheets go here
|  |  └── main.css             # Main CSS file
|  |  └── syntax.css           # Style sheet for code syntax highlighting
|  └── img                     # Images go here
├── menu                       # Menu pages
├── _config.yml                # Site build settings
├── Gemfile                    # Ruby Gemfile for managing Jekyll plugins
├── index.md                   # Home page
├── LICENSE.md                 # License for this theme
├── README.md                  # Includes all of the documentation for this theme
└── rss-feed.xml               # Generates RSS 2.0 file which Jekyll points to
```


```
---
layout:
title:
author:
categories:
tags: []
image:
---
```

`layout` specifies which layout to use, `title` is the page or post title, `categories` can be used to better organize your posts, `tags` are used when generating related posts based on the topic of the post, and `image` specifies which images to use. Have a look at some posts in the `_posts` directory to see how these variables are set.

### MathJax

Lagrange comes out of the box with [MathJax](https://www.mathjax.org/), which allows you to display mathematical equations in your posts through the use of [LaTeX](http://www.andy-roberts.net/writing/latex/mathematics_1).

### Syntax Highlighting

Lagrange provides syntax highlighting through [fenced code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/). Syntax highlighting allows you to display source code in different colors and fonts depending on what programming language is being displayed. You can find the full list of supported programming languages [here](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers). Another option is to embed your code through [Gist](https://en.support.wordpress.com/gist/).

### Markdown

As always, Jekyll offers support for GitHub Flavored Markdown, which allows you to format your posts using the [Markdown syntax](https://guides.github.com/features/mastering-markdown/). Examples of these text formatting features can be seen below. You can find this post in the `_posts` directory as well as the `README.md` file.

## Credits

### Creator

#### Paul Le

* [www.lenpaul.com](http://lenpaul.com)

* [Twitter](https://twitter.com/paululele)

* [GitHub](https://github.com/LeNPaul)
