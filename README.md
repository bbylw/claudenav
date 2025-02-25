# WebNavigator - 网站导航目录

> 🎨 一个优雅的网站导航目录，支持深色模式、搜索和分类功能。由 Claude 3.7 Sonnet AI 生成。
![demo](https://github.com/bbylw/claudenav/blob/main/demo.png)
## 🌟 特点

- 🎯 简洁优雅的用户界面
- 🌓 支持深色/浅色主题切换
- 🔍 实时搜索功能
- 📑 网站分类标签
- 📱 响应式设计，支持移动端
- ✨ 平滑动画和交互效果

## 🚀 在线演示

- GitHub Pages: `https://你的用户名.github.io/claudenav`
- Cloudflare Pages: `https://你的项目名.pages.dev`

## 📦 快速部署

1. 点击页面右上角的 Fork 按钮，将本仓库 Fork 到你的 GitHub 账号下
2. 在你的仓库设置（Settings）中，找到 Pages 选项
3. 在 Source 选项中选择 main 分支，点击 Save
4. 等待几分钟后，你的网站就会部署在 `https://你的用户名.github.io/claudenav`

## 🔧 自定义网站

编辑 `script.js` 文件中的 `websites` 数组来自定义网站列表：

```javascript
const websites = [
    {
        name: "网站名称",
        url: "https://网站地址",
        description: "网站描述",
        icon: "fab fa-图标类名",  // Font Awesome图标
        category: "分类名称"      // tech/social/shopping/video/news/tools
    },
    // 添加更多网站...
];
```

## 🌐 其他部署方式

### Cloudflare Pages部署

1. 在 [Cloudflare Dashboard](https://dash.cloudflare.com/) 中创建新的 Pages 项目
2. 导入你 Fork 的 GitHub 仓库
3. 部署设置保持默认即可（无需配置构建命令和输出目录）
4. 点击部署，几分钟后即可通过 `https://你的项目名.pages.dev` 访问

## 🎨 自定义主题

编辑 `styles.css` 文件中的CSS变量来自定义主题颜色：

```css
:root {
    --primary-color: #4361ee;
    --secondary-color: #7209b7;
    --accent-color: #f72585;
    /* 更多颜色变量... */
}
```

## 📝 许可

MIT License

## 🤖 AI生成说明

本项目由 Claude 3.7 Sonnet AI 生成，包括：
- 项目结构设计
- HTML/CSS/JavaScript代码
- 文档编写

---

🌟 如果觉得这个项目有帮助，欢迎Star！
