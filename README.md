# Erika 的猫箱

Hexo 8 + [hexo-theme-matery](https://github.com/blinkfox/hexo-theme-matery) 搭建的个人博客，
站点源码在 `catbox/`（生成产物在 `public/`，已 gitignore；仓库根仅此目录与说明文件）。

## 本地运行

```bash
cd catbox
npm install          # 首次
npx hexo server -p 4000   # http://127.0.0.1:4000/
```

## 图标

`themes/hexo-theme-matery/source/` 下的 `favicon.png`、`favicon.ico`、`apple-touch-icon.png`
与 `medias/logo.png` 均为黑白像素头像图标，由 `assets/build_icons.py` 从参考图裁切生成。