# vamosmobility
repo for pages used to build the [Vamos Mobility website](https://vamosmobility.com).

Pages should be written in [Markdown](https://guides.github.com/features/mastering-markdown/), and will be rendered into HTML by the [Jekyll](https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages) static site generator framework. You don't need to worry about headers/footers and so forth--all of that is automatically added. Just concentrate on writing the page content. 

Every page that you want to be on the site should start with a header that looks like this:

```
---
title: Welcome to Vamos Mobility [insert the real title here]
layout: default [keep this exactly as-is]
---

# {{ page.title }} [keep this exactly as-is]
[It will automatically populate with the title supplied in the header when the page renders]

The rest of the page contents go here. 

Take a look at the code of some of the other pages in the repo for examples. 

```
