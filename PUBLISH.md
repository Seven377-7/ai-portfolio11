# GitHub 网页端发布步骤

如果本机暂时没有安装 Git，也可以先用 GitHub 网页端上传项目。

## 1. 新建仓库

1. 打开 GitHub。
2. 点击右上角 `+`。
3. 选择 `New repository`。
4. 仓库名建议：`ai-portfolio`。
5. 选择 `Public`。
6. 不需要勾选自动创建 README，因为本项目已经有 `README.md`。

## 2. 上传文件

1. 进入新仓库。
2. 点击 `uploading an existing file`。
3. 把本文件夹里的内容拖进去：
   - `index.html`
   - `README.md`
   - `PUBLISH.md`
   - `.gitignore`
   - `.nojekyll`
   - `assets/cover.png`
4. 提交说明写：`Add AI portfolio page`。
5. 点击 `Commit changes`。

## 3. 开启 GitHub Pages

1. 进入仓库 `Settings`。
2. 左侧选择 `Pages`。
3. Source 选择 `Deploy from a branch`。
4. Branch 选择 `main`。
5. Folder 选择 `/root`。
6. 保存后等待 1-3 分钟。

发布成功后，你会得到类似这样的地址：

```text
https://你的用户名.github.io/ai-portfolio/
```

## 4. 后续再学 Git 命令

等 Git 安装成功后，再学习命令行流程：

```bash
git init
git add .
git commit -m "Add AI portfolio page"
git remote add origin <你的仓库地址>
git push -u origin main
```
