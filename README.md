# 楊浩旻 Neal Yang - 個人作品集網站

這是一個純前端的一頁式個人網站，使用 HTML、CSS 和 TypeScript 開發。

## 專案設置

### 安裝依賴

首先確保您已安裝 yarn。如果尚未安裝，請先安裝 yarn：

```bash
npm install -g yarn
```

然後安裝專案依賴：

```bash
yarn install
```

### 編譯 TypeScript

編譯 TypeScript 文件：

```bash
yarn build
```

或者使用監聽模式（自動編譯）：

```bash
yarn watch
```

### 開啟網站

直接在瀏覽器中打開 `index.html` 文件，或使用本地伺服器：

```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx http-server
```

然後在瀏覽器中訪問 `http://localhost:8000`

## 專案結構

```
MyOwnWeb/
├── index.html          # 主 HTML 文件
├── styles.css          # 樣式文件
├── src/
│   └── main.ts         # TypeScript 源文件
├── dist/
│   └── main.js         # 編譯後的 JavaScript 文件
├── package.json        # 專案配置
├── tsconfig.json       # TypeScript 配置
└── README.md           # 本文件
```

## 待完成事項

1. **上傳個人照片**：請將您的照片上傳並替換 `index.html` 中的 `profile-image-placeholder` 部分
2. **更新 Facebook 連結**：請在 `index.html` 中更新 Facebook 連結為您的實際 Facebook 個人檔案連結

## 功能說明

- 一頁式設計，包含首頁、Resume、Projects、Contact 四大區段
- 平滑滾動導航
- 響應式設計，支援各種螢幕尺寸
- 使用 TypeScript 處理動態交互
