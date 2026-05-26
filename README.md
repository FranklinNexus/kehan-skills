<div align="center">

# Kehan.skill

> _"融资是加速器，不是奖状。创始人自己，才是最早的产品。"_

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-blue)](https://github.com/FranklinNexus/kehan-skills)
[![Runtime](https://img.shields.io/badge/Runtime-Cursor%20%7C%20Claude%20%7C%20Antigravity-lightgrey)](https://github.com/FranklinNexus/kehan-skills)
[![Context](https://img.shields.io/badge/Context-China%20Early--Stage%20%7C%20AI%20Era-orange)](PRINCIPLES.md)

<br>

**董科含 / Kehan 的早期创业陪跑操作系统。不是公众号摘录，是可执行的创始人教练框架。**

<br>

面向 **15–25 岁创始人 · 融资全流程 · 条款与控制感 · AI 时代执行节奏 · Coffee Chat 成长追踪**，  
封装为可安装 Skill：能拆证据、点瓶颈、给 7 天动作，而不是灌鸡汤。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [边界说明](#边界说明)

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

## 同源系列

| Skill | 领域 | 仓库 |
| --- | --- | --- |
| **Kehan.skill** | 融资 · 年轻创始人 · 陪跑 | **本仓库** |
| **PG.skill** | 创业想法 · 写作 · Maker | [paul-graham-skills](https://github.com/FranklinNexus/paul-graham-skills) |
| **Sam.skill** | 野心 · 复利 · AI 战略 | [sam-altman-skills](https://github.com/FranklinNexus/sam-altman-skills) |
| **ZYM.skill** | 用户价值 · 组织 · 长期执行 | [zhang-yiming-skills](https://github.com/FranklinNexus/zhang-yiming-skills) |

---

## 边界说明

- 蒸馏行为框架，**非原文库**，不含私域路径、联系方式、长文引用。
- **不扮演董科含**，不提供投资/法律/税务意见；条款问题请找专业律师。
- 见 [`SOURCE_POLICY.md`](SOURCE_POLICY.md)

---

<div align="center">

**给年轻创始人的不是更多焦虑，而是一套能拆证据、保控制权、把对话变成进展的教练系统。**

</div>
