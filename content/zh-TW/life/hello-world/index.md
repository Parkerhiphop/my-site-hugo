---
title: "你好，世界"
date: 2024-03-01
description: "第一篇文章，測試封面照片、內文圖片、圖說與替代文字。"
tags: ["測試", "第一篇"]
draft: false
cover: "cover.png"
coverAlt: "一張柔和青綠色的寬幅色塊圖，作為封面示意"
coverCaption: "封面說明：這是 cover.png，透過 front matter 的 `cover` 欄位設定，`coverAlt` 設定替代文字，`coverCaption` 設定說明文字。"
---

歡迎來到我的網站！這篇文章用來測試圖片功能，包含封面照片、內文圖片、圖說（caption）與替代文字（alt text）。

## 封面照片設定方式

在 front matter 設定以下欄位：

```yaml
cover: "cover.png"          # 圖片檔名（與 index.md 同目錄）
coverAlt: "替代文字"         # 給螢幕閱讀器與搜尋引擎
coverCaption: "顯示在圖片下方的說明文字"
```

Hugo 的 page bundle 讓圖片與文章存放在同一個資料夾，Congo 主題會自動抓取。

## 內文圖片

使用 Congo 的 `figure` shortcode，可以同時設定 `alt`（替代文字）與 `caption`（圖說）：

{{< figure src="sample.png" alt="一張溫暖琥珀色的色塊圖，作為內文圖片示意" caption="內文說明：這是 sample.png，透過 `figure` shortcode 嵌入。`alt` 設定替代文字，`caption` 設定顯示在圖片下方的說明文字，支援 **Markdown** 語法。" >}}

## 第一節

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.

## 第二節

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.

### 子節

Sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.

## 第三節

Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
