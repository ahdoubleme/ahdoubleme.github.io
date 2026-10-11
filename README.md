# Double me — 个人作品集

一个无需构建工具、可直接部署到 GitHub Pages 的静态个人网站。

## 发布步骤（Windows）

1. 登录 GitHub： https://github.com/ahdoubleme
2. 点击右上角 `+` → `New repository`。
3. Repository name 填写 `ahdoubleme.github.io`。
4. 选择 `Public`，勾选 `Add a README file`，点击 `Create repository`。
5. 在新仓库中点击 `Add file` → `Upload files`。
6. 把本文件夹中的 `index.html` 拖进上传区域。
7. 在下方 `Commit changes`，再次点击 `Commit changes` 确认。
8. 打开仓库 `Settings` → 左侧 `Pages`。
9. 在 `Build and deployment` 下，Source 选 `Deploy from a branch`。
10. Branch 选 `main`，目录选 `/(root)`，点击 `Save`。
11. 等待几分钟后访问 https://ahdoubleme.github.io/

## 修改网站

- 用 Windows 记事本或 VS Code 打开 `index.html`。
- 搜索 `Double me` 或页面里的中文内容，改成你想展示的文字。
- 在 GitHub 仓库打开 `index.html`，点击铅笔图标可在线编辑；保存时选择 `Commit changes`。
- 上传自己的图片时，把图片文件也上传到仓库，然后按需修改 HTML。

## 注意

- `ahdoubleme.github.io` 这个仓库名必须和 GitHub 用户名一致（用户名大小写不敏感）。
- 仓库应为 Public，GitHub Pages 的可用性和设置可能受账户或组织策略影响。
- 本网站目前使用 CSS 抽象插画，不依赖外部图片或 JavaScript 库。
