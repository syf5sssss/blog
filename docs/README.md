---
home: true
title: 主页
# heroImage: https://vuejs.press/images/hero.png
actions:
  - text: Get Started
    link: /get-started.html
    type: primary

  - text: Introduction
    link: https://vuejs.press/guide/introduction.html
    type: secondary

features:
  - title: Simplicity First
    details: Minimal setup with markdown-centered project structure helps you focus on writing.
  - title: Vue-Powered
    details: Enjoy the dev experience of Vue, use Vue components in markdown, and develop custom themes with Vue.
  - title: Performant
    details: VuePress generates pre-rendered static HTML for each page, and runs as an SPA once a page is loaded.
  - title: Themes
    details: Providing a default theme out of the box. You can also choose a community theme or create your own one.
  - title: Plugins
    details: Flexible plugin API, allowing plugins to provide lots of plug-and-play features for your site.
  - title: Bundlers
    details: Default bundler is Vite, while Webpack is also supported. Choose the one you like!

footer: MIT Licensed | Copyright © 2018-present VuePress Community
---

This is the content of home page. Check [Home Page Docs][default-theme-home] for more details.

[default-theme-home]: https://vuejs.press/reference/default-theme/frontmatter.html#home-page


npm run docs:dev

npm run docs:build

pages的设置需要选择gh-pages分支的docs

部署的时候需要将打包到dist的文件上传到gh-pages目录的docs目录下

本地测试需要将dist的文件复制到blog目录下，http-server启动即可，如有文件加载问题，清空浏览器缓存即可。

dist->gh-pages/docs