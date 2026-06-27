# Apology to my dearest mama

童童写给妈妈的互动道歉 / 感恩网页。

**🔗 在线地址：https://liguanruitong.github.io/apology-to-my-dearest-mama/**

## 这是什么

一个纯静态的小网页，从信纸对话开始，按住 `T` 键 3 秒给妈妈一个"抱抱"，
放出烟花，穿过时光机，进入"我们一起走过的时光"相册，最后落款。

陪着的角色：小猪（自称"居"、哼哼），还有两只小黄人贴纸（Bob / DJ），点一下会说话。

## 怎么跑

纯静态，没有构建步骤。本地直接打开 `index.html` 即可，或：

```bash
python3 -m http.server 8080
# 然后浏览器打开 http://localhost:8080
```

## 部署

托管在 GitHub Pages：`main` 分支 / 根目录。push 后约 1–2 分钟自动重建上线。

## 目录

- `index.html` — 全部页面与逻辑
- `img/` — 照片与贴纸
- `fonts/` — 字体
