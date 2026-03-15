**English:** This repository contains two Claude Code skills for product UX research workflows. `product-interview-design` guides you through designing a product evaluation study from scratch — from research framing to participant briefing — using a phase-gated process that enforces the correct order of design decisions. `product-interview-analyst` guides you through systematic qualitative analysis of interview data, producing prioritized findings and mechanism-level propositions in a format ready for product and design teams. Both skills are built for commercial contexts where fast turnaround and actionable outputs are the primary constraints.

---

# UXR Skills

两个 Claude Code Skill，覆盖产品评测研究的设计与分析全流程。

## Skills

### [product-interview-design](product-interview-design/SKILL.md)

从零设计产品评测研究方案，或在执行前审查已有草案。

6 个阶段，逐步产出：研究框架 → 评估框架 → 参与者设计 → 任务与会话设计 → 访谈提纲 → 参与者指导语。

每个阶段需用户明确 approve 后才进入下一阶段，确保设计决策按正确顺序做出。

### [product-interview-analyst](product-interview-analyst/SKILL.md)

对产品评测访谈数据进行系统性定性分析。

4 个阶段：快速沉浸 → 指标对齐编码 → 模式解读 → 产品报告。

产出包含三层证据结构（数字层、原话层、机制层）的可落地报告，直接支持产品决策。

## 使用方式

将对应 Skill 目录复制到你的 Claude Code skills 路径，或在 Claude Code 中直接引用 `SKILL.md` 作为 system prompt 启动。

详细使用说明见各 Skill 的 `SKILL.md` 文件。

## 设计原则

两个 Skill 均遵循以下原则：

- **逐 phase 执行，用户 approve 后继续。** 分析和设计决策是累积的，顺序错误的决策会在后续阶段放大。
- **区分陈述与解读。** 用户原话是证据，分析结论是推断，两者不能混同。
- **矛盾是数据。** 受访者之间的分歧比任何单一数据点更有价值。
- **为商业场景而设计。** 快速周转，产出直接可用的报告，而非学术写作。
