---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 798659b1f59514cb753b383c1f423b09_6b3c16a7df2f11f1b140525400de85a5
    ReservedCode1: VrH09I0td+d1AZpgMjJtaXWrfYW5sjWf7+O3pWdEBQR9w4MIR+SWphFc/iCgYKenV6a4ZKIryfdY/UKaS82x9DCBiEwykeuteOBW9A8w/Q8hAw9VNosd/9QDWTKpvBK+dRSJ1fKSE4h1dcUF2Av6a7CuL62S63f4/l8cMV2poKIlMTcajQuhMs/Ajrg=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 798659b1f59514cb753b383c1f423b09_6b3c16a7df2f11f1b140525400de85a5
    ReservedCode2: VrH09I0td+d1AZpgMjJtaXWrfYW5sjWf7+O3pWdEBQR9w4MIR+SWphFc/iCgYKenV6a4ZKIryfdY/UKaS82x9DCBiEwykeuteOBW9A8w/Q8hAw9VNosd/9QDWTKpvBK+dRSJ1fKSE4h1dcUF2Av6a7CuL62S63f4/l8cMV2poKIlMTcajQuhMs/Ajrg=
---

# 敲谈姐儿 · 办公室解压小游戏（单文件版） v1.4.0

> Qiaotan Jieer · Office Stress-Relief Game (Single-File Edition)

一个纯前端、零依赖、零安装的「打地鼠」式办公室解压小游戏。整个游戏（含全部美术素材、音效逻辑与彩蛋图片）压缩进 **单个 HTML 文件**，双击即可离线运行。

A pure front-end, zero-dependency, zero-install whack-a-mole style office stress-relief game. The entire game — all artwork, audio logic and the bonus picture — is packed into **one single HTML file**. Just double-click and play offline.

---

## 中文说明

### 文件清单

| 文件 | 说明 |
| --- | --- |
| `敲谈姐儿_单文件版_v1.4.0.html` | 游戏本体，约 7.9 MB，含全部内嵌素材，离线可用 |

### 玩法

- **目标**：点击／敲击从洞口冒出来的人物头部得分。
- **连击**：连续命中触发连击倍率，连击越高分数越高。
- **过关**：关卡总数随难度变化——**轻松／普通 9 关、困难 12 关、地狱 15 关**；达到当关目标分数即过关，场景自动切换到下一关。
- **掉命**：漏掉一个目标扣 1 条命，命数耗尽本局结束；结算页给出评级与统计数据。
- **加命**：敲中金蛋 +1 条命、敲中彩蛋 +2 条命，加到的命会一直累计（轻松档无上限，普通上限 20、困难上限 12、地狱上限 10）；过关进入下一关时命数保留，仅在开始新局或「重玩本关」时回到该难度的初始命数。
- **干扰**：关卡越高越乱——黑鸟飞过头顶（打下来会砸在洞口挡住目标）、黑色炸弹（砸中 -1 条命）、绿色核弹（砸中全屏爆炸，直接失败）。
- **彩蛋**：打通当前难度的全部关卡（9～15 关）有惊喜；四档难度（含普通）通关后的彩蛋页均会出现「领取惊喜」入口，点击后进入全屏惊喜图片页（轻松／普通为冰棍儿惊喜图，困难／地狱为咖啡惊喜图），彩色纸屑自画面上方飘落，3 秒后出现「返回主菜单」按钮。

### 难度

| 难度 | 关卡数 | 节奏 | 初始命数 | 加命累计上限 |
| --- | --- | --- | --- | --- |
| 轻松 | 9 关 | 慢慢冒头 | 15 条 | 无上限 |
| 普通 | 9 关 | 常规节奏 | 10 条 | 20 条 |
| 困难 | 12 关 | 快速连冒 | 8 条 | 12 条 |
| 地狱 | 15 关 | 手速考验 | 6 条 | 10 条 |

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

- **1.4.0** — 初始生命值上调：轻松 6 → 15 条、普通 5 → 10 条、困难 4 → 8 条、地狱 3 → 6 条（加命累计上限不变：轻松无上限、普通 20、困难 12、地狱 10）；主菜单难度卡片与 HUD 生命显示同步更新；产物文件名统一附加版本标记。
- **1.3.0** — 关卡总数按难度拆分：轻松／普通各 9 关、困难 12 关、地狱 15 关（此前统一 15 关）；HUD 的「第 X / Y 关」与主菜单难度卡片同步显示各档关数，打满本难度全部关卡后进入彩蛋页，彩蛋页标语同步为「× 关全通」；玩法说明与彩蛋说明文案一并更新。
- **1.2.0** — 生命值规则调整：金蛋／彩蛋加到的命可一直累计，上限按难度区分（轻松无上限、普通 20、困难 12、地狱 10）；过关进入下一关时命数保留不再回满，仅新开一局或重玩本关时重置；HUD 生命值改为「♥ ×当前 / 上限」数字显示，并适配手机窄屏排布。
- **1.1.0** — 彩蛋升级：普通难度通关后的彩蛋页同样提供「领取惊喜」按钮；点击进入全屏惊喜图片页，彩色纸屑从画面上方持续飘落，3 秒后出现「返回主菜单」按钮；主菜单底部增加版本号标识。
- **1.0.0** — 首个发布版本：15 关卡流程、四档难度、连击计分、干扰物系统、结算记分牌、音乐音效开关、通关彩蛋（含内嵌彩蛋图片）。

