# Modern Portfolio - 现代化个人作品集

一个设计精美、功能完整的个人作品集网站，展示你的技能和项目。

## ✨ 特性亮点

### 🎨 设计特点
- **玻璃态设计** - 现代流行的 Glassmorphism 风格
- **动态背景** - 流动的渐变动画效果
- **精致动画** - 流畅的滚动和交互动画
- **打字机效果** - 英雄区域动态文字展示
- **数字滚动** - 统计数据动画效果
- **代码窗口** - 创意的开发者信息展示

### 🛠️ 技术栈
- **HTML5** - 语义化结构
- **CSS3** - 高级动画、Flexbox、Grid、玻璃态效果
- **JavaScript ES6+** - 交互式功能
- **Google Fonts** - Inter 字体
- **响应式设计** - 完美适配各种设备

### 📱 功能模块
- **导航栏** - 平滑滚动、激活状态指示
- **英雄区域** - 个人介绍、统计数据、代码窗口
- **关于我** - 详细介绍、亮点展示
- **技能栈** - 分类展示技术能力
- **项目展示** - 过滤功能、悬停效果
- **联系方式** - 联系表单、社交链接

## 🚀 快速开始

### 本地运行

1. 克隆项目
```bash
git clone https://github.com/aur0ra333/modern-portfolio-demo.git
cd modern-portfolio-demo
```

2. 直接在浏览器打开
```bash
open index.html
```

3. 或使用本地服务器
```bash
npx http-server
# 访问 http://localhost:8080
```

### 部署到 GitHub Pages

1. 创建 GitHub 仓库
2. 推送代码
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/modern-portfolio-demo.git
git push -u origin main
```

3. 启用 GitHub Pages
   - Settings → Pages
   - Source: Deploy from a branch (main)
   - Save

## 🎯 自定义指南

### 修改个人信息

编辑 `index.html`:
- 姓名、职位、介绍文字
- 统计数据（项目数、经验年数等）
- 技能标签
- 项目信息
- 联系方式

### 修改配色方案

编辑 `styles.css` 中的 CSS 变量:
```css
:root {
    --primary: #6366f1;      /* 主色调 */
    --secondary: #ec4899;    /* 辅助色 */
    --accent: #06b6d4;       /* 强调色 */
}
```

### 添加更多项目

复制 `.project-card` 结构，修改内容即可。

## 📊 项目截图

（添加项目截图）

## 🔧 扩展建议

- [ ] 添加后端 API 存储联系表单数据
- [ ] 集成 EmailJS 发送邮件
- [ ] 添加多语言支持
- [ ] 添加深色/浅色主题切换
- [ ] 集成 Google Analytics
- [ ] 添加项目详情页
- [ ] 添加博客功能
- [ ] 集成 CMS 系统

## 📄 License

MIT License

## 👤 作者

你的姓名 - [@yourusername](https://github.com/yourusername)

---

**适合简历的亮点项目** 🚀

- 展示前端开发能力
- 展示 UI/UX 设计能力
- 展示动画和交互实现能力
- 可直接用作个人网站
