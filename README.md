# Accounting Games · GitHub Pages

当前多游戏版本包含三个入口：Account Name Cards、Accounting Elements 和 Open Door。部署文件已经整理在 `github-pages-upload/` 文件夹内。

## 上传到已有 GitHub 仓库

1. 打开仓库的 `main` 分支。
2. 将 `github-pages-upload/index.html` 上传到仓库根目录，并确认仓库中的旧 `index.html` 被替换。
3. 不需要上传 `questions.js`；这版游戏的题库和逻辑都包含在 `index.html` 中。旧文件若仍留在仓库，不会被新页面调用。
4. 等 GitHub Pages 自动更新完成后，原来的 Pages 首页链接会显示新游戏。

## 新建 GitHub 仓库

1. 新建一个 **Public** 仓库。
2. 上传 `github-pages-upload/` 里面的 `index.html` 和本说明文件。上传时把 `index.html` 放在仓库根目录，不要把整个文件夹嵌套上传。
3. 打开 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/(root)`，点击 **Save**。
4. Pages 发布后，在 Settings → Pages 页面复制网站地址。

## 文件说明

- `dr-cr-doors.html`：当前多游戏页面的源文件。
- `github-pages-upload/index.html`：适合作为 GitHub Pages 首页上传的副本。
