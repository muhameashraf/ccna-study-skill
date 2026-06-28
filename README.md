# 📡 CCNA 200-301 Study Skill for Claude

> **I built this skill because I believe AI should make studying smarter, not harder.**
> Instead of reading through hundreds of pages alone, this skill gives you an intelligent study partner that explains concepts, quizzes you, tracks your progress, and adapts to your level — all inside Claude.
> My goal is simple: help people study CCNA the right way, using AI as their personal tutor.

A Claude skill that turns any Cowork or Claude Desktop session into a structured **CCNA 200-301 exam study assistant** — covering all 6 official exam domains with quizzes, subnetting drills, IOS config walkthroughs, and personal progress tracking.

---

## ✨ Features

| Mode | Trigger | What You Get |
|------|---------|--------------|
| **Concept Explanation** | "explain OSPF" / "what is STP" | Definition + how it works + IOS config + practice question |
| **Quiz** | "quiz me on VLANs" / "test me" | MCQ questions (A–D), graded with explanations |
| **Subnetting Drill** | "subnet 192.168.1.0/27" | Full working: mask, wildcard, range, broadcast |
| **Config Walkthrough** | Paste any IOS config | Annotated lines, flagged errors, corrected config |
| **Cheat Sheet** | "compare OSPF vs EIGRP" | Markdown comparison table with exam angles |

---

## 📚 Exam Domains Covered

| # | Domain | Weight |
|---|--------|--------|
| 1 | Network Fundamentals | 20% |
| 2 | Network Access | 20% |
| 3 | IP Connectivity | 25% |
| 4 | IP Services | 10% |
| 5 | Security Fundamentals | 15% |
| 6 | Automation & Programmability | 10% |

---

## 📦 Installation

### Option 1 — Install `.skill` file (Recommended)
1. Download [`ccna-study.skill`](./ccna-study.skill)
2. Open **Claude Desktop** → **Cowork**
3. Drag and drop `ccna-study.skill` into the Cowork window
4. The skill is now active — start studying!

### Option 2 — Manual install
1. Download [`SKILL.md`](./SKILL.md)
2. Place it at:
   ```
   /mnt/skills/user/ccna-study/SKILL.md
   ```
3. Restart Claude Desktop / Cowork

---

## 🚀 Example Prompts

```
Quiz me on OSPF neighbor states
Explain VLANs and trunking
Subnet 10.0.0.0/22 — show full working
Review this config: [paste IOS output]
Cheat sheet for STP port states
What is the difference between RADIUS and TACACS+
Give me 10 practice questions on ACLs
What ports does DNS use?
```

---

## 📊 Personal Progress Tracking

The skill includes a **21-topic progress tracker** across all 6 domains.

At the start of each session Claude will show your current progress and ask what to study next.

Status legend:
- ⬜ Not started
- 🔄 In progress  
- ✅ Done
- ❗ Needs review

---

## 🧠 Study Tips Baked In

- Every concept explanation ends with a practice question
- Quiz mode hides answers until you respond
- Subnetting always shows full step-by-step working
- IOS configs use proper `ios` syntax highlighting
- Each response is tagged with its exam domain and weight

---

## 📁 Repo Structure

```
ccna-study-skill/
├── README.md          — this file
├── SKILL.md           — raw skill (readable on GitHub)
└── ccna-study.skill   — installable package for Claude Desktop / Cowork
```

---

## 🎯 Exam Info

- **Exam code:** 200-301 CCNA
- **Duration:** 120 minutes
- **Questions:** 100–120
- **Passing score:** ~825 / 1000
- **Question types:** MCQ, drag-and-drop, fill-in-blank, sim/simlet

---

## 👤 Author

**Muhamed Ashraf** — Mechatronics Engineer  
[github.com/muhameashraf](https://github.com/muhameashraf)

---

## 📄 License

MIT — free to use, modify, and share.
