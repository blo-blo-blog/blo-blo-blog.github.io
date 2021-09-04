---
title: "[遊戲] Bashcrawl介紹"
date: 2021-09-04T09:16:15+08:00
draft: false
categories: ["遊戲"]
tags: ["Bashcrawl","Bash"]
weight: 0
---

### 簡介

這是一個純文字的地牢遊戲，他的呈現方式非常有趣，是用目錄和文件來代表房間和提示，遊玩的方式是用Bash的指令，很適合Bash的初學者玩，在遊戲的過程中，還可以學習到不同的指令使用方式。

### 安裝

在開始之前，我們的電腦之中必須有Bash或[Zsh](https://opensource.com/article/19/9/getting-started-zsh)。Linux, BSD和MacOS這些作業系統預設都包含Bash。Windows的使用者可以先安裝[Cygwin](https://www.cygwin.com/)或[WSL](https://docs.microsoft.com/en-us/windows/wsl/wsl2-about)，也可以嘗試使用Linux。

到[官網](https://gitlab.com/slackermedia/bashcrawl/-/tree/master/)或是點擊[這裡](https://gitlab.com/slackermedia/bashcrawl/-/archive/master/bashcrawl-master.zip)下載並且解壓縮。

### 開始遊戲

首先，用終端機開啟bashcrawl的目錄，輸入指令`ls`，會出現當前目錄下的檔案：

```
blobloblog@mylaptop:~/Downloads/bashcrawl-master$ ls
entrance  LICENSE  README.md
```

有一檔案寫著`README.md`，使用指令`cat`將他所有的內容輸出在終端機中：

```
cat README.md
```

或是使用`less`，可以用方向鍵瀏覽文件內容，按下`q`離開：

```
less README.md
```

仔細閱讀`README.md`，然後使用以下指令開始遊戲：

```
cd entrance/
```

祝大家玩的愉快 ଘ(੭ˊᵕˋ)੭* ੈ✩

#### 參考文件
[https://marlborough-college.gitbook.io/attic-lab/the-terminal/games/level-1-bashcrawl](https://marlborough-college.gitbook.io/attic-lab/the-terminal/games/level-1-bashcrawl)