---

## English

### What's inside

| File | Description |
| --- | --- |
| `敲谈姐儿_单文件版_v1.4.0.html` | The whole game, ~7.9 MB, all assets embedded, works offline |

### Gameplay

- **Goal**: click / whack the character's head as it pops out of a hole to score.
- **Combos**: consecutive hits raise a combo multiplier — the longer the streak, the higher the score.
- **Progression**: the number of levels depends on difficulty — **9 on Easy/Normal, 12 on Hard, 15 on Hell**. Reach the level's target score to advance; the scene switches automatically.
- **Lives**: missing a target costs 1 life. Run out of lives and the run ends; a scoreboard shows your rank and stats.
- **Extra lives**: hitting a gold egg grants +1 life, a colour egg +2. Gained lives keep accumulating up to the difficulty cap (Easy: unlimited, Normal: 20, Hard: 12, Hell: 10). Lives carry over between levels; they only reset to the difficulty's starting value when you start a new run or replay the current level.
- **Hazards**: later levels get chaotic — a black bird flying overhead (knock it down and it blocks a hole), black bombs (hit one and you lose 1 life), and a green nuke (hit it and the screen explodes — instant failure).
- **Easter egg**: clear every level of the current difficulty (9–15 levels) for a surprise; every difficulty (including Normal) shows a "claim your surprise" button on the clear screen, which opens the full-screen surprise picture (ice-lolly art on Easy/Normal, coffee art on Hard/Hell).

### Difficulties

| Difficulty | Levels | Pace | Starting lives | Extra-life cap |
| --- | --- | --- | --- | --- |
| Easy (轻松) | 9 | Slow pops | 15 | Unlimited |
| Normal (普通) | 9 | Regular pace | 10 | 20 |
| Hard (困难) | 12 | Fast chains | 8 | 12 |
| Hell (地狱) | 15 | Reflex test | 6 | 10 |

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

- **1.4.0** — Higher starting lives: Easy 6 → 15, Normal 5 → 10, Hard 4 → 8, Hell 3 → 6 (extra-life caps unchanged: Easy unlimited, Normal 20, Hard 12, Hell 10). Menu difficulty cards and the HUD life display updated; artefact filenames now carry a version tag.
- **1.3.0** — Level counts now vary by difficulty: 9 on Easy/Normal, 12 on Hard, 15 on Hell (previously a flat 15). The HUD "level X / Y" counter and the menu difficulty cards show each mode's total, and clearing every level of the current difficulty leads to the bonus screen, whose badge now reads "X levels cleared". Gameplay and bonus descriptions updated accordingly.
- **1.2.0** — Life rules reworked: extra lives from eggs accumulate up to a per-difficulty cap (Easy unlimited, Normal 20, Hard 12, Hell 10); lives persist across levels and only reset when a new run starts or the current level is replayed; the HUD now shows lives as "♥ ×current / cap" and fits narrow phone screens.
- **1.1.0** — Easter egg upgrade: Normal difficulty now shows the "claim your surprise" button too; tapping it opens a full-screen picture page where coloured confetti keeps falling from the top, and a "back to main menu" button appears after 3 seconds. The menu footer now shows the version number.
- **1.0.0** — First release: the full 15-level flow, four difficulties, combo scoring, hazard system, scoreboard, music/SFX toggles, and the clear-game easter egg (picture embedded).

---

## 使用提示 / Usage note

仓库根目录中的文件名为 `敲谈姐儿_单文件版_v1.4.0.html`；若从 Release 页面下载，附件为同一文件的 ASCII 命名版本 `qiaotan-jieer_v1.4.0.html`，两者内容与字节完全一致（当前单文件版 SHA256 `c274fae1…63e7c`）。下载后直接双击即可开始游戏，无需解压或安装任何东西。

In the repository root the file is named `敲谈姐儿_单文件版_v1.4.0.html`; if you download it from a Release page, the asset is the same file under an ASCII name, `qiaotan-jieer_v1.4.0.html`, byte-identical to it (current single-file SHA256 `c274fae1…63e7c`). After downloading, just double-click the HTML file to play — nothing to unzip or install.
*（内容由AI生成，仅供参考）*
