---
title: "用 Hugo + GitHub Pages 搭建个人网站"
date: 2026-05-17
draft: false
description: "把这次建站过程沉淀成一篇可复用的笔记"
tags: ["Hugo", "GitHub Pages"]
categories: ["知识库"]
ShowToc: true
---

## 问题

如何低成本搭建一个长期可维护的个人品牌网站？

## 结论

Hugo + PaperMod + GitHub Pages + GitHub Actions 是一条非常稳的路。

## 易错点

- baseURL 配错
- draft 没改为 false
- Hugo 不是 Extended 版
- Workflow 没拉 submodule