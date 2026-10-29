# 東京收藏地圖

Google 地圖收藏的東京地點，依地區與類型整理的一頁式地圖。

- 地點資料：Google 地圖匯出（2026-10-29），簡介與評分依當日的 Google 地圖頁
- 底圖：国土地理院（地理院タイル・淡色地図），去除文字後重新上色
- 鐵路線與車站：© OpenStreetMap contributors（ODbL）
- 地標外觀照片：Wikimedia Commons，各張作者與授權標在照片下方（CC BY／CC BY-SA 等自由授權）
- 運行情報：公共交通オープンデータセンター（ODPT），都營交通運行情報（CC BY 4.0），瀏覽器端即時讀取

產生方式在私人 repo 的 `travel/tokyo-map/`（classify.py → basemap.py → rail.py → build.py --web；底圖圖磚由 tiles.py 產生到 `tiles/`）。
