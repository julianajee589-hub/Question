# Juliana的问题解决系统 2.0

蓝色蝴蝶主题、纯静态、离线优先的 ChatGPT 指令生成器。

## 直接离线使用

解压后双击 `index.html` 即可。无需安装 Node.js、npm 或任何依赖。

## 发布到 GitHub Pages

1. 在 GitHub 创建一个仓库。
2. 将解压后的全部内容上传到仓库根目录，包括 `index.html`、`manifest.webmanifest`、`assets` 文件夹、`README.md` 和 `.nojekyll`。
3. 打开仓库 `Settings` → `Pages`。
4. 在 `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/ (root)`，保存。

## 职责边界

- 网站：整理少量输入，生成高质量 ChatGPT 指令。
- ChatGPT：逐步完成客观分析、结构识别、杠杆寻找与方案比较。
- Notion：管理最终形成的项目、任务和执行过程。

网站只在当前浏览器中自动保存草稿，不上传数据，也不包含项目管理、提醒或复盘功能。

## 添加到手机主屏幕

- iPhone/iPad：在 Safari 中打开网站，点击“分享”→“添加到主屏幕”。
- Android：在 Chrome 中打开网站，选择“添加到主屏幕”或“安装应用”。

主屏幕名称为“Juliana系统”，图标为银蓝色水光蝴蝶。
