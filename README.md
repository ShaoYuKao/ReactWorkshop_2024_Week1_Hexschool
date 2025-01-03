# 第一週 - 從函式拆解認識設計模式

> 2024 React 作品實戰冬季班 - hexschool

本專案支援 Node.js 執行環境，必須要安裝 **v16.0.0 LTS** 以上版本。

此模板提供了一個最小的設置，以便在 Vite 中使用 React，並支持 HMR 和一些 ESLint 規則。

目前，有兩個官方插件可用：

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) 使用 [Babel](https://babeljs.io/) 進行快速刷新
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) 使用 [SWC](https://swc.rs/) 進行快速刷新

### 完成條件

- 請透過 Codepen 或 GitHub Pages 提交作業，以方便助教與講師檢視
- 須自行撰寫 React，若有參考同學作業，請附上參考來源
- 請勿將提問的問題寫在程式碼中
- 回報時務必要附上 Discord 名稱、作業等級 .. 等完整繳交內容
- GitHub Pages 需正常開啟
- 需至少完成 Lv1 作業等級
- 以上需符合規定，否則會審核失敗

### 此任務你會獲得以下技能

- 關注點分離
- 設計模式
- React 初始化

## 指令列表

- `npm install` - 初次下載該專案後，需要使用 `npm install` 來安裝套件
- `npm run dev` - 啟動開發伺服器
  - 若沒有自動開啟瀏覽器，可嘗試手動在瀏覽器上輸入 `http://localhost:5173/ReactWorkshop_2024_Week1_Hexschool/`
- `npm run build` - 打包專案
- `npm run preview` - 預覽打包後的專案
- `npm run deploy` - 進行自動化部署

## 資料夾結構

當前專案的資料夾及檔案結構如下：

```
|   .copilot-commit-message-instructions.md
|   .gitignore
|   eslint.config.js
|   index.html
|   package-lock.json
|   package.json
|   README.md
|   vite.config.js
|   
+---public
|       vite.svg
|       
\---src
    |   App.css
    |   App.jsx
    |   index.css
    |   main.jsx
    |   
    \---assets
            react.svg
```

**根目錄**

- `.copilot-commit-message-instructions.md`：提供有關提交訊息的規範說明。
- `.gitignore`：列出應該被 Git 忽略的檔案和目錄。
- `eslint.config.js`：ESLint 的配置檔案，用於設定代碼檢查規則。
- `index.html`：專案的主 HTML 檔案，包含應用的根元素。
- `package-lock.json`：鎖定專案依賴版本的檔案。
- `package.json`：專案的配置檔案，包含專案名稱、版本、依賴和腳本等資訊。
- `README.md`：專案的說明文件，包含專案介紹、指令列表和資料夾結構等資訊。
- `vite.config.js`：Vite 的配置檔案，用於設定開發伺服器和打包選項。

**`public/` 資料夾**

- `vite.svg`：Vite 的標誌檔案。

**`src/` 資料夾**

- `App.css`：主要的樣式檔案，包含應用的樣式定義。
- `App.jsx`：主要的 React 元件，負責渲染應用的主要內容。
- `index.css`：全局樣式檔案，包含應用的基本樣式定義。
- `main.jsx`：入口文件，負責渲染 `App` 元件。

**`assets/` 資料夾**

- `react.svg`：React 的標誌檔案。

## 主線任務說明

完成以下兩份作業：

1\. 使用此 [[頁面模板與資料格式](https://codepen.io/hexschool/pen/jENwNZO)] 完成下方功能：

- 使用者可以查看產品列表
- 使用者可以點擊單一產品，查看詳細資訊

2\. 觀看 [課程影音 - 關注點分離](https://courses.hexschool.com/courses/react-video-course1/lectures/58000034) 並練習 kata

作業須符合此[作業規範](https://hackmd.io/XbKPYiE9Ru6G0sAfB5PBJw)

## **繳交內容**

1. 您的 Discord 使用者名稱
2. 您的作業等級，請見下方等級表，例如 LV1
3. 作業網址：請提供 CodePen 或 GitHub Pages 連結，以方便助教與講師檢視
4. 回報「是否有觀看預習影片？」

#### 作業地雷

- GitHub Pages 需正常開啟
- 提問超過 2 個問題批改時間會延長

每週主線任務範例：<https://github.com/hexschool/react-training-chapter-2024>

### 挑戰等級

- LV 1｜參考程式碼範例，並重新撰寫及補上註解
- LV 2｜僅使用課程版型，並重新撰寫產品列表的功能
- LV 3｜不使用課程版型完成此功能
