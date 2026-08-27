# 內含的第三方元件

這個工具是單一 HTML 檔，以下元件已內嵌其中：

| 元件 | 用途 | 授權 |
| --- | --- | --- |
| [pdf.js](https://github.com/mozilla/pdf.js) 3.11.174 | 解析 PDF、取出文字與座標 | Apache License 2.0 |
| [tesseract.js](https://github.com/naptha/tesseract.js) 5.1.1 | 掃描檔文字辨識（瀏覽器端） | Apache License 2.0 |
| [tesseract.js-core](https://github.com/naptha/tesseract.js-core) 5.1.1 | 上者的 WebAssembly 核心 | Apache License 2.0 |
| [tessdata_fast `chi_tra`](https://github.com/tesseract-ocr/tessdata_fast) | 繁體中文辨識語料 | Apache License 2.0 |

各元件的完整授權條款請見其原始專案。

# 附近好吃好買（travel.html）

這一支沒有內嵌任何第三方程式碼，但執行時會呼叫以下服務：

| 服務 | 用途 |
| --- | --- |
| [Overpass API](https://overpass-api.de/) | 查詢某個座標附近的店家 |
| [Nominatim](https://nominatim.openstreetmap.org/) | 地名搜尋與反向地理編碼 |

兩者提供的地點資料皆為 © OpenStreetMap 貢獻者，依
[ODbL](https://www.openstreetmap.org/copyright) 授權。
