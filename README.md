# Twobro 个人网站

一个现代化的个人网站，展示技术栈、技能和作品。

## 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **样式**: 自定义CSS，Tiffany配色方案
- **图标**: Font Awesome 6.0
- **字体**: Inter (Google Fonts)
- **部署**: GitHub Pages

## 网站特性

### 🎨 设计特色
- 现代化的Tiffany蓝色主题
- 响应式设计，支持移动端
- 平滑的动画效果
- 专业的排版和布局

### 🚀 技术特性
- **托管**: GitHub Pages
- **CDN**: Cloudflare全球加速
- **安全**: TLS 1.2/1.3加密
- **性能**: IPv4/IPv6双栈支持

### 📱 功能模块
- 个人介绍和技能展示
- 作品集展示
- 技术栈介绍
- 联系方式

## 部署到GitHub Pages

### 方法一：自动部署（推荐）

1. 将代码推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择部署源为 `gh-pages` 分支
4. 每次推送到 `main` 分支时会自动部署

### 方法二：手动部署

1. 克隆仓库到本地
2. 安装依赖（如果需要）
3. 推送到GitHub
4. 在仓库设置中启用GitHub Pages

## 文件结构

```
├── index.html          # 首页
├── about.html          # 关于页面
├── skills.html         # 技能页面
├── portfolio.html      # 作品页面
├── contact.html        # 联系页面
├── 404.html           # 404错误页面
├── styles.css          # 样式文件
├── script.js           # JavaScript文件
├── README.md           # 说明文档
└── .github/workflows/  # GitHub Actions配置
    └── deploy.yml      # 自动部署配置
```

## 自定义配置

### 修改个人信息
编辑各个HTML文件中的个人信息部分。

### 修改样式
编辑 `styles.css` 文件中的CSS变量：
```css
:root {
    --tiffany-blue: #81D8D0;
    --tiffany-light: #E8F6F3;
    --tiffany-dark: #5BA3A0;
    /* 其他颜色变量 */
}
```

### 添加新页面
1. 创建新的HTML文件
2. 复制现有页面的基本结构
3. 在导航栏中添加链接
4. 添加相应的样式

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT License

## 联系方式

- 邮箱: twobro@example.com
- 微信: twobro-dev
- GitHub: github.com/twobro
- LinkedIn: linkedin.com/in/twobro 