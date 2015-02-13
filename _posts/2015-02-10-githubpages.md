---
title: "Gittin' it sorted on github"
date:   2015-02-10 18:43:02
categories: "site"
layout: post

---


{{ site.github.project_title }}

Lessons learned while putting this little site together

1. This may well be easier than hexo after all... especially for public stuff.


`_config.yml`

This file contains the configuration.

When `jekyll new` does it's bizzo, it opts for some defaults that don't quite marry with the way that github pages are done.

```yaml
- markdown: kramdown
+ markdown: redcarpet
```

identification (or not)

```yaml
title: siteTitle
email: nope

```
