# 欢乐拍泡泡

一个面向儿童的大屏体感拍泡泡网页游戏。支持单人挑战和双人 PK，通过浏览器摄像头和 MediaPipe Hands 在本地识别手部动作。

## 在线运行

GitHub Pages 地址通常为：

https://0612Leo.github.io/happy-bubble-pop/

首次部署可能需要等待 1-3 分钟。

## 本地运行

```bash
npm install
npm run dev
```

然后打开终端显示的本地地址，例如 `http://127.0.0.1:5173/`。

## MAXHUB 安卓会议平板使用

1. 在 MAXHUB 浏览器中打开 GitHub Pages 地址。
2. 允许浏览器使用摄像头。
3. 选择“单人”或“双人 PK”。
4. 如果体感模块加载失败，确认 MAXHUB 可以访问 jsDelivr / Google Fonts / Tailwind CDN。

## 隐私说明

摄像头画面只在本地浏览器中用于实时手势识别，不上传、不保存。
