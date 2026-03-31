# Pretext Demo

一个展示 [Pretext](https://github.com/chenglou/pretext) 高级排版能力的交互式 Demo（[预览](https://github.com/villweb/pretext-demo)）

## 🎯 Demos

| Demo | Description |
|------|-------------|
| 📰 [index.html](./index.html) | Pretext 基础用法 + 性能对比 + 互动输入 |
| 📰 [wrap-demo.html](./wrap-demo.html) | 文字环绕图片排版（单向浮动） |
| 📰 [full-wrap-demo.html](./full-wrap-demo.html) | 文字完全环绕图片（双栏流动） |
| 📰 [advanced-demo.html](./advanced-demo.html) | 高级排版（杂志双栏 + 聊天气泡收缩 + 多形状环绕） |

## ✨ 核心算法（学习自官方源码）

- `carveTextLineSlots()` - 区间切割
- `circleIntervalForBand()` - 圆形碰撞检测
- 二分搜索收缩包裹
- `layoutNextLine()` - 逐行路由
- `walkLineRanges()` - 行宽遍历

## 📦 参考源码

- 官方仓库: [chenglou/pretext](https://github.com/chenglou/pretext)
- 核心文件: `dynamic-layout.ts`, `editorial-engine.ts`, `wrap-geometry.ts`, `bubbles-shared.ts`

## 📄 在线预览

- 打开 [index.html](./index.html) 即可运行
- 或访问 [chenglou.me/pretext](https://chenglou.me/pretext/)

## License
MIT
