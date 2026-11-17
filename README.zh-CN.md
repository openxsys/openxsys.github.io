# OpenXSys 官网

[English](README.md) · [官网](https://openxsys.com/?lang=zh) · [OpenXSys Skill 主仓库](https://github.com/gengshupeng/open-x-sys)

这里统一维护 OpenXSys 中英文官网、真实使用案例和域名转发源码。

| 目录 | 用途 |
|---|---|
| `site/` | 首页、语言切换和可选的路线探索页 |
| `gallery/ai-industry/` | 中英文 AI 产业研究真实案例 |
| `assets/readme/` | 案例预览图和示意图 |
| `redirects/` | 备用域名转发源码 |

GitHub Pages 从 `main` 分支根目录发布到 **https://openxsys.com/**。`.nojekyll` 保持纯静态部署。

GitHub Pages 每个站点支持一个主域名。**https://openxsys.cn/** 的转发使用个人项目仓库的 `site-redirect` 分支部署。该分支只存放部署产物，源码统一保存在这里的 `redirects/` 中；不再单独维护转发仓库。

使用任意本地静态 HTTP 服务即可预览。根页面跳转到 `site/index.html` 时会保留语言参数和章节锚点。

Skill、安装说明、问题反馈、贡献和版本发布统一在[项目主仓库](https://github.com/gengshupeng/open-x-sys)维护。

MIT · #OpenXSys
