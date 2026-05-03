# 超级九宫格游戏

一个基于 HTML、CSS 和 JavaScript 的超级九宫格游戏，支持双人对战。

## 游戏特色

- 🎮 **双版本支持**：基础版和进阶版
- 🎯 **策略性强**：九宫格嵌套，需要考虑全局策略
- 📱 **响应式设计**：支持手机和平板设备
- 🎨 **精美UI**：现代化界面设计

## 部署指南

### Vercel 部署

1. **推送代码到 GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/your-username/super-tic-tac-toe.git
   git push -u origin main
   ```

2. **部署到 Vercel**
   - 将代码推送到 GitHub 后，访问 [Vercel](https://vercel.com)
   - 点击 "New Project"
   - 选择你的 GitHub 仓库
   - 点击 "Deploy"

3. **自定义域名（可选）**
   - 在 Vercel 仪表板中配置你的自定义域名

### 本地开发

```bash
# 安装 Vercel CLI
npm install -g vercel

# 本地运行
vercel dev
```

## 游戏规则

### 基础规则版
- 传统规则，策略明确
- 九宫格被占领后不能落子
- 适合新手玩家

### 进阶规则版  
- 九宫格被占领后仍可落子
- 更多策略可能性
- 适合高手玩家

## 技术栈

- **前端**：HTML5, CSS3, JavaScript (ES6+)
- **部署**：Vercel
- **数据库**：无（纯前端实现）

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 许可证

MIT License