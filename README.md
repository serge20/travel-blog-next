# travel-blog-next


``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build

```

## Project Structure

專案目錄結構

```bash
├─ api         # 各模組 Api
│  └─ index       # 通用 Api
│
├─ assets      # 樣式等要 build 的東西
│  ├─ antd-custom    
│  └─ style       # 專案樣式
│
├─ components  # 組件
│
├─ Page        # 頁面，會自動生 route
│  ├─ index.js    # 首頁
│  └─ view.js     # 景點詳細頁面
│  └─ _app.js     # 設定redux
│
├─ static       # 靜態檔
│
├─ .babelrc     # babel 設定
│
├─ .routes     # routes 設定
│
├─ next.config.js # next 設定
│
├─ package.json
│
└─ README.md      # 你現在在看的這份文件

```

## 使用next.js 框架 , 實作步驟



``` bash

1.npm i init
2.npn i react react-dom next
3.新增 page 資料夾與新增 index.js / _App.js / viewjs
4.導入 redux redux-saga react-redux next-redux-wrapper next-redux-saga
5.導入ant.desig
6.新增 api 資料夾統一管理 api
6.index.js使用 getInitialProps call Api 
7.新增 components 資料
8.新增 router 資料
8.將 header / footer / card 模組化
9.import header / footer / card 到 index.js 取 store 資料 進行 map
10.將資料傳遞到 card 子組件,整理並渲染
11.利用 next-routes 進行 :id 跳轉
12.git 新增 Repository , push
```
