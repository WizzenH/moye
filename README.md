# 墨页 Moye

中文长文图文排版工具。支持古风水墨主题、竖排标题、内置字体、章节标题识别、自动分页、JPG/ZIP 与 PDF 导出。

## 本地运行

无需安装依赖或构建。运行 `python3 -m http.server 8080 --directory dist`，打开 http://localhost:8080 。

草稿保存在浏览器本地。字体文件及来源说明位于 `dist/fonts/`。PDF 为图片版。

## 检查

运行 `node --check dist/app.js` 和 `node check.cjs`。

本仓库保存网站源码；GitHub 仓库公开与网站访问权限分别设置。
