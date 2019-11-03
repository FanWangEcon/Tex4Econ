# RMD Instructions

## RMD YML Front Matters

### Standard Front-matter

```{yml}
output:
  html_notebook:
    number_sections: yes
  html_document:
    df_print: paged
    number_sections: yes
  pdf_document:
    number_sections: true
urlcolor: blue
```

### Numbered listings

```{yml}
---
title: "Introductory Mathematics for Economists  \nUniversity of Houston, Fall 2019"
output:
  word_document:
    number_sections: true
  html_notebook:
    number_sections: true
  html_document:
    df_print: paged
    number_sections: true
  pdf_document:
    number_sections: true
---
```

### Colored Links

Add blue to url Links, all else default

```{yml}
---
title: "File"
output:
  word_document: default
  html_notebook: default
  html_document: default
  pdf_document: default
  md_document:
    variant: markdown_github  
urlcolor: blue
---

Back to **[Fan](https://fanwangecon.github.io/)**'s R4Econ Homepage **[Table of Content](https://fanwangecon.github.io/R4Econ/)**

# File
```

### Table of Content

Add table of content

```{yml}
title: "Introductory Mathematics for Economists  \nUniversity of Houston, Fall 2019"
output:
  word_document: default
  html_notebook: default
  html_document: default
    toc: true
    toc_depth: 2  
  pdf_document: default
    toc: true
    toc_depth: 2  
urlcolor: blue
```
