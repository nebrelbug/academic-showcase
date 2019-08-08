---
title: Markdown
linktitle: Markdown
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
math: true
diagram: true
menu:
  academic-theme:
    parent: Examples
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

## Footnotes
[Learn how](https://sourcethemes.com/academic/docs/writing-markdown-latex/#footnotes)

According to Jessica Fridrich[^1], one should focus first on solving a cube in a minimum number of moves.

[^1]: Inventor of the Fridrich speedcubing method

## Diagrams
[Learn how](https://sourcethemes.com/academic/docs/writing-markdown-latex/#diagrams)

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```

## Code Highlighting
[Learn how](https://sourcethemes.com/academic/docs/writing-markdown-latex/#code-highlighting)

```r
# about understanding everything the code does. Just enjoy!

data()          # browse pre-loaded data sets
data(rivers)    # get this one: "Lengths of Major North American Rivers"
ls()            # notice that "rivers" now appears in the workspace
head(rivers)    # peek at the data set
# 735 320 325 392 524 450

length(rivers)  # how many rivers were measured?
# 141
summary(rivers) # what are some summary statistics?
#   Min. 1st Qu.  Median    Mean 3rd Qu.    Max.
#  135.0   310.0   425.0   591.2   680.0  3710.0

# make a stem-and-leaf plot (a histogram-like data visualization)
stem(rivers)
```


## LaTeX Equations
[Learn how](https://sourcethemes.com/academic/docs/writing-markdown-latex/#rm-latex-math)

$$\gamma\_{n} = \frac{ 
\left | \left (\mathbf x\_{n} - \mathbf x\_{n-1} \right )^T 
\left [\nabla F (\mathbf x\_{n}) - \nabla F (\mathbf x\_{n-1}) \right ] \right |}
{\left \|\nabla F(\mathbf{x}\_{n}) - \nabla F(\mathbf{x}\_{n-1}) \right \|^2}$$
