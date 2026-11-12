# 私版 DeepSeek（手机端）

一个单页应用，无后端。浏览器直接连 `api.deepseek.com`，API Key 与聊天记录只保存在本机。

- `index.html` —— 全部代码
- `manifest.json` / `icon.svg` / `icon-maskable.svg` —— 安装信息与图标
- `sw.js` —— 离线壳
- `_headers` —— Cloudflare Pages 用的响应头（Gitee Pages 会忽略，无害）

打开后：右上角设置 → 填 API Key → 开始。
