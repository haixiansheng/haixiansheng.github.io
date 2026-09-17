# 🖼️ 免费在线图片工具 · Free Online Image Tools

一组**纯浏览器本地运行**的免费图片工具 —— 没有服务器，图片不上传。

**在线访问：** https://haixiansheng.github.io/

## 🧰 工具列表

| 工具 | 说明 | 地址 |
|---|---|---|
| 🔒 **人脸马赛克** | 自动识别人脸打码（马赛克/模糊/黑块） | [https://haixiansheng.github.io/face-mosaic/](https://haixiansheng.github.io/face-mosaic/) |
| 🗜️ **图片压缩** | 最高省 90% 体积，支持目标大小模式 | [https://haixiansheng.github.io/image-compressor/](https://haixiansheng.github.io/image-compressor/) |
| 🔄 **图片格式转换** | PNG/JPG/WebP/BMP 互转，透明通道智能处理 | [https://haixiansheng.github.io/image-converter/](https://haixiansheng.github.io/image-converter/) |

## ✨ 共同特点

- 🔒 **图片不上传** — 没有后端服务器，技术上无法存储你的图片
- ✈️ **断网可用** — 首次加载后，计算全在本地
- 🆓 **免费 · 免注册 · 无水印 · 不限量**
- 🕵️ **自动清除 EXIF** — 顺带移除 GPS 位置隐私
- 🌏 **中英双语**

## 🔍 自己验证（30 秒）

按 `F12` → **Network** 面板 → 清空 → 处理一张图片。
如果只看到页面自身的静态资源，说明**图片没有被上传**。这个方法无法作弊。

更直观：加载完页面后**断开网络**，再处理一张图——能正常用就说明计算全在本地。

## 📁 结构

```
haixiansheng.github.io/          # 本仓库（工具总站）
├── index.html / en/index.html   # 工具导航
├── about.html / privacy.html
├── style.css
└── <工具各有独立仓库>
```

各工具源码：
- [face-mosaic](https://github.com/haixiansheng/face-mosaic)
- [image-compressor](https://github.com/haixiansheng/image-compressor)
- [image-converter](https://github.com/haixiansheng/image-converter)

## 📄 License

MIT
