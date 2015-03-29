---
title: 初始化部落格
date: 2015-03-28 15:08 UTC
tags: GitHub, Middleman
---

### GitHub

- 設定 SSH Keys 可參考 [generate SSH Keys]

- 上傳
    - git config --global user.email "you@example.com"
    - git config --global user.name "Your Name"
    - git remote add origin https://github.com/name/my_blog.git
    - git push -u origin master

### Middleman

- 查看版本
middleman version

- 建立 blog
middleman init my_blog --template=blog --rack

- 在本機觀看
middleman server

- 建立新文章
middleman article "xxx"

- 編譯成靜態網頁
middleman build

- 加入 LiveReload 功能

    - Gemfile 加入 gem "middleman-livereload"

    - Config.rb 加入 activate :livereload

    - 執行 bundle install

### Markdown 語法查詢可參考 [DILLINGER]

### 一個不錯的教學影片: [Quickly Initializing a Static Middleman Website]

[generate SSH Keys]: https://help.github.com/articles/generating-ssh-keys/
[DILLINGER]: http://dillinger.io/
[Quickly Initializing a Static Middleman Website]: https://youtu.be/5aTOxzJLzB4



