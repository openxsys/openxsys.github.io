# OpenXSys site redirect

[Chinese](README.zh-CN.md)

This repository provides a lightweight redirect to the official OpenXSys website at <https://openxsys.com/>. The main project is <https://github.com/openxsys/open-x-sys>.

GitHub Pages publishes this repository from the root of `main`. The custom domain is recorded in `CNAME`; GitHub also handles its `www` alias when DNS is configured.

The landing page uses a browser redirect to the official website, preserving the path, query string and fragment. The same page is used for unknown paths through `404.html`. Browsers without JavaScript use the refresh or continuation link to the home page. This is a static redirect page, not an HTTP 301 redirect service.

DNS for the apex domain uses GitHub Pages A records. The `www` CNAME points to `openxsys.github.io`. HTTPS is provided by GitHub Pages.
