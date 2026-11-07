# Rijksakademie A55

A phone-friendly viewer for a 3D Gaussian Splatting scan of studio A55 at the Rijksakademie. Captured with an XGRIDS PortalCam on 2026-11-07 and reconstructed in LCC Studio.

Live: https://evan01624.github.io/rijks-studio-scan/

- Three quality levels: Smooth (about 215K splats, phone default), Standard (about 430K) and High (about 860K, desktop default).
- Controls: drag to look around, zoom and pan; drag the mini map to move through the room; the auto tour circles the room centre.
- `splat/*/partNN.wasm` files are chunks in `.splat` format (32 bytes per Gaussian). The extension is left over from an earlier host's file-type limits.

Libraries: [three.js](https://github.com/mrdoob/three.js) (MIT), [GaussianSplats3D](https://github.com/mkkellogg/GaussianSplats3D) (MIT).
