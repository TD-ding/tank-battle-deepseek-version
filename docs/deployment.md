# 部署指南 - 坦克大战 deepseek-version

## 环境要求

- 现代浏览器（Chrome / Firefox / Edge / Safari 最新版）
- 无需安装任何运行时或依赖

## 运行方式

### 方式一：直接打开（推荐）

用浏览器直接打开 `index.html` 文件即可开始游戏。

### 方式二：本地服务器

```bash
# Python 3
python3 -m http.server 8000

# Node.js (需要先安装 http-server)
npx http-server -p 8000
```

然后访问 `http://localhost:8000`。

### 方式三：部署到静态托管

将项目文件上传到任意静态文件托管服务：

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Nginx / Apache

只需提供 `index.html` 文件即可，无构建步骤。

## 项目文件

```
tank-battle-deepseek-version/
├── index.html       # 游戏主文件（自包含，无外部依赖）
├── docs/
│   └── deployment.md
└── README.md
```

## 操作说明

| 按键 | 功能 |
|------|------|
| ↑↓←→ / WASD | 移动坦克 |
| 空格 | 射击 |
| P | 暂停/继续 |
| R | 重新开始（游戏结束后） |
| Enter / 点击屏幕 | 开始游戏 |
