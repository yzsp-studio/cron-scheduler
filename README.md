<div align="center">

# 🎬 cron-scheduler

## 别再回「我会提醒你」——任务真被创建才算数
## Stop saying "I'll remind you": a schedule only counts once it's really created

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

创建、查看、更新或删除定时任务，覆盖一次性提醒、周期任务、复杂日历规则和后台监控。核心原则是只调用当前环境里真实可用的定时工具：定时调用成功才算任务被创建，环境没有任何可用工具时明确说明，绝不假装已创建。支持多轮编辑已有任务；创建前先解析时间、锚定时间基准并澄清歧义，创建或更新后再校验下一次触发时间。适用于提醒、持续关注某个目标，以及按小时/日/周/月/年运行和管理任务。

### ✨ 能做什么

- 一次性提醒、周期任务、复杂日历规则，一句话创建
- 定时工具调用成功才算创建，没有可用工具时如实说明
- 创建前解析时间、锚定基准，歧义澄清后才落任务
- 创建或更新后校验下一次触发时间
- 查看、更新、删除与多轮编辑已有任务
- 后台监控任务持续跟踪某个目标

### 📦 包含的技能

- `cron-scheduler` —— 见 [`cron-scheduler/SKILL.md`](cron-scheduler/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/cron-scheduler.git
cp -r cron-scheduler/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

Creates, lists, updates and deletes scheduled tasks: one-off reminders, recurring runs, complex calendar rules and background monitoring. The rule is simple — only scheduling tools that actually exist in the current environment are called, and a task counts as created only when the scheduling call succeeds. If no such tool is available, it says so instead of pretending. Time expressions get parsed, anchored and de-ambiguated before any write, and every create or update is followed by a check of the next fire time. Handy for reminders, ongoing watch targets, and running or managing hour/day/week/month/year jobs.

### ✨ What it does

- One-off reminders, recurring jobs and complex calendar rules from one sentence
- Only reports success when the scheduling call really returns
- Parses and anchors times, clearing ambiguity before creating anything
- Verifies the next fire time after every create or update
- Lists, edits, updates and deletes existing jobs across multiple rounds
- Background monitors keep watching a target over time

### 📦 Skills included

- `cron-scheduler` — [`cron-scheduler/SKILL.md`](cron-scheduler/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/cron-scheduler.git
cp -r cron-scheduler/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
