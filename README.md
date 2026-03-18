# OpenClaw 学习之旅

大庆的个人 OpenClaw 学习历程记录网站。

## 📁 文件结构

```
openclaw-learning-site/
├── index.html      # 主页面
├── styles.css      # 样式文件
├── script.js       # 交互脚本
└── README.md       # 本文件
```

## 🚀 如何查看网站

### 方式一：直接打开（最简单）
双击 `index.html` 文件，用浏览器打开即可。

### 方式二：本地服务器（推荐）
如果需要在手机或其他设备上预览，可以启动本地服务器：

```bash
# 进入项目目录
cd "/Users/liqing/项目文档/openclaw-learning-site"

# Python 3
python3 -m http.server 8080

# 或 Node.js
npx serve .

# 或 PHP
php -S localhost:8080
```

然后在浏览器访问：`http://localhost:8080`

## 📝 内容说明

| 板块 | 内容 |
|------|------|
| 学习历程 | 记录 OpenClaw 学习的关键时间节点 |
| 已掌握技能 | 飞书文档、Bitable、自动化工作流等 |
| 实战案例 | 每日简报系统等实际项目展示 |

## 🎨 自定义修改

### 添加新的时间线节点
编辑 `index.html`，在 `.timeline` 容器内添加：

```html
<div class="timeline-item">
    <div class="timeline-date">YYYY-MM-DD</div>
    <div class="timeline-content">
        <h3>标题</h3>
        <p>描述内容</p>
        <span class="tag tag-info">标签</span>
    </div>
</div>
```

### 修改配色
编辑 `styles.css`，修改 `:root` 中的颜色变量：

```css
:root {
    --primary-color: #1e40af;    /* 主色调 */
    --primary-light: #3b82f6;    /* 亮色 */
    --primary-dark: #1e3a8a;     /* 暗色 */
}
```

### 添加新项目案例
编辑 `index.html`，在 `.projects-section` 中添加新的 `.project-card`。

## 📱 响应式支持

网站已适配：
- 💻 桌面端（> 768px）
- 📱 平板端（480px - 768px）
- 📱 手机端（< 480px）

## 🔧 技术栈

- HTML5
- CSS3 (Flexbox + Grid)
- Vanilla JavaScript (ES6+)
- 无依赖、无框架

## 📄 License

MIT - 自由使用和修改

---

Built with ❤️ using OpenClaw
