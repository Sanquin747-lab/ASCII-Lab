# ASCII LAB

万物，字符化。一个完全在浏览器中运行的 ASCII 视觉转换工具。

## 功能

- 图片、视频、摄像头、屏幕共享与中英文文字输入。
- 实时字符转换，六种字符集及自定义字符。
- 字符密度、亮度、对比度、原色与单色控制。
- 四套视觉预设，桌面和手机布局。
- 导出 PNG、TXT、独立 HTML，以及无音频 WebM 录制。

素材始终在本机处理，不上传到服务器。摄像头和屏幕共享需要浏览器授权，推荐桌面版 Chrome 或 Edge。PDF、文档等可通过共享其可见画面转换，不直接解析原文件。GIF 使用静态帧。

## 本地使用

直接用浏览器打开 `index.html`。实时设备输入建议通过 HTTPS 或本机 HTTP 服务使用。

## GitHub Pages

在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，分支选择 **main**，目录选择 **/ (root)**，保存。

这是无依赖的静态网站，无需安装依赖、构建或配置密钥。GitHub Pages 完成部署后，网站地址会显示在 Pages 设置中。

后续改动在功能分支提交，通过 PR 审核并获得发布确认后合并到 `main`，再由 GitHub Pages 更新网站。详见 [开发规范](CONTRIBUTING.md)。磁带雨预览在 `feature/tape-rain`，尚未作为稳定版发布。
