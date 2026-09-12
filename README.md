# 简历随行 · 发布产物（Release artifacts）

本仓库只存放「简历随行」浏览器扩展的**发布产物**，不含源码。

- `latest.json`：版本清单（扩展的「检查更新」读取它）
- `lvsuiv-<版本>.zip`：可分发扩展包（解压后用 Edge/Chrome 的开发者模式加载）

扩展只读取 latest.json 的版本号与下载链接，**不上传任何简历/个人信息**（请求为无正文 GET，不带 Cookie）。
