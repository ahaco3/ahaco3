# Ahaco3 个人主页

这是我的个人 GitHub Pages 主页，采用简约清新的设计风格。

## 🎨 设计特点

- **配色方案**：以白色为主背景，薄荷绿（#34D399）为强调色，雾霾蓝为辅助色
- **字体**：Inter + Noto Sans SC，兼顾中英文显示
- **响应式**：适配桌面和移动设备
- **无依赖**：纯 HTML/CSS，无需 JavaScript 框架

## 🚀 本地预览

```bash
# 方法1：直接用浏览器打开
open index.html

# 方法2：使用 Python 简单服务器
python3 -m http.server 8000
# 然后访问 http://localhost:8000

# 方法3：使用 Node.js 的 serve
npx serve .
```

## 📝 如何维护

### 修改个人信息

打开 `index.html`，找到对应部分修改：

1. **名字**：搜索 `Ahaco3`，替换为你想要的名字
2. **简介**：在 `hero` 区域修改 `.subtitle` 和 `.tagline`
3. **关于我**：在 `about-card` 中修改段落内容

### 修改技能标签

找到 `skills-container` 部分，添加或删除 `.skill-tag`：

```html
<span class="skill-tag">你的新技能</span>
```

### 添加新项目

在 `projects-grid` 中添加新的 `project-card`：

```html
<div class="project-card">
    <h3>项目名称</h3>
    <p>项目描述...</p>
    <div class="project-tags">
        <span class="project-tag">技术标签</span>
    </div>
</div>
```

### 修改联系方式

在 `contact-links` 中修改链接：

```html
<a href="你的链接" class="contact-link" target="_blank">
    图标 + 文字
</a>
```

### 修改配色

如需调整颜色，编辑 CSS 变量部分（`:root`）：

```css
:root {
    --accent-primary: #新颜色;  /* 主要强调色 */
    --accent-secondary: #新颜色; /* 次要强调色 */
}
```

## 🌐 部署到 GitHub Pages

1. 在 GitHub 创建名为 `ahaco3.github.io` 的仓库
2. 将本文件夹内容推送到仓库
3. 在仓库 Settings > Pages 中启用 GitHub Pages
4. 访问 https://ahaco3.github.io 查看效果

## 📄 文件结构

```
ahaco3-github-pages/
├── index.html      # 主页（所有内容都在这里）
├── README.md       # 本文件
└── .gitignore      # Git 忽略文件（可选）
```

## 💡 小贴士

- 使用 VS Code 的 "Live Server" 插件可以实时预览修改
- 修改后记得清除浏览器缓存（Ctrl+Shift+R）查看最新效果
- 可以使用 [Favicon.io](https://favicon.io/) 生成网站图标

---

**保持简约，持续进化。**
