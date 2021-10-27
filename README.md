# md2pdf

This [script](./md2pdf) will let you generate a pdf from a markdown file.

## Usage

```bash
md2pdf README.md
```

## Dependencies

1. `pandoc`
2. `texlive` (`texlive-most` in arch)
3. [eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) template

## Tips

Add the following to the top of you markdown file before running the script to annotate the pdf with metadata.
```
---
title: "The Document Title"
author: [Example Author, Another Author]
date: "2017-02-20"
keywords: [Markdown, Example]
...
```
