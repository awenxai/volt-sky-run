# Volt-1 Sky Run 3D

Fly an electric aerocar through a neon dusk city. Three control modes:
Easy (up/down), Medium (4 directions), Hard (8 directions with thrust physics).
Works with keyboard, on-screen buttons, or phone tilt (gyroscope). UI in 中文 / English.

驾驶电动飞行汽车穿越黄昏霓虹城市。三种难度：简单（上下）、中等（4 向）、困难（8 向 + 惯性）。
支持键盘、屏幕按键和手机体感（陀螺仪）操控，界面中英文切换。

## 本地运行 / Run locally

体感需要 https 或 localhost，直接双击打开 index.html 也能玩，但手机体感要通过网址访问。

```bash
npx serve .
```

然后打开 http://localhost:3000

## 发布到 Vercel / Deploy

```bash
npx vercel          # 预览版 / preview
npx vercel --prod   # 正式版 / production
```

或者推送到 GitHub，在 vercel.com 导入仓库。不需要任何构建设置（Framework: Other）。

## 文件 / Files

- `index.html` — 游戏全部代码（画面、音乐、操控）
- `three.min.js` — Three.js r128 3D 引擎（MIT License）
