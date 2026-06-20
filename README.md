# 袁子炎 · 个人简历

> Python 后端开发 / AI 应用开发

一个温暖、极简风格的个人简历静态网页，展示技能、项目作品、工作经历和教育背景。

## 预览

在线访问：https://idsion123.github.io/jianli

## 功能

- 一页式滚动布局，响应式设计（桌面 / 平板 / 手机）
- 技能分类展示（卡片 + 进度条动画）
- 项目作品展示（含截图占位）
- 工作经历时间轴
- 首尾呼应的米白/暖灰色调
- 渐入动画和滚动过渡效果

## 技术栈

纯静态页面，零外部依赖（除 Google Fonts）：

- HTML5
- CSS3（Flexbox / Grid / 自定义动画）
- JavaScript（IntersectionObserver 驱动滚动动画）

## 本地运行

```bash
# 直接用浏览器打开
open index.html
# 或用 Python 启动本地服务
python -m http.server 8000
# 访问 http://localhost:8000
```

## 部署

支持部署至任意静态托管平台：

- **GitHub Pages** — `main` 分支推送即可
- **Vercel** — 导入项目，零配置部署
- **Netlify** — 拖拽 `index.html` 或连接 Git 仓库

## 项目结构

```
├── index.html          # 主页面（含打印版简历）
├── PRDS/               # 产品需求文档
├── design/             # UI 设计文档
├── images/
│   ├── 头像/           # 个人头像
│   ├── projects/       # 项目截图
│   └── 设计参考/       # 设计参考图
└── 参考简历/           # 原始简历文档
```

## License

MIT
