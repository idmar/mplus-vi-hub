# GitHub 部署指引

本目录已是一个完整的 git 仓库（分支 `main`，含首次提交）。任选以下一种方式部署：

## 方式 A：命令行推送（推荐）

```bash
# 1. 解压（如使用压缩包）
tar -xzf mplus-vi-hub.tar.gz && cd mplus-vi-hub

# 2. 在 GitHub 网页创建空仓库（不要勾选 README/.gitignore/License）
#    https://github.com/new  →  例如仓库名 mplus-vi-hub

# 3. 关联远程并推送（把 <用户名> 换成你的 GitHub 用户名）
git remote add origin https://github.com/<用户名>/mplus-vi-hub.git
git push -u origin main
```

推送时用户名填 GitHub 用户名，密码填 **Personal Access Token**
（在 https://github.com/settings/tokens 生成，勾选 `repo` 权限）。

## 方式 B：GitHub 网页直接上传

1. https://github.com/new 创建仓库（如 `mplus-vi-hub`）
2. 在仓库页面点击 **Add file → Upload files**
3. 把本目录下的 `index.html`、`README.md`、`.gitignore` 和 `images/`、`brand-kit/` 两个文件夹拖入上传
4. 提交（Commit changes）

> 注意：网页上传无法保留 git 提交历史；如需保留历史请用方式 A。

## 启用 GitHub Pages（在线预览）

推送完成后：

1. 仓库 **Settings → Pages**
2. Source 选择 **Deploy from a branch**，Branch 选 `main` / 根目录 `(root)`，保存
3. 约 1 分钟后访问 `https://<用户名>.github.io/mplus-vi-hub/`

本站点为纯静态 HTML，无需任何构建步骤，Pages 开箱即用。
