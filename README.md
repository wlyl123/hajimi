# Blockly Web Builder GPT

可视化拖拽建站工具，基于 Google Blockly 与 GPT AI 能力，支持一键生成生产级前端代码。

## 下载

> 从 [GitHub Releases v0.1.0](https://github.com/wlyl123/blockly-web-builder-gpt/releases/tag/v0.1.0) 下载：

| 版本 | 下载链接 | 说明 | 授权 |
| ---- | -------- | ---- | ---- |
| Demo 版 | [blockly-web-builder-demo-v0.1.0.zip](./blockly-web-builder-demo-v0.1.0.zip) | 仅含开源层，免费使用 | MIT |
| Release 版 | [blockly-web-builder-release-v0.1.0.zip](./blockly-web-builder-release-v0.1.0.zip) | 含加密商业功能，需授权码 | 商业授权 |

## 功能特性

- **可视化编辑**：基于 Google Blockly 的拖拽式编程界面，无需手写代码
- **AI 辅助**：集成 GPT 能力，智能生成和优化代码
- **一键导出**：生成生产级前端代码包，直接部署
- **响应式设计**：生成的页面自适应桌面/平板/手机
- **代码分层**：开源层 (MIT) + 私有层 (商业授权)
- **混淆加密**：痛点功能 javascript-obfuscator 混淆保护
- **授权管理**：RSA 授权码生成与在线验证

## 快速开始

1. 下载对应版本的 zip 包
2. 解压到任意目录
3. 用静态服务器打开 `index.html`

```bash
# 示例：使用 Python 启动静态服务器
python -m http.server 8080
# 浏览器访问 http://localhost:8080
```

## 部署

### GitHub Pages

本项目已配置 GitHub Actions 自动部署到 GitHub Pages，推送 `main` 分支即可触发部署。

### 其他平台

将解压后的内容上传到任意静态托管平台（Vercel / Netlify / Cloudflare Pages 等）。

## 技术栈

- Google Blockly — 可视化编程框架
- OpenAI GPT — AI 代码生成
- Vite + TypeScript — 前端构建
- React — UI 框架

## License

- 开源层：MIT License
- 私有层：商业授权，需购买授权码

## 链接

- 开发仓库：[blockly-web-builder-gpt](https://github.com/wlyl123/blockly-web-builder-gpt)
- Releases：[v0.1.0](https://github.com/wlyl123/blockly-web-builder-gpt/releases/tag/v0.1.0)
