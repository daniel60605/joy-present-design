# 樂呈設計 Joy Present

品牌形象網站：炭黑、香檳金、銀白雙弧，以原始 Logo 延伸光影與空間構圖。
地址：台北市信義區松隆路3-2號。

## 開啟與部署

直接開啟 index.html 即可使用靜態網站；也可將本資料夾的 index.html、style.css、script.js 與完整 assets/ 上傳到靜態網站服務。WebGPU 模組需要 HTTPS 或 localhost，無支援時保留 CSS 雙弧光影；減少動態偏好會停用動畫。

開發建置：Node.js 環境執行 npm ci、npm run build。已附編譯完成的 assets/shader-effects.js，瀏覽網站無需安裝套件。

## 內容與素材

- assets/joy-present-logo.jpg：使用者提供的原始品牌標誌。
- assets/interior.jpg、commercial.jpg、dental.jpg：沿用既有專案的空間參考照片。頁面均註明為氛圍參考，非公司實績；原始攝影來源未附於接續資料，正式更換素材時應保留攝影授權與來源紀錄。
- 外部字型：Google Fonts 的 Noto Serif TC、Noto Sans TC、Cormorant Garamond；離線時使用本機襯線／無襯線字型。
- Shaders 套件採 MIT 授權，第三方授權見 THIRD-PARTY-LICENSES.txt；已停用套件遙測。
- 指南連結為官方來源，僅供前期評估，非個案法規或施工審查結論。

## 需求筆記

表單只在瀏覽器產生摘要，可複製，不會提交、寄信或儲存。若要啟用真正收件，需另接公司確認的聯絡信箱或接收服務。本版不捏造電話、信箱、案例、資歷。

## 互動與無障礙

手機選單支援 Escape；頁籤支援左右方向鍵、Home、End；指南採原生 details；表單有原生必填與信箱驗證；支援鍵盤焦點及 prefers-reduced-motion。
