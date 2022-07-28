# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### 功能介紹

在 RWD 模式下，有時候 WEB 跟手機版的背景不同，所以不能對同一張圖直接做 RWD 時，會拆分成兩張圖片，像是在<=768px 模式下是手機，其餘皆是 WEB。

舉例: 在註冊頁面的時候會遇到，手機跟 WEB 模式都共用相同的註冊 form 組件，但背景圖是不同的情況，我們可以把 WEB 看作是一個 A 元件，而手機是 B 元件，至於註冊 form 是一個共同 C 元件，這麼做我們就可以分開進行功能迭代，對 WEB 元件另外設置背景圖，然後再取用共同元件 form 即可。

可參考我引用在的另一個專案
註冊頁面 Side Project:
https://github.com/AnsonLoHK/reactjs-regist-page-mobile-and-web-version
