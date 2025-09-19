# QN交流社区 - 游戏交流平台

这是一个游戏爱好者的综合交流平台，提供游戏讨论、攻略分享、新闻资讯等内容。

## 项目特点

- 现代化的UI设计，采用渐变色和阴影效果
- 响应式布局，适配各种屏幕尺寸
- 丰富的动画效果，提升用户体验
- 无障碍设计，支持高对比度模式和减少动画模式
- 完善的交互功能，包括标签切换、平滑滚动、表单提交等

## GitHub Pages 部署指南

### 准备工作
1. 确保已安装 [Git](https://git-scm.com/downloads)
2. 在 GitHub 上创建一个新的仓库

### 部署步骤

1. 将项目克隆到本地
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

2. 将项目文件添加到仓库中
```bash
git add .
git commit -m "Initial commit"
```

3. 推送到 GitHub
```bash
git push origin main
```

4. 启用 GitHub Pages
   - 进入仓库的 "Settings" 页面
   - 在左侧导航中点击 "Pages"
   - 在 "Branch" 下拉菜单中选择 "main" 或 "master"
   - 点击 "Save"
   - 等待几分钟，GitHub Pages 将自动部署你的网站

5. 访问你的网站
   - 部署完成后，你可以通过 `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/` 访问你的网站

## 注意事项

- 本项目已包含 `.nojekyll` 文件，确保 GitHub Pages 不会使用 Jekyll 处理网站
- 所有图片均使用外部链接，确保在 GitHub Pages 上能正常加载
- 如需修改网站内容，请直接编辑 `qn_community_fixed.html` 文件

## 技术栈

- HTML5
- CSS3
- JavaScript
- Font Awesome 图标库