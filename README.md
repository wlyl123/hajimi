# Blockly Web Builder GPT

可视化拖拽建站工具，基于 Google Blockly 与 GPT AI 能力，支持一键生成生产级前端代码。

## 功能特性

- **可视化编辑**：基于 Google Blockly 的拖拽式编程界面，无需手写代码
- **AI 辅助**：集成 GPT 能力，智能生成和优化代码
- **一键导出**：生成生产级前端代码包，直接部署
- **响应式设计**：生成的页面自适应桌面/平板/手机

## 快速开始

1. 下载 `blockly-web-builder-gpt-dist.zip`
2. 解压到任意目录
3. 用静态服务器打开 `dist/index.html`

```bash
# 示例：使用 Python 启动静态服务器
cd dist
python -m http.server 8080
# 浏览器访问 http://localhost:8080
```

## 部署

### GitHub Pages

本项目已配置 GitHub Actions 自动部署到 GitHub Pages，推送 `main` 分支即可触发部署。

### 其他平台

将 `dist` 目录内容上传到任意静态托管平台（Vercel / Netlify / Cloudflare Pages 等）。

## 校验

SHA-256: `41436550242a76a834dbfbe10f39ccd8e54b81c8f17e485dfc6e677ff91c21cb`

## 技术栈

- Google Blockly — 可视化编程框架
- OpenAI GPT — AI 代码生成
- Vite — 前端构建工具
- TypeScript — 类型安全

## License

MIT
