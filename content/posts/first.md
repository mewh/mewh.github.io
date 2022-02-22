---
title: "First Post and Welcome to My Blog!"
date: 2022-02-22T16:36:19+09:00
# weight: 1
# aliases: ["/first"]
tags: ["web", "dev", "meta"]
author: "Matthias Harvey"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "New Site and Blog."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: true
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/mewh/mewh.github.io/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
For this first post I'll discuss why I chose to make this site using [Hugo](https://gohugo.io/) instead of other technologies.

My choice was guided by the following:
- Fast - get a score of 100 (or very close) on [PageSpeed Insights](https://pagespeed.web.dev/)
- Stay away from PHP
- Easy management of SEO
- Fast to add new content
- Low complexity

WordPress sites can be notoriously slow, but for interest's sake I decided to check out the speed of a WordPress site using the newest version and a lightweight theme.
The [TWENTY TWENTY-ONE](https://wp-themes.com/twentytwentyone/) theme looked quite nice and lightweight. It got an okay [PageSpeed Insights score](https://pagespeed.web.dev/report?url=https%3A%2F%2Fwp-themes.com%2Ftwentytwentyone%2F). At the time of writing I got a mobile score of 92 and a desktop score of 99.

Not too bad, but it's just a basic blog site....

Previously I've used [Jekyll](https://jekyllrb.com/), but so far I'm liking Hugo.  I tried a few Hugo theme demo sites on PageSpeed Insights and they all got a score of 100. The asset minification and the fact that it's all statically generated contributes to its speed.

I'll see how it goes if I need to do more customising, but so far Hugo looks great.

At some point I also want to look into the feasibility of using Hugo for sites for customers that want to be able to add and modify content themselves. I know there are some nice markdown editors for github, or one can use github directly, but the layperson wants something like WordPress's interface.
