---
layout: post
title: blog 포스팅 테스트
description: "블로그 포스팅 테스트"
tags: [sample post]
author: Haan
image:
  background: triangular.png
---

Here be a sample post with a custom background image. To utilize this "feature" just add the following YAML to a post's front matter.

```yaml
image:
  background: filename.png
```

This little bit of YAML makes the assumption that your background image asset is in the `/images` folder. If you place it somewhere else or are hotlinking from the web, just include the full http(s):// URL. Either way you should have a background image that is tiled.

If you want to set a background image for the entire site just add `background: filename.png` to your `_config.yml` and BOOM --- background images on every page!

