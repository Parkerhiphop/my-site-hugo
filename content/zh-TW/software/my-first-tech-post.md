---
title: "用 Hugo 建立靜態網站"
date: 2024-03-02
description: "介紹如何使用 Hugo 搭配 Congo 主題建立個人網站。"
tags: ["Hugo", "靜態網站", "Congo"]
draft: false
---

Hugo 是目前速度最快的靜態網站生成器之一，搭配 Congo 主題可以快速建立一個功能完整的個人網站。

## 為什麼選擇 Hugo

- **速度快**：毫秒級建置時間
- **無依賴**：單一執行檔，不需 Node.js
- **彈性高**：豐富的主題與模板系統

## 安裝步驟

```bash
brew install hugo
hugo new site my-site
cd my-site
git init
git submodule add https://github.com/jpanther/congo themes/congo
```

## 設定 hugo.toml

```toml
baseURL = 'https://example.org/'
title = 'My Site'
theme = 'congo'
defaultContentLanguage = 'zh-TW'
```

## 小結

只需幾分鐘，你就能在本機跑起一個完整的靜態網站，再透過 Cloudflare Pages 免費部署到全球 CDN。
