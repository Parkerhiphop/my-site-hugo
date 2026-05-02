---
title: "個人網站"
date: 2024-03-03
description: "用 Hugo + Congo 主題建立的多語系個人網站，部署於 Cloudflare Pages。"
tags: ["Hugo", "Cloudflare", "多語系"]
draft: false
project: true
---

這個網站本身就是一個作品。以下是技術選型與功能概覽。

## 技術棧

| 項目 | 選擇 |
|---|---|
| 靜態生成器 | Hugo 0.161 |
| 主題 | Congo v2 |
| CMS | Decap CMS |
| 留言 | Cusdis |
| 部署 | Cloudflare Pages |

## 功能

- **多語系**：繁體中文（預設）、英文、日文
- **深色模式**：跟隨系統自動切換
- **目錄**：長文章自動產生 TOC
- **留言**：Cusdis 輕量留言系統，深色模式同步
- **訂閱**：文章頁底嵌入 Substack 訂閱框
- **CMS**：Decap CMS 提供視覺化編輯介面

## 原始碼

原始碼存放於 GitHub，透過 Cloudflare Pages 自動部署。推送至 `main` 觸發正式環境建置；其他分支觸發預覽環境建置。
