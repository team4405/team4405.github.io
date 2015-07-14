---
layout: page
title: "Posting Instructions"
subheadline: ""
show_meta: false
teaser: ''
permalink: "/posting/"
---
## Submissions

If you are submitting a post, use  the following template and fill in the information. Save the file in the format:

```
YYYY-MM-DD-title-no-spaces.md
```

and email it so [software@team4405.com](mailto:software@team4405.com) and we will post it. Please attach any images and refer to them by the same file name in your post.

## Post Template

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

	The text of the post goes here. For more information on how 
	to use Markdown, go to 
	[markitdown.net/markdown](http://www.markitdown.net/markdown) 
	and you can try it out on that page.


You can add this block just under `header: no` and before the `---` if you want a header image to go with your post:

	image:
		title: IMAGE.jpg
		caption: CAPTION
		caption_url: CAPTION-LINK

Otherwise, if you delete the `header: no` then you will get our logo on the top of you post, like this page.
