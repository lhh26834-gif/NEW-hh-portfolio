# HH L Portfolio

这是一个个人作品集展示网站项目。

## 立即查看

如果本机还没有安装 Node.js / npm，可以直接打开：

```txt
preview.html
```

或访问当前本地预览服务：

```txt
http://localhost:4173
```

`preview.html` 是不依赖安装包的静态预览版，图片读取自 `public/portfolio/`。

## 推荐上传版本

建议上传这个轻量部署包：

```txt
deploy-site-optimized/
```

这个文件夹已经把图片压缩为 WebP，总体积约 3MB，适合上传 GitHub Pages、Netlify 或 Vercel。

## 视频链接

视频作品已经改为 B 站嵌入播放：

```txt
https://www.bilibili.com/video/BV1pQLy6gEem/
```

部署到 Vercel / Netlify / GitHub Pages 前，不需要上传本地 mp4，只保留 `abai-daily-vlog-cover.jpg` 作为封面即可。

## React + Vite 版本

安装 Node.js 后，在当前目录执行：

```bash
npm install
npm run dev
```

然后打开终端中显示的本地地址。

## 素材目录

所有图片放在：

```txt
public/portfolio/
```

React/Vite 版本使用 `/portfolio/文件名` 路径；静态预览版使用 `public/portfolio/文件名` 路径。视频播放使用 B 站链接，不依赖本地 mp4。
