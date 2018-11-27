## Vue 專案建立
---
### 設置package.json
#### 相依套件
- css-loader
- vue
- vue-loader
- vue-template-compiler
#### 開發環境套件
- webpack
- webpack-cli
#### 執行命令
``"build": "webpack --mode development"``
### 設置webpack.config.json
- 設置進入點(index.js)、輸出路徑(dist/build.js)
- 設置module
- 設置plugin
### 設置index.js
index.js做為vue app的進入腳本，在index.js中加載vue元件。
### 執行
``npm run build``產生build.js檔案