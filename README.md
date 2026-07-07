# interview-to-jtbd

Turn messy customer interviews into JTBD maps, opportunity areas, and product briefs — with evidence, not vibes.

## Overview

`interview-to-jtbd` is a universal agent skill for analyzing user interviews, research notes, and open-ended customer feedback. It helps an AI agent turn raw materials into an evidence-backed JTBD (Jobs to be Done) map, opportunity map, product brief, hypothesis backlog, and plan for subsequent interviews.

The core idea is not to build a separate SaaS or CLI as the main entry point, but to package the methodology into a portable skill that different AI agents can use: Claude Code, OpenAI Codex, Cursor, Gemini CLI, and any agent that can read `SKILL.md`-style instructions.

## Product Positioning

### Category
Agent Skill / AI research synthesis workflow.

### Target Audience
- Product managers doing their own discovery.
- Founders and indie hackers needing to quickly understand customers.
- AI builders who don't want to manually process interviews.
- UX researchers in small teams without budget for Dovetail/Marvin/Condens.
- Product bootcamps, students, product communities.

### Value Proposition
Enterprise research repositories solve the problem of centralized storage and teamwork. `interview-to-jtbd` solves a narrower problem: quickly and reproducibly turning a set of interviews into actionable product artifacts, while preserving the link between every conclusion and its evidence.

**Positioning Formula:** Dovetail-style research synthesis for AI agents and markdown-first teams.

## Market Context
While existing products (Dovetail, Marvin, Condens, Looppanel, Aurelius, Productboard) address broad enterprise/workspace scenarios, `interview-to-jtbd` fills the open niche:
- open-source
- skill-first
- markdown/file-first
- local/privacy-first
- no workspace, billing, onboarding, or SaaS account required
- focuses on JTBD, rather than general qualitative analysis.

## Methodology
Based on:
- JTBD: Users "hire" products to make progress in a specific situation.
- Outcome-Driven Innovation: Focus on job, desired outcomes, unmet needs, and opportunity areas.
- Human-in-the-loop: When using LLMs in qualitative research, human oversight, evidence grounding, and bias mitigation are crucial.

## Design Constraints
The skill is universal and does not depend on a specific AI platform.
- `SKILL.md` is the portable core.
- No `agents/openai.yaml` required in the core.
- Does not rely on OpenAI-only metadata.
- No app installation needed for basic usage.
- No Node/Python needed for basic usage.
- No API key required at the skill level (provider determined by the user's agent).
- Does not store interviews in a third-party service.
- AI synthesis is never presented as fact without evidence.

## Getting Started
Point your favorite AI agent (like Cursor, Claude Code, or an open-source CLI agent) to the `SKILL.md` file in this repository and ask it to analyze your research notes or interview transcripts.
