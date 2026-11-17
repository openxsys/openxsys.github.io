# OpenXSys 域名跳转

[English](README.md)

本仓库为 OpenXSys 提供 `openxsys.cn` 入口。正式官网是 <https://openxsys.com/>，主项目位于 <https://github.com/openxsys/open-x-sys>。

GitHub Pages 从 `main` 分支根目录发布。自定义域名为 `openxsys.cn`；DNS 配置完成后，GitHub 同时处理 `www` 别名。

入口通过浏览器跳转到正式官网，保留路径、查询参数与页面锚点。`404.html` 为其他路径提供相同的跳转。关闭 JavaScript 的浏览器可通过页面刷新或链接进入官网首页。这是静态跳转页，不提供 HTTP 301 重定向服务。

根域名使用 GitHub Pages 的 A 记录，`www` 的 CNAME 指向 `openxsys.github.io`。HTTPS 由 GitHub Pages 提供。
