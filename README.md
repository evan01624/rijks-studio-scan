# Rijks 工作室掃描

用手機或電腦瀏覽工作室的 3D Gaussian Splatting 掃描。掃描以 XGRIDS PortalCam 拍攝，由 LCC Studio 建模。

線上網址：https://evan01624.github.io/rijks-studio-scan/

- 三種畫質：輕量約 29 萬顆（手機預設）、標準約 57 萬顆、完整約 111 萬顆（電腦預設）。
- 操作：拖曳環顧、縮放、平移；可拖曳右上角小地圖移動位置；自動導覽會繞房間中心走一圈。
- `splat/*/partNN.wasm` 其實是 `.splat` 格式的分塊（每顆高斯 32 位元組），副檔名沿用自原本的託管限制。

使用的函式庫：[three.js](https://github.com/mrdoob/three.js)（MIT）、[GaussianSplats3D](https://github.com/mkkellogg/GaussianSplats3D)（MIT）。
