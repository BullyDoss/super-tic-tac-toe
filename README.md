# 超级九宫格游戏 (Super Tic Tac Toe)

基于 HTML5、CSS3 和 JavaScript 开发的双人对战策略游戏。

## 游戏特色

- **双版本支持**：基础版与进阶版两种规则模式
- **九宫格嵌套**：9 个小九宫格决定大九宫格的落子位置
- **响应式设计**：适配手机、平板和桌面端设备
- **极简部署**：纯前端实现，无需后端或数据库

## 快速开始

直接用浏览器打开即可运行：

```bash
# 方式一：双击文件打开
index.html

# 方式二：命令行启动
start index.html  # Windows
open index.html   # macOS
```

## 游戏规则

### 通用规则

- 游戏目标：在胜负九宫格中在横、竖、斜方向先连成三子的玩家获胜
- 游戏布局：有 9 个普通九宫格和 1 个胜负九宫格
- 每个普通九宫格对应胜负九宫格的一个位置
- 玩家轮流在普通九宫格中落子
- 在一个普通九宫格中连成三子，则该九宫格归该玩家所有
- 胜负九宫格的对应位置会标记胜者
- 落子位置决定对方的下一个落子位置：在位置(row,col)落子 则对方必须在(row*3+col)号九宫格落子
- 若指定九宫格已满，可任意选择其他九宫格落子

### 基础版

**普通九宫格有胜者后，不能再在该九宫格中落子**

### 进阶版

**普通九宫格有胜者后，仍然可以在该九宫格的空位上落子**

### 游戏结束

- 胜负九宫格先连成三子的玩家获胜
- 所有九宫格已满且无胜者则平局

## 项目结构

```
SuperTicTacToe/
├── index.html    # 游戏主界面（完整实现）
├── .gitignore     # Git 忽略规则
└── README.md      # 项目说明文档
```

## 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 | 样式与响应式布局 |
| JavaScript ES6+ | 游戏逻辑与交互 |

## 浏览器兼容性

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 更多信息

如果还是不懂可以查看以下资源：

- 📖 **GitHub 项目**：[https://github.com/BullyDoss/super-tic-tac-toe](https://github.com/BullyDoss/super-tic-tac-toe)
- ✉️ **邮箱联系**：3041765943@qq.com
- 🎬 **视频教程**：[https://b23.tv/Je7VZOh](https://b23.tv/Je7VZOh)

## 在线体验

访问 GitHub Pages 即可在线游玩：
[https://bullydoss.github.io/super-tic-tac-toe](https://bullydoss.github.io/super-tic-tac-toe)
