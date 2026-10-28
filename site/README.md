# 曾朋涛 · 个人网站

单页静态站点，无需构建工具，直接部署到 GitHub Pages。

## 文件

```
index.html          首页（内嵌样式）
assets/photo.jpg    证件照
assets/resume.pdf   简历 PDF
```

## 部署到 GitHub Pages（3 步）

1. 在 GitHub 新建仓库，仓库名必须填成你的用户名小写 + `.github.io`：
   - 例如你的用户名是 `Gin-zeng`，仓库名就填 `Gin-zeng.github.io`
   - 选 **Public**，不勾选 README（保持空仓库）

2. 把这个文件夹里的三个文件上传到仓库根目录（上传时 `assets` 目录里的两个文件保持在同一路径）：
   - `index.html`
   - `assets/photo.jpg`
   - `assets/resume.pdf`

3. 打开仓库 **Settings → Pages**，把 **Source** 改成 `main` 分支（或 Deploy from a branch → main / root），保存。

大约 1 分钟后，浏览器访问：

```
https://Gin-zeng.github.io
```

就能看到网站。

## 修改内容

- 直接编辑 `index.html`：姓名、简介、项目卡片、技能、荣誉都在正文里，照着改即可。
- 换照片：把 `assets/photo.jpg` 替换成同名图片。
- 换简历：把 `assets/resume.pdf` 替换成新的 PDF。

## 注意

- 仓库必须是 Public，GitHub 免费版 Pages 只支持公开仓库（付费 Pro 才能私有）。
- 如果域名访问报 404，先等 1 分钟刷新；再检查 Settings → Pages 里的 Source 是否保存成功。
