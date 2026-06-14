# AI 工具箱

给开发者的 AI 调试与效率工具集，纯静态网页，无需安装，开箱即用。

## 工具列表

### 💬 Messages 可视化

将 OpenAI / Anthropic 格式的 `messages` JSON 渲染成直观的对话视图。

**支持功能：**
- 多角色消息展示（user / assistant / system / tool）
- 工具调用（tool_use）与工具结果（tool_result）的结构化展示
- 嵌套内容块（text、image、document 等）
- 实时渲染，粘贴 JSON 即可预览

**适用场景：** 调试 LLM 对话流、排查 API 请求结构、分享对话记录。

## 使用方式

直接在浏览器中打开 `index.html`，或部署到任意静态托管服务（GitHub Pages、Vercel、Netlify 等）。

```bash
# 本地预览（任选其一）
open index.html
python3 -m http.server 8080
```

## 技术栈

纯原生 HTML / CSS / JavaScript，无任何依赖。

## License

MIT
