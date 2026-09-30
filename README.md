# 你的世界

方块建造小游戏。程序生成世界，包含主世界、下界和末地，支持键鼠和触屏，适合 iPad 游玩。

## 在线体验

GitHub Pages: `https://yefei404.github.io/your-world/`

## 功能特性

- **新的世界**：可填写种子，留空则随机生成
- **三个维度**：主世界、下界、末地
- **建造与探索**：挖掘、放置、背包、成就和模组商店
- **键鼠 / 触屏**：左侧拖动移动，右侧拖动转视角
- **iPad 桌面图标**：Safari「添加到主屏幕」显示角色图标，标题为「你的世界」

## 项目结构

```
your-world/
├── index.html      # 单文件应用（HTML + CSS + JS + Three.js）
├── logo.png        # 标题画面角色
├── icon.png        # iPad 主屏幕图标
└── README.md
```

## 本地运行

```bash
open index.html
# 或使用静态服务器
npx serve .
```

## 部署

1. 在 GitHub 创建仓库 `yefei404/your-world`（Public）
2. push 到 `main` 分支
3. Settings → Pages → Source 选 `main` 分支、根目录 `/`

## License

MIT
