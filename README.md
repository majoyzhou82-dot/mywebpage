# 独立开发者个人主页

这是一个简洁、现代的个人主页，展示独立开发者的技能、项目和工作方式。

## 文件结构

```
mywebpage/
├── index.html      # 主页面
├── styles.css      # 样式文件
├── script.js       # 交互脚本
└── README.md       # 说明文档
```

## 本地预览

直接在浏览器中打开 `index.html` 文件即可预览。

## 部署选项

### 1. GitHub Pages
- 将仓库推送到 GitHub
- 在 Settings > Pages 中启用 GitHub Pages
- 选择 main 分支作为源

### 2. Netlify / Vercel
- 直接拖放文件夹到 Netlify/Vercel
- 或连接 GitHub 仓库自动部署

### 3. 静态托管服务
- Cloudflare Pages
- AWS S3 + CloudFront
- 任何支持静态网站的托管服务

## 自定义内容

### 需要替换的占位符：

1. **联系方式**
   - `your-email@example.com` → 你的邮箱
   - `https://twitter.com/yourhandle` → 你的 Twitter 链接

2. **项目链接**
   - `在 Enter 查看 →` 的 `href="#"` → 你的项目链接
   - `简历/作品集 →` 的 `href="#"` → 你的简历或作品集链接

3. **视频内容**
   - 将 `[视频预览或链接]` 替换为实际的视频嵌入代码或链接

4. **版权信息**
   - footer 中的 `独立开发者` 可替换为你的名字

## 视觉定制

在 `styles.css` 中修改 CSS 变量：

```css
:root {
    --bg-color: #0a0a0a;        /* 背景色 */
    --text-primary: #ffffff;    /* 主文字颜色 */
    --text-secondary: #a0a0a0;  /* 次要文字颜色 */
    --accent-color: #3b82f6;    /* 强调色（蓝色） */
}
```

## 特性

- ✅ 响应式设计，支持移动端
- ✅ 滚动动画效果
- ✅ 克制的配色方案
- ✅ 纯静态文件，易于部署
- ✅ 无外部依赖
- ✅ SEO 优化的 meta 标签

## 浏览器支持

- Chrome/Edge (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- 移动浏览器
