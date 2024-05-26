---
title: Eighth Blog Post
author: "rudifa, an Astro Learner"
description: "Investigating tag patterns."
image:
  url: "https://docs.astro.build/default-og-image.png"
  alt: "The word astro against an illustration of planets and stars."
pubDate: 2022-05-23
tags:
  - astro
  - tags
  - patterns

# tags: ["yaml", "json", "toml"]

tech: ["astro", "vercel"]
tracks:
  - Astro content collections
techno:
  - astro
  - vercel
audience:
  - Dev
---

## Investigate astro tag patterns

### Which formats can we use to define frontmatter properties such as tags?

```
In Markdown files, frontmatter is typically written in YAML, but can also be written in JSON or TOML. Here's how you can define a tags property in each format:

YAML:
---
tags:
  - tag1
  - tag2
  - tag3
---

JSON:

---
"tags": ["tag1", "tag2", "tag3"]
---
TOML:

---
tags = ["tag1", "tag2", "tag3"]
---
In each of these examples, tags is an array of strings.
```
