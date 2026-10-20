# viewFile 文件预览

基于 Vue.js + Element-UI + PDF.js 实现的纯前端文件预览组件，CDN 资源已全部本地化，开箱即用。

## 支持预览的文件类型

| 分类 | 格式 |
| --- | --- |
| Office 文档 | doc, docx, xls, xlsx, ppt, pptx |
| PDF | pdf |
| 图片 | jpg, jpeg, png, gif, svg, webp, tiff, bmp, psd |
| 视频 | mp4, mkv, avi, flv, mov, wmv, webm, ogv |
| 音频 | mp3, wav, ogg, aac, m4a, flac, wma |
| 文本 | txt, md, rtf, csv, tsv, sh, bat, ps1, sql, xml, json, yaml, html, css, js |

## 使用方式

1. 直接部署为静态站点，打开 `index.html`。
2. 在输入框中粘贴文件 URL，点击「预览」。
3. 或通过地址栏参数传入文件地址：

```
index.html?url=https://example.com/1.pdf
```

4. 全屏嵌入模式（适合 iframe 集成）：

```
index.html?url=https://example.com/1.pdf&view=wp
```

5. 也支持将本地文件拖入页面进行预览。

## 特性

- 每种文件类型有独立的预览样式
- 响应式设计，适配 PC 与移动端
- CDN 资源本地化，预览速度快
- Office 文档通过微软 Office Online 服务预览（需公网可访问的文件地址）

## 开源协议

[MIT](LICENSE)
