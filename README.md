# 🏎️ 卡丁车竞速游戏

> 基于 Unity 开发的 3D 卡丁车竞速游戏 | WebGL 即点即玩

[🎮 在线试玩](https://konodioda3939.itch.io/mykartinggame) 

---

## 📖 项目简介

这是一款使用 **Unity 2020.3 LTS** 开发的 3D 卡丁车竞速游戏。项目基于 Unity 官方 Karting Microgame 模板进行复现与深度优化，实现了车辆物理控制、AI 对手、道具系统等核心玩法，并成功部署至 WebGL 平台，支持浏览器即点即玩。

**开发时间**：2026.02 - 至今  
**开发引擎**：Unity 2020.3.49f1 LTS  
**部署平台**：[itch.io](https://konodioda3939.itch.io/mykartinggame)

---

## ✨ 功能特性

| 功能 | 描述 |
|------|------|
| 🎮 **车辆控制** | 基于 WheelCollider 的物理控制，支持加速、刹车、转向、漂移 |
| 🏁 **赛道系统** | 完整赛道设计，包含检查点、终点判定 |
| 📊 **游戏状态** | 开始菜单、游戏进行、胜利/失败结算界面 |
| 🌐 **WebGL 支持** | 包体优化至 15MB，支持网页即点即玩 |

---

## 🛠️ 技术栈

- **游戏引擎**: Unity 2020.3.49f1 LTS
- **编程语言**: C#
- **渲染管线**: URP (Universal Render Pipeline)
- **物理系统**: WheelCollider, Rigidbody
- **输入系统**: Unity Input System (New)
- **构建平台**: WebGL
- **版本控制**: Git, GitHub
- **部署平台**: itch.io

---

## 🎮 操作说明

### 键盘控制
| 按键 | 功能 |
|------|------|
| `W` / `↑` | 加速 |
| `S` / `↓` | 刹车/倒车 |
| `A` / `←` | 向左转向 |
| `D` / `→` | 向右转向 |
| `Space` | 漂移/手刹 |
| `R` | 重置车辆位置 |

## 📁 项目结构
MyKartingGame/
├── Assets/
│ ├── Karting/
│ │ ├── Scripts/
│ │ ├── Scenes/
│ │ ├── Prefabs/
│ │ ├── Materials/
│ │ └── Textures/
│ ├── Settings/
│ └── ...
├── Packages/
├── ProjectSettings/
├── .gitignore
└── README.md
### 安装步骤

```bash
# 1. 克隆仓库
git clone https://github.com/konodioda3939/MyKartingGame.git

# 2. 使用 Unity Hub 打开项目
# 选择项目文件夹，Unity 会自动导入资源

# 3. 打开场景
Assets/Karting/Scenes/MainScene.unity

# 4. 点击 Play 运行
