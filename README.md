# 报位置 · Hermes

手机打开网页 → 授权定位 → 把坐标分享/复制发给 Hermes 的 QQ/微信。

纯前端，无后端，不存任何数据。需 HTTPS（GitHub Pages 免费提供）。

- 定位：浏览器 Geolocation API（enableHighAccuracy）
- 分享：navigator.share 调起系统分享
- 复制：Clipboard API
- 地址反查：Nominatim/OSM（失败时坐标仍然可用）