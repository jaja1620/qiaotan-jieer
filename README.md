# 敲谈姐儿 · 办公室解压小游戏（单文件版） v1.0.0

> Qiaotan Jieer · Office Stress-Relief Game (Single-File Edition)

一个纯前端、零依赖、零安装的「打地鼠」式办公室解压小游戏。整个游戏（含全部美术素材、音效逻辑与彩蛋图片）压缩进 **单个 HTML 文件**，双击即可离线运行。

A pure front-end, zero-dependency, zero-install whack-a-mole style office stress-relief game. The entire game — all artwork, audio logic and the bonus picture — is packed into **one single HTML file**. Just double-click and play offline.

---

## 中文说明

### 文件清单

| 文件 | 说明 |
| --- | --- |
| `敲谈姐儿_单文件版.html` | 游戏本体，约 7.1 MB，含全部内嵌素材，离线可用 |

### 玩法

- **目标**：点击／敲击从洞口冒出来的人物头部得分。
- **连击**：连续命中触发连击倍率，连击越高分数越高。
- **过关**：共 **15 关**，达到当关目标分数即过关，场景自动切换到下一关。
- **掉命**：漏掉一个目标扣 1 条命，命数耗尽本局结束；结算页给出评级与统计数据。
- **干扰**：关卡越高越乱——黑鸟飞过头顶（打下来会砸在洞口挡住目标）、黑色炸弹（砸中 -1 条命）、绿色核弹（砸中全屏爆炸，直接失败）。
- **彩蛋**：打通 15 关有惊喜；困难与地狱难度通关后会出现「领取惊喜」入口。

### 难度

| 难度 | 节奏 | 初始命数 |
| --- | --- | --- |
| 轻松 | 慢慢冒头 | 6 条 |
| 普通 | 常规节奏 | 5 条 |
| 困难 | 快速连冒 | 4 条 |
| 地狱 | 手速考验 | 3 条 |

### 操作

| 操作 | 方式 |
| --- | --- |
| 敲击目标 | 鼠标左键点击 / 触屏点按 |
| 暂停 | 界面右上角暂停按钮 |
| 音乐 / 音效 | 界面右上角 `♪` / `🔊` 按钮，可独立开关 |
| 返回主菜单 | 结算页或暂停面板中的返回按钮 |

### 运行环境

- 任意现代浏览器：Chrome / Edge / Firefox / Safari 桌面版与移动版均可。
- **无需安装、无需联网、无需 Node.js 或 Python 等运行时**，不发起任何网络请求，不写入本地存储，无第三方库。
- 画面基于 Canvas 绘制（逻辑分辨率 1280 × 720），自动适配窗口缩放与高 DPI 屏幕，窗口尺寸变化时自动重排。

### 版本

- **1.0.0** — 首个发布版本：15 关卡流程、四档难度、连击计分、干扰物系统、结算记分牌、音乐音效开关、通关彩蛋（含内嵌彩蛋图片）。

---

## English

### What's inside

| File | Description |
| --- | --- |
| `敲谈姐儿_单文件版.html` | The whole game, ~7.1 MB, all assets embedded, works offline |

### Gameplay

- **Goal**: click / whack the character's head as it pops out of a hole to score.
- **Combos**: consecutive hits raise a combo multiplier — the longer the streak, the higher the score.
- **Progression**: **15 levels** in total. Reach the level's target score to advance; the scene switches automatically.
- **Lives**: missing a target costs 1 life. Run out of lives and the run ends; a scoreboard shows your rank and stats.
- **Hazards**: later levels get chaotic — a black bird flying overhead (knock it down and it blocks a hole), black bombs (hit one and you lose 1 life), and a green nuke (hit it and the screen explodes — instant failure).
- **Easter egg**: clear all 15 levels for a surprise; on Hard and Hell difficulties a "claim your surprise" entry appears after clearing.

### Difficulties

| Difficulty | Pace | Starting lives |
| --- | --- | --- |
| Easy (轻松) | Slow pops | 6 |
| Normal (普通) | Regular pace | 5 |
| Hard (困难) | Fast chains | 4 |
| Hell (地狱) | Reflex test | 3 |

### Controls

| Action | Input |
| --- | --- |
| Whack a target | Left mouse click / tap on touch screens |
| Pause | Pause button at the top-right of the HUD |
| Music / SFX | `♪` / `🔊` buttons at the top-right, toggled independently |
| Back to main menu | Button on the scoreboard or the pause panel |

### Requirements

- Any modern browser: Chrome / Edge / Firefox / Safari, desktop or mobile.
- **No installation, no internet, no Node.js or Python runtime required.** No network requests, no local storage writes, no third-party libraries.
- Rendered on a Canvas (logical resolution 1280 × 720) with automatic scaling for window resizing and high-DPI displays.

### Version

- **1.0.0** — First release: the full 15-level flow, four difficulties, combo scoring, hazard system, scoreboard, music/SFX toggles, and the clear-game easter egg (picture embedded).

---

## 使用提示 / Usage note

仓库根目录中的文件名为 `敲谈姐儿_单文件版.html`；Release 页面提供的下载附件为同一文件的 ASCII 命名版本 `qiaotan-jieer_v1.0.0.html`，两者内容与字节完全一致（SHA256 `ad87705d…9e76cfb`）。下载后直接双击即可开始游戏，无需解压或安装任何东西。

In the repository root the file is named `敲谈姐儿_单文件版.html`; the downloadable asset on the Release page is the same file under an ASCII name, `qiaotan-jieer_v1.0.0.html`. Both are byte-identical (SHA256 `ad87705d…9e76cfb`). After downloading, just double-click the HTML file to play — nothing to unzip or install.
