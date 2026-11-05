# Kin — AI Red Team & Reliable Delivery

**AI red team work and evidence-led delivery.** ARKX Grandmaster · multi-language engineering discipline · project-based delivery with an explicit Stage 0 boundary.

**AI 红队对抗 + 证据驱动交付。** ARKX Grandmaster · 多语言工程纪律 · 项目制合作，Stage 0 边界写清楚。

What I take on: adversarial assessments and vulnerability reports, document-to-structured-data pipelines, and custom Windows / Android builds.

接到手上的活：对抗性评估与漏洞报告、文档到结构化数据的流水线、Windows / Android 定制开发。

---

## Evidence, not adjectives / 先看证据

### ARKX CTF — GRANDMASTER, 7,200 points

24 / 24 challenges cleared across three tracks (Beginner 7, Advanced 9, Expert 8); the DEFCON track stands at 2 of 3 levels. The public portfolio carries a redacted write-up per vulnerability class: LLM prompt injection, path traversal / WAF bypass, YAML deserialization to RCE, TOCTOU race conditions, MCP resource enumeration, and auth-boundary escalation.

Engagements this maps to: adversarial assessment, red-team testing, and vulnerability reports that state the mechanism, the exploitation path and the fix — defensible line by line.

[Portfolio and write-ups →](https://github.com/kinsin818/red-team-ctf-portfolio)

### sendguard — one rule, six languages, one gate

A single frozen filename rule implemented independently in Go, TypeScript, Rust, Java, C# and Python, with a CI matrix on Windows, macOS and Ubuntu. The point is not the language count; it is the gate that decides whether the six ports return byte-identical verdicts.

Current reading: **RED** — 20 of the 44 required cells carry a verdict conflict, only 4 of the 44 have every field recorded, and field coverage is 2,281 / 2,640. The repository publishes the conflicts and the blanks cell by cell. A gate that can fail, and says so, is the deliverable.

[Repository and current reading →](https://github.com/kinsin818/sendguard)

---

## How I work / 合作方式

**You send** a written requirement and, if you have one, a UI mockup or design sketch. Text is enough to start.

**Stage 0 — free, one page.** I return a one-page build plan: scope, feature breakdown, milestones with time and price, the recommended stack (plus one alternative), and the top risks. It is yours to keep, with no obligation.

It stays at decision level: which stack, how many milestones, why this path. It is not a construction-grade specification, and the full blueprint is not part of the free page.

**After award.** The full implementation blueprint and the code start once the project is awarded. Work is paid per milestone, and the first milestone is a runnable walking skeleton of your core flow — not a slide deck.

**Boundaries.** Anything outside the agreed milestone is out of scope for that round and is priced and scheduled explicitly. Changes are written down before they are built.

**Communication.** Text-first and asynchronous, with acceptance criteria per milestone. One-person studio, AI-assisted and cross-checked — not a team, and the work is not outsourced.

---

## What the projects prove / 这些项目证明的能力

| Capability | Project | What it demonstrates |
|---|---|---|
| Data cleaning & quality control | [**AI Congress Online**](https://github.com/kinsin818/AI-Congress-Online) · [**DataSweeper**](https://github.com/kinsin818/datasweeper) · Data Master¹ | A live document-to-structured-data service (CSV / Excel / JSONL / PDF / Word, bring your own key); a Windows tool that finds dirty CSV rows before they are loaded, with a published benchmark; an on-device Android cleaning engine. |
| AI agent orchestration & local control | DoCom¹ · [**armory-rightclick**](https://github.com/kinsin818/armory-rightclick) | Task dispatch, status, interrupt and evidence collection against a local model gateway; a Windows shell entry point with a permission gate, context extraction, action routing and an evidence trail. |
| Desktop & mobile delivery | [**LaneFlow Free**](https://github.com/kinsin818/LaneFlow-Free) · LabelFlow¹ | Process-level traffic routing on Windows, MIT and downloadable; an offline Android app with zero permissions, shipped as a demonstration build. |
| Reproducible engineering discipline | [**sendguard**](https://github.com/kinsin818/sendguard) | Six independent ports of one spec, a gate that adjudicates them, and published readings — including the failures. |

¹ Private showcase repository — not linked publicly; a walkthrough (screen recording or screenshots) can be shared on request.
¹ 私有门面仓，不公开链接；可应要求提供演示录像或截图。

---

## Focus / 方向

- **AI agent orchestration** — multi-model coordination, task state machines, evidence-led delivery.
- **Reproducible engineering** — one spec, several implementations, a gate that can fail.
- **Privacy first** — local gateways, bring-your-own-key, on-device processing.

---

## Note

Showcase repos publish no application source code and no secrets; open-source repos carry real code and an explicit licence. Where a claim can be reproduced, the repository says how.

门面仓不公开应用源码与密钥；开源仓是真代码，并附带明确许可证。凡是能复现的说法，仓里都写了怎么复现。

*Updated 2026-11-05 · 更新于 2026-11-05*
