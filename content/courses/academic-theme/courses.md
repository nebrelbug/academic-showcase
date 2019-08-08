---
title: Courses
linktitle: Configuring Courses
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  academic-theme:
    parent: Learn
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

## Flexibility

This feature can be used for publishing content such as:

* **Online courses**
* **Project or software documentation**
* **Tutorials**

The `courses` folder may be renamed. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form
```yaml
menu:
  X:
    parent: optional
    weight: 1
```
Where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `example:` to `<NewFolderName>:`.
