
---
# layout: ../../layouts/MarkdownPostLayout.astro
title: '[Vim]Edit a macro'
pubDate: 2025-02-11
description: 'Vim practice'
author: 'Noritaka'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'Astroのロゴ。'
tags: ["Vim",]
---


```
Edit a macro
Copy and paste the below text and type some commands like below.

---
/tip 7 1 1 <CR> (Serch tip711)
qq yyp q u 　   (Record yyp into register q)
:put q <CR>　   (Paste registered command yyp )
A p <Esc>　　   (Edit the command)
V "qy uu        (Rerecord the edited command into register q  )
@q              (Run command register q)
---
tip711
```
