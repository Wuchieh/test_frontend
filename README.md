# 測試內容

請先將此專案 fork 到自己的 GitHub 上，再進行修改。

baseUrl 將由面試官提供。

文檔網址為 ${baseUrl}/swagger/index.html。

## 測試內容

1. 完成 `BFormControls.vue` 輸入組件的封裝。 (封裝組件)
2. 用戶資料只有在首次進入畫面時可以去請求。 (節流)
3. 其餘請依照 `App.vue` 的要求完成。

## BFormControls.vue 要求

1. 能使用 v-model 做雙向綁定 (使用 vue3.4 以下方法可加分)
2. id: 不可重複，但允許用戶自行設置
3. type: 類型string, 預設為text
4. placeholder: 類型string
5. label: 類型string
6. 點擊label後，需聚焦到input標籤，不可使用js處理
7. 外部可以使用 GetData 方法取得資料

## 注意事項

1. 只允許使用 `Composition API` 寫法
2. 請使用 `typescript` 寫法

## 額外內容

1. 自行封裝確認框組件
2. 請將您的專案透過自動化構建方式部屬，如(cloudflare pages、github pages、netlify、vercel 等)

## 其他

範本: [https://exam.wuchieh.tk/](https://exam.wuchieh.tk/)
