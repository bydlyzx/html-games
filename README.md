# html-games

这是一个用来练习 **AI 辅助编程（AI Programming）** 的小项目：目录中包含 10 个“单文件（Single-file）”网页小游戏，主要使用原生 `HTML / CSS / JavaScript` 与 `Canvas` 实现。

This repository is a small practice project for **AI-assisted programming (AI Programming)**. It contains 10 single-file web mini-games, built mainly with vanilla `HTML / CSS / JavaScript` and `Canvas`.

## 快速开始 / Quick Start

- 推荐入口 / Recommended entry: `index.html`
- 也可以直接打开任意 `*.html` 单文件开始玩。

## 小游戏清单（10）/ Game List (10)

### 1) 经典坦克大战 / Tank Battle

- 入口 / Entry: `tank.html`
- 中文：经典街机坦克大战复刻。守护基地、击毁敌坦、可破坏砖墙；包含关卡推进、计分与连杀倍率（Combo）以及随机道具（护盾/加速/冻结/加固基地等）。
- English: A classic arcade Tank Battle remake. Defend the base, destroy enemy tanks, and break brick walls. Includes stages, score + combo multiplier, and power-ups (shield/speed/freeze/fortify, etc.).
- 操作 / Controls: `WASD` / 方向键移动，`Space` 开火；`Space` 也用于开始/重开。

### 2) 雷电风纵向射击 / Thunder Shooter (Vertical Shooter)

- 入口 / Entry: `thunder.html`
- 中文：雷电风纵向卷轴射击。鼠标平滑操控，自动连射；通过强化/副武器提升火力，包含 Boss 战与爆炸特效。
- English: A Raiden-style vertical scrolling shooter. Smooth mouse control with auto-fire, weapon upgrades/sub-weapons, boss fights, and explosion effects.
- 操作 / Controls: 鼠标移动控制机体；点击或 `Space` 使用 Bomb。

### 3) 雷电 2048 / THUNDER 2048: RAIDEN EDITION

- 入口 / Entry: `2048.html`
- 中文：把“2048”做成街机战斗版本：合成触发爆炸、能量槽蓄满可释放轰炸技能，支持连击加成与“时光倒流”类按钮。
- English: An arcade twist on 2048: merges trigger explosions, energy charges a bomb skill, combo bonuses reward chain merges, and an “undo/time rewind” style action is available.
- 操作 / Controls: 方向键移动；也支持鼠标/手指拖拽；能量满后按 `Space` 或点击技能按钮释放轰炸。

### 4) NEON BREAKER - 极光打砖块 / Neon Breaker (Brick Breaker)

- 入口 / Entry: `block.html`
- 中文：霓虹赛博风打砖块。控制挡板反弹光球，收集掉落增益（同时小心“病毒代码”类负面掉落），节奏偏爽快。
- English: A neon cyber-style brick breaker. Bounce the ball with the paddle, collect drops/power-ups (and avoid harmful ones), with fast-paced arcade feedback.
- 操作 / Controls: 鼠标移动控制挡板；点击发射/射击；`P` 或 `Esc` 暂停。

### 5) 霓虹贪吃蛇 / Neon Snake

- 入口 / Entry: `snake.html`
- 中文：霓虹风贪吃蛇，包含自适应布局、速度档位、穿墙模式等设置，以及 WebAudio 氛围音乐与音效。
- English: A modern neon Snake with adaptive layout, multiple speed presets, optional wall-wrapping mode, plus WebAudio ambient music and sound effects.
- 操作 / Controls: PC 使用方向键或 `WASD`；`Space` 开始/暂停；移动端在游戏区域轻扫切换方向。

### 6) 经典泡泡龙 / Puzzle Bobble (Bubble Shooter)

- 入口 / Entry: `dragon.html`
- 中文：经典泡泡龙/泡泡射手。瞄准发射泡泡，三消掉落；包含多关卡与特殊泡泡（如炸弹、彩虹、石头等），并带有“顶棚下落/压迫”机制。
- English: A classic Bubble Shooter / Puzzle Bobble. Aim and shoot bubbles to match and clear groups, with multiple levels and special bubbles (bomb/rainbow/stone), plus a ceiling-drop pressure mechanic.
- 操作 / Controls: 鼠标移动瞄准，点击发射；移动端滑动瞄准，松手发射。

### 7) 水果忍者 / Fruit Ninja (Slicing)

- 入口 / Entry: `fruit.html`
- 中文：切水果玩法：在屏幕上移动鼠标/手指进行“切割”，连击加分；包含特殊水果（冰冻/狂热/巨剑等）与炸弹惩罚机制。
- English: Fruit-slicing gameplay: move your mouse/finger to slash fruits, build combos for higher score, and watch out for bombs. Includes power-up fruits (freeze/frenzy/big blade, etc.).
- 操作 / Controls: 鼠标移动/按下或触摸滑动来切水果；不要碰炸弹。

### 8) 豪华版五子棋 / Gomoku Deluxe

- 入口 / Entry: `five.html`
- 中文：15×15 五子棋人机对战，黑棋先手。包含三档难度 AI（含 α–β 剪枝）、悔棋次数、皮肤与音效。
- English: 15×15 Gomoku (Black first) with Human vs AI. Includes three difficulty levels (with alpha–beta pruning), limited undo, skins, and sound effects.
- 操作 / Controls: 点击棋盘落子；可切换难度、悔棋与重新开始。

### 9) 豪华版中国象棋 / Chinese Chess (Xiangqi)

- 入口 / Entry: `chess.html`
- 中文：现代风格中国象棋人机对战。提供多档 AI 难度与多套主题皮肤，交互以“点击选子 → 点击落点”为主。
- English: A modern Xiangqi (Chinese Chess) game with AI opponents, multiple difficulty levels and themes. Interaction is click-to-select and click-to-move.
- 操作 / Controls: 鼠标点击选中棋子，再点击目标位置完成走子；可调整难度与主题。

### 10) 中英文单词消消乐 / English Vocabulary Matching

- 入口 / Entry: `card.html`
- 中文：寓教于乐的中英文单词配对消除。选择词库后生成卡片，点击英文会发音（Web Speech API），再匹配对应中文释义完成消除；适合背单词与短语。
- English: An educational EN–ZH vocabulary matching game. Pick a word bank, generate cards, click an English card to hear pronunciation (Web Speech API), then match its Chinese meaning to clear pairs.
- 操作 / Controls: 点击“开始/换一局”生成卡片；点击英文 → 再点对应中文进行配对。
