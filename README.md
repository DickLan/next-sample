
#### README.md

常見的專案架構說明
pages
功能: 存放 Next.js 的頁面文件，每個文件對應一個路由。
範例:
index.tsx: 主頁面，包含用戶名的 API 請求和顯示。
display/index.tsx: 一個顯示頁面，用於路由測試。

pages/api
功能: 存放 Next.js 的 API 路由處理器，用於處理後端請求。
範例:
test.ts: 處理 /api/test 路由，從另一個 API 獲取數據並返回。

styles
功能: 包含 CSS 樣式文件，用於定義全局和模組化 CSS。
範例:
globals.css: 定義全局樣式。
Home.module.css: 為首頁定義模組化樣式。

public
功能: 存放靜態文件，如圖片和 favicon。
範例:
圖片文件和 favicon.ico。

src
功能: 可以用來組織更大的專案，存放 JavaScript 和 TypeScript 文件。
範例:
目前沒有特定的 src 資料夾結構示例，但通常包括組件、工具函數等。




```markdown:README.md
# Next.js Example Project

## Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

