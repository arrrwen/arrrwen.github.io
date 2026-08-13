# Personal Thinking Blog

一个参考极简中文博客版式制作的 Astro 博客模板。

## 本地运行

```bash
npm install
npm run dev
```

浏览器打开终端显示的本地地址（通常是 http://localhost:4321）。

## 写新文章

在 `src/content/blog/` 新建 `.md` 文件：

```md
---
title: "文章标题"
date: 2026-08-13
description: "首页显示的摘要"
---

正文……
```

## 修改右侧文案

编辑 `src/layouts/BaseLayout.astro` 中的：

`保持思考 —— 但要行动`

## 修改 GitHub

同一个文件中，把 `https://github.com/` 换成自己的 GitHub 地址。

## 构建

```bash
npm run build
```

构建结果在 `dist/`。
