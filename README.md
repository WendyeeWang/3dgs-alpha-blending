# 3D Gaussian Splatting - Alpha Blending 原理演示

交互式演示 3D Gaussian Splatting 中 Front-to-Back Alpha Blending 的工作原理。

## 🎬 在线演示

👉 **[点击查看演示](https://ningzeliu.github.io/3dgs-alpha-blending/)**

或扫描下方二维码：

![QR Code](qrcode-github.png)

## 📖 内容介绍

本演示详细解释了 3D Gaussian Splatting 渲染中的 Alpha Blending 步骤：

1. **什么是 3DGS** - 高斯分布表示场景的核心概念
2. **深度排序** - Front-to-Back 策略的原理
3. **核心公式** - Volume Rendering 离散化公式详解
4. **逐步混合** - G₁(蓝) → G₂(绿) → G₃(红) 的计算过程
5. **背景合成** - 最终颜色计算
6. **总结** - 为什么 Front-to-Back 优于 Back-to-Front

## 🎮 操作说明

- **←/→ 键**: 上一步/下一步
- **空格键**: 自动播放/暂停
- **点击圆点**: 跳转到指定步骤

## 🚀 本地运行

直接用浏览器打开 `index.html` 即可，无需任何服务器或依赖。

## 📚 参考文献

- [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)
- Kerbl, B., Kopanas, G., Leimkühler, T., & Drettakis, G. (2023). 3D Gaussian Splatting for Real-Time Radiance Field Rendering. ACM Transactions on Graphics.

## 📄 License

MIT License
