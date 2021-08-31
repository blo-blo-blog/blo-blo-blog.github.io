---
title: "config.yml基本設定"
date: 2021-08-05T10:39:24+08:00
draft: true
categories: ["個人網站"]
tags: ["Hugo"]
weight: 0
---

### 前言

`config.yml`中可以設定網頁的部份配置。

可以先把範例設定貼到你的`config.yml`中，然後填寫尖括弧中的內容，後面會再進行詳細的說明。

### 範例設定

```

baseURL: "https://<USERNAME>.github.io/<your_repo>"
title: "<your title>"
theme: PaperMod
languageCode: utf-8
defaultContentLanguage: zh-hant
publishdir: "<your dir>"

enableInlineShortcodes: true
enableRobotsTXT: true

outputs:
    home:
        - HTML
        - RSS
        - JSON
        
markup:
    goldmark:
        renderer:
            unsafe: true

languages:
    zh-hant:
        languageName: "繁中"
        weight: 0
        menu:
            main:
                - name: "文章列表"
                  url: archives
                  weight: 1
                - name: "分類"
                  url: categories/
                  weight: 2
                - name: "標籤"
                  url: tags/
                  weight: 3
                - name: "搜尋"
                  url: search
                  weight: 4

params:
    author: <YOUR NAME>

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
    
    homeInfoParams:
        Title: "<your title>"
        Content: >
        	<your multi-line content>x
    socialIcons:
        - name: github
          url: "<your github url<"
        - name: instagram
          url: "<your instagram url>"

taxonomies:
    category: categories
    tag: tags
    
```









https://gohugo.io/templates/output-formats#default-output-formats
