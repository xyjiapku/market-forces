# MARKET FORCES — A Firm's Journey

**A single-file classroom role-play game for teaching market structure.**
**一款用于课堂角色扮演的单文件游戏，教学「市场结构」板块。**

Play online / 在线游玩: **https://xyjiapku.github.io/market-forces/**

---

## English

### What it is

Students run their own small manufacturing firm and make the same decisions a real owner
makes — how many workers to hire, what price to charge, whether to advertise, whether to
collude — through four market structures in sequence. The point is not to win. The point is
to *feel* how differently a firm has to behave when the market around it changes.

Built for AP Microeconomics, IGCSE Economics 0455 and IB Economics, but the underlying
model is plain economics and needs no syllabus to enjoy.

### The four acts

The order is deliberate: meet the two extremes first, then the two realistic middle grounds.
Perfect competition teaches what it feels like to have no power at all; monopoly shows the
opposite with the same workshop and the same costs; monopolistic competition then takes the
protection away but keeps the differentiation; and oligopoly — which needs everything before
it — closes the game as a contest against a thinking rival.

| Act | Structure | What the student discovers |
|---|---|---|
| 1 | **Perfect competition** | Price is given. Profit is maximised where MC = P. Then free entry drives price down until economic profit is zero; free exit lets it recover. |
| 2 | **Monopoly** | A licence and a patent open the chapter. Barriers to entry, MR = MC, a profit rectangle, a deadweight-loss triangle, price discrimination — and **monopsony**: the same firm setting the town's wage rather than its price, paying workers less than they add, and destroying value from the other side of the market. Then a regulator's price cap. |
| 3 | **Monopolistic competition** | Differentiation buys a downward-sloping demand curve of your own — and imitation takes it away again. Advertising pays only when the margin covers it. |
| 4 | **Oligopoly** | Your best move depends on their move. A payoff matrix, a cartel offer, a regulator, and a prisoner's dilemma. |

### How a lesson runs

| Mode | Time | Content |
|---|---|---|
| Quick Round | 20–25 min | Perfect competition only, then the debrief |
| Standard | 40–50 min | Competition, market power, then product differentiation (the first three acts) |
| Full Campaign | 2 lessons | All four structures, ending in a strategic duel |

Each mode is simply the first *N* chapters of the one canonical order, so the sequence can never
drift out of step with the game.

### Tasks: one rule, no surprises

Every section of the game — each of the three lab tabs and every decision or question step in a
chapter — declares its tasks in a single registry. That one list drives three things that used to
disagree: what the side panel shows, whether the step may be left, and when Insight is awarded.
A task that is not in the registry cannot block progress; a task that is in it always does.
"Continue" is never greyed out — press it and the game tells you exactly what is still missing,
and in the factory it takes you to the tab that is blocking you.

The **task panel** sits in its own column on the right, deliberately apart from the data,
the simulation, the choices and the reports. It opens by itself the first time a section is
seen so the tasks get read, collapses to a small counter once the work is done or when a story
step has nothing to decide, and can be opened or closed by hand at any moment.

### Before the markets: the firm itself

The game deliberately starts *inside* the firm. The student tours the workshop, separates
**fixed factors** (land, capital) from **variable factors** (labour, raw materials), and then
spends a session in the **Cost Lab**:

- drag the workforce and watch total, marginal and average product — discovering diminishing
  marginal returns and the fact that MP cuts AP at AP's peak;
- watch AFC, AVC, AC and MC all move together, and find the output that minimises AC and the
  output that minimises AVC;
- set a market price and find the profit-maximising output, then test the shutdown rule.

Nine small missions in the lab each award **Insight points**, so a student can score poorly on
profit and still demonstrate that they understand the economics.

Each student plays alone on their own device. Everything is on one HTML page — no install,
no login, no network connection required once loaded.

### Scoring

- **Firm value** — cumulative economic profit across every decision. This is the main score.
- **Insight points** — earned for correct reasoning, not for good luck.
- Rank titles are scaled to the mode played, so a Quick Round is never compared unfairly with a
  Full Campaign.
- There is deliberately no single winning number: identical technology and identical costs
  produce wildly different outcomes, because students read the market differently. That
  comparison is the lesson.

### Debrief

The final screen shows the rank, where the money came from by chapter, a season-by-season
ledger, and **28 reflection questions** grouped by chapter with model answers — including
cross-market questions such as *"the same machine and the same workers earned nothing in
Chapter 1 and $1,466 in Chapter 4. Why?"*

A built-in **Teacher Guide** (Teacher button) contains the full numerical tables, the event-card
list, the syllabus mapping for AP / IGCSE / IB, and the common misconceptions to watch for.

### Technical

- One file, ~190 KB, no build step, no CDN, no external requests, no cookies, no data leaves
  the device. Save it and it works offline.
- All numbers come from one economics engine: a short-run production function
  `Q = 48KL² / (16K² + L²)`, a linear market demand `Q = 300 − 5P`, and the full cost curve set
  derived from them. Nothing is hard-coded twice.
- Charts are hand-drawn SVG.

### Credit

Designed and written by **Dr. Xiangyu Jia** (Changzhou Foreign Languages School Bilingual
Department) for classroom use. Feel free to use it in your own teaching.

---

## 中文

### 这是什么

