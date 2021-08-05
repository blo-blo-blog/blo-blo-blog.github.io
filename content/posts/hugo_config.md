---
title: "設定檔config.yml基本設定"
date: 2021-08-05T10:39:24+08:00
draft: true
categories: ["個人網站"]
tags: ["Hugo"]
weight: 0
---

### 



```
baseURL: "https://kkkeevvvin.github.io"
title: "kkkeevvvin"
theme: PaperMod

languageCode: zh-hant
defaultContentLanguage: zh-hant

publishdir: "../kkkeevvvin.github.io"
enableInlineShortcodes: true
enableRobotsTXT: true

languages:
    zh-hant:
        languageName: "繁中"
        weight: 0
        menu:
            main:
                - name: "文章列表"
                  url: archives
                  weight: 5
                - name: "搜尋"
                  url: search
                  weight: 15
                - name: "標籤"
                  url: tags/
                  weight: 10
                - name: "分類"
                  url: categories/
                  weight: 10

outputs:
    home:
        - HTML
        - RSS
        - JSON

params:
    author: kkkeevvvin

    defaultTheme: dark
    # disableThemeToggle: true
    ShowShareButtons: true
    ShowReadingTime: true
    # disableSpecial1stPost: true
    displayFullLangName: true
    ShowPostNavLinks: true
    ShowBreadCrumbs: true
    ShowCodeCopyButtons: true
    ShowToc: true
    # comments: false
    images: ["papermod-cover.png"]

    homeInfoParams:
        Title: "kkkeevvvin"
        Content: >
            嗨！
    socialIcons:
        - name: github
          url: "https://github.com/kkkeevvvin/kkkeevvvin.github.io"
        - name: instagram
          url: "https://www.instagram.com/kkkeevvvin/"

taxonomies:
    category: categories
    tag: tags

markup:
    goldmark:
        renderer:
            unsafe: true
```





https://gohugo.io/templates/output-formats#default-output-formats
