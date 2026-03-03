# JiaTianrui1.github.io

个人简历主页（GitHub Pages）。

## 预览
部署后访问：`https://JiaTianrui1.github.io`

## 文件结构
- `index.html`：主页
- `assets/style.css`：样式
- `assets/resume.pdf`：简历 PDF

## 部署步骤（用户主页）
1. 在 GitHub 新建仓库：**JiaTianrui1.github.io**（Public）
2. 上传本项目文件（或本地 git push）
3. 打开仓库 Settings → Pages：
   - Source 选择 **Deploy from a branch**
   - Branch 选择 **main / (root)**
4. 访问：`https://JiaTianrui1.github.io`

## 更新简历
替换 `assets/resume.pdf` 后提交即可：
```bash
git add assets/resume.pdf
git commit -m "Update resume"
git push
```

> 注意：该页面会公开展示联系方式。若介意隐私，可删掉手机号或换成求职邮箱。
