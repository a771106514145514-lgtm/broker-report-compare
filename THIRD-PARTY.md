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

同樣是單一 HTML 檔，內嵌了：

| 元件 | 用途 | 授權 |
| --- | --- | --- |
| [Leaflet](https://leafletjs.com/) 1.9.4 | 顯示地圖、圖釘與路線 | BSD 2-Clause |

執行時會呼叫以下服務（都不需要金鑰）：

| 服務 | 用途 |
| --- | --- |
| [Overpass API](https://overpass-api.de/) | 查詢某個座標附近的店家 |
| [Nominatim](https://nominatim.openstreetmap.org/) | 地名搜尋與反向地理編碼 |
| [OpenStreetMap 圖磚](https://operations.osmfoundation.org/policies/tiles/) | 地圖底圖 |
| [Valhalla](https://valhalla1.openstreetmap.de/) | 計算步行路線 |
| [Wikimedia Commons](https://commons.wikimedia.org/) | 少數店家在 OSM 上登記的照片 |

以上服務提供的地點與地圖資料皆為 © OpenStreetMap 貢獻者，依
[ODbL](https://www.openstreetmap.org/copyright) 授權。

## Leaflet 授權條款

```
BSD 2-Clause License

Copyright (c) 2010-2023, Volodymyr Agafonkin
Copyright (c) 2010-2011, CloudMade
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
