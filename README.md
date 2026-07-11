<div align="center">

# Kehan.skill

> _"融资是加速器，不是奖状。创始人自己，才是最早的产品。"_

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-blue)](https://github.com/FranklinNexus/kehan-skills)
[![Runtime](https://img.shields.io/badge/Runtime-Codex%20%7C%20Cursor%20%7C%20Claude%20%7C%20Antigravity-lightgrey)](https://github.com/FranklinNexus/kehan-skills)
[![Context](https://img.shields.io/badge/Context-China%20Early--Stage%20%7C%20AI%20Era-orange)](PRINCIPLES.md)

<p align="center">
  <img src="assets/kehan.jpg" alt="Kehan / 董科含" width="440" />
</p>

<br>

**董科含 / Kehan 的早期创业陪跑操作系统。不是公众号摘录，是可执行的创始人教练框架。**

<br>

面向 **15–25 岁创始人 · 融资全流程 · 条款与控制感 · AI 时代执行节奏 · Coffee Chat 成长追踪**，  
封装为可安装 Skill：能拆证据、点瓶颈、给 7 天动作，而不是灌鸡汤。

[两大场景](#为什么你需要-kehan-skill) · [看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [FAQ](#faq)

</div>

---

## 为什么你需要 Kehan skill

约董科含 coffee chat 很有价值，但不是所有问题都适合占用对方时间，也不是所有话都适合当面说出口。

### 1. 效率：不必事事约人聊

- **融资节奏、pitch 结构、投资人反馈归类、term sheet 红线**——很多可以在见面前用 Skill 先跑一轮，带着更好的问题去聊。
- **Office hour 记录**可整理成「承诺 + 指标 + 下次证据」，减少重复叙述、提高每次对话的信息密度。
- AI 时代构建变快，瓶颈往往在**判断与结构**；Skill 把「该问什么、缺什么证据」前置，节省双方时间。

### 2. 隐秘性：有些话不必让对方知道

- 你还在犹豫要不要退学、要不要融这一轮、某条条款会不会架空你——这些不一定适合在第一次 coffee chat 里和盘托出。
- 用 Skill 先在本地厘清：**真实瓶颈、可逆选项、最坏情况**，再决定见谁、说什么、暴露多少。
- 蒸馏包**不含原文重建、不含私域路径**（见 [`SOURCE_POLICY.md`](SOURCE_POLICY.md)），适合作为你自己的思考沙盒，而不是代替真人关系。

> Skill 是教练框架，不是董科含本人，也不替代律师/投资决策。重要节点仍建议真人 + 专业人士。

---

<div align="center">

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [边界说明](#边界说明) · [FAQ](#faq)

</div>

---

## 效果示例

### 问：我 19 岁，有个 AI 项目，想下个月退学全职创业。该不该？

```
Kehan 式判断 ❯  先别用「退学」当英雄叙事，用证据当决策。

              你需要回答的不是「我有没有勇气」，
              而是三件事：
              1）过去 60 天有没有不可辩驳的进展（用户、demo、拒绝记录）
              2）退学后 runway 与可逆路径是什么
              3）如果项目失败，你能否在 12 个月内回到可接受轨道

              融资、退学、gap year 都是不可逆或高成本选项。
              先做一个 30 天 reversible experiment：
              每周交付一个可被外部验证的 artifact，
              再决定要不要把人生开关拨到「不可逆」。

              热情不是缺点。没有证据就 all in，才是。
```

### 问：投资人总说「很喜欢我们」，但就是不投。什么意思？

```
Kehan 式判断 ❯  礼貌喜欢 ≈ 没有 commitment。

              真正的信号是：约第二次会、要数据、见合伙人、
              给 term sheet、或明确说「为什么现在不行」。

              把投资人反馈分成三桶：
              - 故事不清楚
              - 证据太弱
              - 阶段/赛道/基金周期不匹配

              不要继续在错的人身上求认同。
              本周任务：复盘最近 10 次对话，
              每次只留一句「对方要的下一个具体动作」，
              没有动作的，归档为 no。
```

### 问：我们有三份 coffee chat 记录，怎么整理成有用的成长档案？

```
Kehan 式判断 ❯  档案不是日记，是下次干预的地图。

              每次记录必须拆成五块：
              1. 观察：这次聊完发生了什么变化？
              2. 证据：真实世界多了什么 artifact？
              3. 解读：这说明创始人在哪条曲线上？
              4. 承诺：下次见面前要交付什么？
              5. 指标：什么数字/产物能证明做到了？

              追踪曲线建议固定五项：
              CEO 表达 · 产品认知 · 团队节奏 · 融资准备 · 用户/社群信号

              如果连续两次只有「很有热情」没有新证据，
              下一次就要直接问：你承诺的东西为什么没有发生？
```

> 不扮演董科含本人。调用的是**中国早期语境**下的融资、陪跑、年轻人判断与执行纪律。

---

## 安装

### Codex（推荐）

让 Codex 直接从 GitHub 安装本仓库中的 skill，或在克隆后运行：

```powershell
.\scripts\install.ps1 -Platform codex
```

安装目标为 `~/.codex/skills/`。重启 Codex 后生效。

### 其他 Agent Runtime

```powershell
git clone https://github.com/FranklinNexus/kehan-skills.git
cd kehan-skills
.\scripts\install.ps1 -Platform cursor
```

| 目标 | 命令 |
| --- | --- |
| Claude Code | `.\scripts\install.ps1 -Platform claude` |
| 项目 Antigravity | `.\scripts\install.ps1 -Platform antigravity -Scope project -ProjectPath "你的项目路径"` |
| 全平台 | `.\scripts\install.ps1 -Platform all` |

手动路径：`~/.cursor/skills/kehan/` · `~/.claude/skills/kehan/` · `.agents/skills/kehan.md`

### 使用

```
> 用董科含 / Kehan 的视角帮我看这轮融资节奏
> 帮我 review 这份 term sheet 对创始人的风险
> 我是大二学生，这个方向该不该现在 all in？
> 把这三份 office hour 记录整理成成长追踪档案
```

显式触发：`董科含` · `董柯含` · `Kehan` · `N1` · `奇绩` · `融资` · `pitch` · `年轻创始人`

---

## 蒸馏了什么

### 7 条核心原则

| 原则 | 一句话 |
| --- | --- |
| **融资是工具** | 为加速真实机会而融，不为证明自己而融 |
| **创始人即产品** | 使命感、学习率、可信度、动量先于 PPT |
| **赞美要落地** | 投资人夸奖直到「下一步行动」才算数 |
| **条款 > 估值** | 控制权、清算优先、对赌比 headline 更致命 |
| **安全激进** | 可逆实验在前，不可逆人生赌注在后 |
| **AI 时代** | 构建变便宜，判断、分发、结构更重要 |
| **对话要追踪** | Coffee chat 必须变成承诺 + 指标 + 复盘 |

### 覆盖场景

- 年轻创始人评估与教练
- 融资策略、pitch、投资人 pipeline、拒绝分析
- Term sheet 商业含义与控制权红线（非法律意见）
- AI 时代快速验证与执行
- N1 / 奇绩语境下的网络与陪跑
- Office hour / coffee chat **成长追踪**

### 输出形态

```markdown
### 董科含式判断
[直接诊断]

### 最关键的问题
[一个瓶颈]

### 证据缺口
- [...]

### 本周动作
- [...]
```

详见 [`skills/kehan/PLAYBOOK.md`](skills/kehan/PLAYBOOK.md) · [`EVALUATION.md`](EVALUATION.md)

---

## 仓库结构

```text
kehan-skills/
├── skills/kehan/
│   ├── SKILL.md
│   └── PLAYBOOK.md
├── PRINCIPLES.md
├── scripts/install.ps1
└── ...
```

---

## FAQ

### 这和董科含本人是什么关系？

Skill 是**蒸馏后的教练框架**，用于帮你思考与准备对话，**不是**董科含官方账号，也不代表他的投资建议。

---

## 边界说明

- 蒸馏行为框架，**非原文库**，不含私域路径、私人联络信息、长文引用。
- **不扮演董科含**，不提供投资/法律/税务意见；条款问题请找专业律师。
- 见 [`SOURCE_POLICY.md`](SOURCE_POLICY.md)

---

<div align="center">

**给年轻创始人的不是更多焦虑，而是一套能拆证据、保控制权、把对话变成进展的教练系统。**

</div>
