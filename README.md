# 🛡 坦克大战 · Tank Battle

一个用纯 **HTML + Canvas + JavaScript** 编写的经典坦克大战（Battle City）网页游戏。单文件 `index.html`，无需任何依赖，双击即可游玩。

## 运行方式

直接用浏览器打开 `index.html` 即可，也可以启动一个本地服务器：

```bash
# 任选其一
npx serve .
python -m http.server 8000
```

然后访问 http://localhost:8000 。

## 玩法

- **移动**：方向键 `↑ ↓ ← →` 或 `WASD`
- **射击**：空格键
- **暂停**：`P`
- **静音**：`M`

目标：消灭每一关的所有敌方坦克，同时**保护屏幕底部的基地（星形徽标）**。基地被摧毁或生命耗尽即游戏结束。

## 特性

- 经典网格地图，含 **砖墙**（可摧毁）、**钢墙**（不可摧毁）、**河水**（阻挡）、**草丛**（可隐藏坦克）
- 敌人自动刷新、追击玩家、随机游走与开火
- 计分、生命、关卡、难度递增（关卡越高敌人越多、速度越快）
- 出生护盾、爆炸粒子特效、WebAudio 音效
- 支持键盘与按钮操作，响应式界面

## 技术栈

- 原生 JavaScript（ES6）
- HTML5 Canvas 2D 渲染
- Web Audio API 音效
- 无任何第三方库

## 文件结构

```
tank-battle/
├── index.html   # 游戏全部代码（HTML + CSS + JS）
└── README.md
```

## 许可

MIT License
