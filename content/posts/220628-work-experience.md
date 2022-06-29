---
title: Work Experience
date: 2022-06-28T00:18:14+01:00
lastmod: 2022-06-28T00:18:14+01:00
author: Darthagnon
avatar: /img/authors/Darthagnon.jpg
authorlink: https://robot-one.github.io
#cover: /img/cover.jpg
# images:
#   - /img/cover.jpg
categories:
  - Events and Seasons
tags:
  - Work
  - todo
# nolastmod: true
draft: false
---

Today, I'm starting a work experience placement with the British Civil Service. This page is a temporary demo scratchpad to show off some ideas.

<!--more-->

While I'm working on service embedding for static websites (in the project [Darth's Hugo Shortcodes](https://github.com/Darthagnon/darths-hugo-shortcodes); see [here for the release thread on the GoHugo forums](https://discourse.gohugo.io/t/release-darths-hugo-shortcodes/38943)), here's some features I believe may be helpful to the department:

## Google Docs/Sheets/Slides/Drive/Forms embedding
Allows for easy document editing and public/semi-public sharing. Downside: initial setup requires a little technical expertise.

### Google Docs
To embed a document, I use the following code:
```
{{</* google doctype="docs" publishcode="2PACX-1vRtcK1TuBM3W_iI_z3mKvNS5Jza1d5eFjVOjZCwsYKl_FbCSdxTI5gjw4E3oWJEF4rCGbEZBtRT8eKS" size="large" url="https://docs.google.com/document/d/1Wl3fQdF85Br01t7gvVsQ4F_clw6LoOCF9kG4fJTpRW8/edit?usp=sharing" */>}}
```
The below document is publicly editable; click on the little blue Google Docs icon to open the editing page. I will eventually disable/delete this, to avoid vandalisation.
{{< google doctype="docs" publishcode="2PACX-1vRtcK1TuBM3W_iI_z3mKvNS5Jza1d5eFjVOjZCwsYKl_FbCSdxTI5gjw4E3oWJEF4rCGbEZBtRT8eKS" size="large" url="https://docs.google.com/document/d/1Wl3fQdF85Br01t7gvVsQ4F_clw6LoOCF9kG4fJTpRW8/edit?usp=sharing" >}}

### Google Forms
Similar code is used to embed a feedback form:

```
{{</* google doctype="docs" publishcode="2PACX-1vRtcK1TuBM3W_iI_z3mKvNS5Jza1d5eFjVOjZCwsYKl_FbCSdxTI5gjw4E3oWJEF4rCGbEZBtRT8eKS" size="large" url="https://docs.google.com/document/d/1Wl3fQdF85Br01t7gvVsQ4F_clw6LoOCF9kG4fJTpRW8/edit?usp=sharing" */>}}
```
**Please do not enter any confidential information or real contact details** (you can reach me from the About page, above); **the below form is a public demo!!!** 
{{< google doctype="forms" publishcode="1FAIpQLSc0lXEcWF2Di7_bPpoq3aF3CvzGQhH5p8RDSed_LYok-mMyyQ" size="large" url="https://docs.google.com/forms/d/1_LZVpM5MYinCAlF4ep0h75Kj0z0bLGZDVWASFEFR6VY/edit" >}}

## Further work
As this is a working document, more examples to come later; slideshows and spreadsheets (e.g. the results of a feedback form) can also be displayed. I am also actively working on bringing over the same features from Microsoft OneDrive and SharePoint.
