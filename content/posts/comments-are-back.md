---
title: "Comments Are Back"
date: 2022-09-22T21:09:53-04:00
draft: false
featured_image: '/images/disqus.jpeg'
tags: ["blog"]
---

Moving to a static website generator like [Hugo](https://gohugo.io) from a CMS tool like [Wordpress](https://wordpress.org) does come at the cost of losing built in features like comments. Hugo provides support for several  third party providers for comments.

After looking at a few, I decided to go with [Disqus.](https://disqus.com) Disqus provides for a free option. Ad supported of course, the saying "nothing in life is free" is not more apparent than on the Internet. This blog is a hobby for now so a few ads is a small price to pay.

The process to set up Disqus was straightforward. After the initial account set up, you add a site giving a shortname and the site url. The set up on hugo with the [Ananke](https://themes.gohugo.io/themes/gohugo-theme-ananke/) theme simply required adding an entry to ```config.toml.```

```toml
disqusShortname = 'welovelsu'
```

After adding the config entry, hugo took care of the rest. Please drop a comment and let me know what you think.
