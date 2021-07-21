---
title: Site Template
---

## Writing at This Blog

You can write posts in this blog by sharing your technical experience and new learning. Consider the following steps:
* Create a fork from this repo.
* Under '_posts' folder create a md file with following format 'YYYY-MM-DD-post-title.md)' (example: 2020-09-05-global-webinar-on-edge-computing.md)
* In the file header put the following 

```
---
layout: post
title: "post title"
permalink: blog/post-permanent-link
---
```

* Make a pull request.

Happy coding!

## Blog Syntax

### Layouts (Home)

A page declared with home layout will list all posts located in '_posts' folder.

```
layout: home
```

## Paths

### Minimum Metadata

No perm url has been applied, thus will not be included in blog folder.

Generated page path:

``2021/07/11/minimum.html``

Image path would be considered from root folder.

``images/images/img1.jpg``

![Meeting](images/img1.jpg)  
