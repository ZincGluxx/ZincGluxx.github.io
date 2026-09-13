# ZincGluxx 的博客

面向 GitHub Pages 的纯静态个人博客。首页是 `index.html`，文章在 `posts/`，样式在 `style.css`。无需安装依赖或运行构建命令。

## 本地预览

在本目录运行 `npx serve .`，或用任何静态文件服务器打开。页面使用根路径资源链接，本地预览时请从网站根目录访问。

## 发布到 GitHub 个人主页

1. 在 GitHub 创建公开仓库 `ZincGluxx.github.io`。
2. 将本目录推送到该仓库的默认分支。
3. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，选择默认分支和 `/ (root)`。
4. 等待 GitHub Pages 发布，然后访问 <https://zincgluxx.github.io/>。

## 写新文章

复制 `posts/hello.html` 作为新文章，修改标题、日期、描述和正文；再在 `index.html` 的 `.posts` 区域添加一张文章卡片并更新计数。确保新链接指向文章文件。
