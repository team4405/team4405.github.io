# Team 4405 Jekyll Website

## Synopsis

This is the repository for Team 4405's website. It is written in Jekyll and then compiled and hosted on Github Pages. 

## Submissions

If you are submitting a post, use  the following template and fill in the information. Save the file in the format:

```
YYY-MM-DD-title-no-spaces.md
```

and email it so [software@team4405.com](mailto:software@team4405.com) and we will post it. Please attach any images and refer to them by the same file name in your post.

## Post Example

```
---
layout: page-fullwidth
subheadline:  "SUBHEADLINE"
title:  "TITLE"
teaser: 'TEASER'
categories:
    - CATEGORY1
tags:
    - TAG1
header: no
---

The text of the post goes here.
```
For more information on how to use Markdown, go to [markitdown.net/markdown](http://www.markitdown.net/markdown) and you can try it out on that page.

You can add this block just under `header: no` and before the `---` if you want a header image to go with your post
```
image:
    title: IMAGE.jpg
    caption: CAPTION
    caption_url: CAPTION-LINK
```

## Local Installation

To develop this site locally, first `git clone` this repo and make sure you have ruby and jekyll installed. You can then `cd` into this directory and run `$ jekyll serve --config _config.yml,_config_dev.yml` to start a local server and navigate to [http://localhost:4000](http://localhost:4000).

## License

A short snippet describing the license (MIT, Apache, etc.)
