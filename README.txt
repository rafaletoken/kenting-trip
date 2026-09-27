# 墾丁之旅 PWA

這是「五甲→墾丁 福安宮之旅」HTML 行程的 iPhone PWA 版本。

## 安裝到 iPhone 主畫面
1. 把整個資料夾放到支援 HTTPS 的網站空間。
2. 用 iPhone 的 Safari 開啟 `index.html` 所在的網站。
3. 點 Safari 的「分享」。
4. 選「加入主畫面」。
5. 加入後會以獨立 App 形式開啟。

注意：不能直接從 iPhone「檔案」App 開啟 HTML 後就取得完整 PWA 安裝效果；PWA 需要 HTTPS 網站環境。

## 內容
- index.html：App 主程式
- manifest.json：iPhone/PWA 安裝資訊
- sw.js：離線快取
- icons/：App 圖示
