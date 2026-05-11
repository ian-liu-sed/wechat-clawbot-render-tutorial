# 微信接入 ClawBot 教程（静态站点）

我们的教程部署在render.com [DeepSeek-Weichat-Clawbot-Tutorial](https://wechat-clawbot-render-tutorial.onrender.com)

## 教程正文在哪里

| 文件 | 说明 |
|------|------|
| [`index.html`](index.html) | 教程主文档 |
| [`styles/main.css`](styles/main.css) | 页面样式（深色主题，与 `deepseek-tui-openclaw-tutorial` 风格相近） |



## 可选：静态托管声明

[`render.yaml`](render.yaml) 声明了 `runtime: static` 与发布目录为仓库根目录，便于使用支持 Blueprint 的托管方式一键创建静态服务。若你使用其他平台，可忽略该文件，只要保证构建产物或根目录能对外提供 `index.html` 与 `styles/` 即可。

## 本地预览

在项目根目录执行（任选其一）：

```bash
# Python 3
python -m http.server 8080
```

浏览器访问 `http://127.0.0.1:8080/` 查看效果。

## 维护说明

- 更新教程内容：只改 `index.html`；样式调整改 `styles/main.css`。  