学生扮演一家小型制造企业的老板，把一个真实企业主会做的决策都做一遍——雇几个工人、
定什么价、要不要打广告、要不要和对手联手——然后依次经历四种市场结构。
目的不是赢，而是**体会**市场环境一变，企业的活法就必须跟着变。

面向 AP 微观经济学、IGCSE 经济 0455 与 IB 经济，但底层模型就是普通经济学，不挑考纲。

### 四幕

顺序是刻意的：先走两个极端，再走两个现实中的中间地带。完全竞争让学生尝到完全没有议价权的滋味；
垄断用**同样的车间、同样的成本**给出反面；垄断竞争拿掉保护但保留差异化；寡头需要前面全部铺垫，
所以放在最后，用一场与"会思考的对手"的博弈收尾。

| 幕 | 市场结构 | 学生自己发现什么 |
|---|---|---|
| 1 | **完全竞争** | 价格是给定的。利润在 MC = P 处最大。随后自由进入把价格压到经济利润为零；自由退出又让价格回升。 |
| 2 | **垄断** | 一张独家执照 + 一项专利开场。进入壁垒、MR = MC、利润矩形、无谓损失三角、价格歧视——以及**买方垄断**：同一家企业不再定价而是定工资，付给工人的少于他们创造的价值，从市场的另一侧再次制造价值损失。最后是监管者的价格上限。 |
| 3 | **垄断竞争** | 差异化换来一条属于自己的向下倾斜需求曲线——然后被模仿者拿走。广告只有在边际利润覆盖成本时才划算。 |
| 4 | **寡头** | 你的最优选择取决于对手的选择。支付矩阵、卡特尔提议、监管者、囚徒困境。 |

### 课堂用法

| 模式 | 时长 | 内容 |
|---|---|---|
| 快速局 | 20–25 分钟 | 只做完全竞争，然后直接进入复盘 |
| 标准 | 40–50 分钟 | 竞争、市场势力，再到产品差异化（也就是前三幕） |
| 完整战役 | 2 课时 | 四种结构全做，收尾于一场策略博弈 |

每个模式都只是**唯一那一条章节顺序的前 N 章**，所以模式与章节顺序不可能走散。

### 任务：一套规则，没有意外

游戏里每一个板块——实验室的三个标签页，以及每一章里的每个决策或问答步骤——都在**同一个注册表**里
声明自己的任务。这一份清单同时决定三件事，而它们以前是会互相矛盾的：侧边面板显示什么、
这一步能不能离开、以及什么时候发 Insight 分。不在清单里的任务不可能卡住进度，
在清单里的任务一定会卡住进度。"继续"按钮**永远不会变灰**——点下去，游戏会明确告诉你还差什么；
在工厂里，它会直接把你带到卡住你的那个标签页。

**任务面板**独占右侧一列，刻意与数据、模拟、选择、报表分开。第一次进入某个板块时它会自动展开，
让玩家把任务读完；任务做完、或某个纯叙事步骤没有任务时，它会收成一张小卡片显示进度；
任何时候都可以手动展开或折叠。

实验室里 9 个小任务各奖励 **Insight 分**，所以一个学生可能利润做得不好，
但仍然能证明他懂经济学。

每人一台设备各自单人游戏。全部内容在一个 HTML 页面里——不用安装、不用登录，
加载完成后断网也能继续。

### 进市场之前：先认识自己的企业

游戏刻意从**企业内部**开始。学生先参观车间，把**固定要素**（土地、资本）与
**可变要素**（劳动、原材料）分开，然后在**成本实验室**里待一节课：

- 拖工人数看总产量、边际产量、平均产量——自己撞出边际报酬递减、以及 MP 切 AP 于 AP 最高点；
- 看 AFC、AVC、AC、MC 一起动，找出让 AC 最低、让 AVC 最低的产量；
- 给定一个市场价格，自己找到利润最大化产量，再检验停产规则。

实验室里 9 个小任务各奖励 **Insight 分**，所以一个学生可能利润做得不好，
但仍然能证明他懂经济学。

### 计分

- **企业价值**：所有决策的累计经济利润，这是主分。
- **Insight 分**：给正确的推理，不给运气。
- 评级阈值会随所玩模式缩放，快速局与完整战役不会被不公平地对比。
- 刻意**不设唯一的胜利数字**：同样的技术、同样的成本，结果天差地别，因为每个人对市场的判断不同——
  学生之间的这个对比本身才是教学重点。

### 复盘

结算页显示评级、各章利润来源、逐季流水账，以及按章分组的 **28 个反思问题**（附参考思路），
其中包括跨市场的追问，例如：*「同样的机器、同样的工人，第 1 章一文不赚、第 2 章赚 $1,466，为什么？」*

内置 **教师手册**（Teacher 按钮）：完整数值表、事件卡清单、AP / IGCSE / IB 考纲映射、常见误解提醒。

### 技术说明

- 单个文件约 190 KB，无构建、无 CDN、无外部请求、无 cookie，数据不离开本机。存下来断网可用。
- 全部数字来自同一个经济学引擎：短期生产函数 `Q = 48KL² / (16K² + L²)`、
  线性市场需求 `Q = 300 − 5P`，以及由它们推出的整套成本曲线。没有任何数字写两遍。
- 图表是手写 SVG。

### 署名

由**贾翔宇 博士**（常外双语高中部）为课堂教学设计与编写。欢迎在自己的课堂上使用。
