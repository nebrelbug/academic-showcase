---
title: Differences from Academic Docs
linktitle: Differences from Academic Docs
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
math: true
diagram: true
menu:
  academic-theme:
    parent: Learn
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

## Creating new content
Read the docs [here](https://sourcethemes.com/academic/docs/managing-content/) to read about managing content. Here are a few differences.

Instead of typing
```
hugo new  --kind project project/my-project-name
```
in your terminal, type
```
hugo new  --kind project projects/my-project-name
```

The same applies to: `post/` -> `posts/`, `talk/` -> `talks/`, `project/` -> `projects`