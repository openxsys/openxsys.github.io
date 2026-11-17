# OpenXSys website

[Chinese](README.zh-CN.md) · [Website](https://openxsys.com/) · [OpenXSys Skill](https://github.com/gengshupeng/open-x-sys)

The official bilingual website, real-use showcase and domain-redirect source for OpenXSys.

| Directory | Purpose |
|---|---|
| `site/` | Homepage, language switching and optional route explorer |
| `gallery/ai-industry/` | The actual industry-research showcase in English and Chinese |
| `assets/readme/` | Showcase previews and diagrams |
| `redirects/` | Secondary-domain redirect source |

GitHub Pages publishes `main` from the repository root to **https://openxsys.com/**. `.nojekyll` keeps the site buildless.

GitHub Pages supports one apex domain per site. The redirect at **https://openxsys.cn/** is deployed from the `site-redirect` branch of the personal project repository. That branch contains only deployment output; its source is maintained here under `redirects/`. Both services are managed as one website, without a separate redirect repository.

Serve this repository with any local static HTTP server to preview it. The root page preserves the language query and section hash when opening `site/index.html`.

The Skill, installation instructions, issues, contributions and releases belong to the [main project repository](https://github.com/gengshupeng/open-x-sys).

MIT · #OpenXSys
