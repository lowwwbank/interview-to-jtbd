# Demo Output: Customer Research Synthesis

This is a synthetic example showing the expected output style for `interview-to-jtbd`.

## Input Excerpt

> "I keep interview notes in three docs, then spend Friday copying quotes into a spreadsheet. By the time I write the roadmap update, I am not sure which quote supports which decision."

> "The hardest part is not the interview itself. It is turning a messy conversation into something the team can trust. If I cannot show the evidence, people just treat it as my opinion."

## JTBD Map

### Job: Trace research evidence to product decisions

**Statement:** When I prepare a roadmap or product brief after customer interviews, I want to connect each decision to the exact evidence behind it, so I can defend priorities without manually rebuilding the research trail.

**Evidence:**
- > "I am not sure which quote supports which decision."
- > "If I cannot show the evidence, people just treat it as my opinion."

**Current workaround:** Manually copying quotes from documents into a spreadsheet before writing product updates.

**Confidence:** Medium. The evidence is directionally strong, but this example uses only two short excerpts.

## Opportunity Map

### Opportunity: Make synthesis traceable by default

**Related job:** Trace research evidence to product decisions.

**Unmet need:** The user needs a faster way to preserve the link between raw interview data, interpreted insights, and product decisions.

**Severity:** High for teams where roadmap decisions are challenged by stakeholders.

**Evidence:**
- > "turning a messy conversation into something the team can trust"
- > "people just treat it as my opinion"

## Product Brief

### Problem

Product teams often lose traceability between interview notes and product decisions during synthesis. This makes roadmap updates weaker because stakeholders cannot easily inspect the evidence behind a recommendation.

### Target User

Product managers, founders, and UX researchers who conduct customer interviews but do not have a dedicated research operations workflow.

### Proposed Direction

An AI agent skill that transforms raw interviews into evidence-backed JTBD maps, opportunity areas, product briefs, and hypothesis backlogs while preserving source quotes.

### Non-Goals

- Replacing human research judgment.
- Acting as a full research repository.
- Inventing market size, frequency, or severity without source data.

## Hypothesis Backlog

### Hypothesis 1: Evidence tables reduce synthesis friction

**If we build:** An automatic evidence table linking each insight to source quotes.

**Then:** Product managers will write product briefs faster and with more confidence.

**We will know we are right when:** Users can explain why a priority exists by pointing to specific interview evidence.

**Risk:** The agent may over-cluster weakly related quotes unless the workflow forces uncertainty labels.

### Hypothesis 2: JTBD framing improves stakeholder alignment

**If we build:** A JTBD map that separates situation, motivation, desired outcome, workaround, and evidence.

**Then:** Teams will discuss customer progress instead of jumping straight to feature requests.

**We will know we are right when:** Product discussions reference jobs and unmet needs instead of isolated quotes.

**Risk:** JTBD statements may become too generic if the input transcripts lack context.

## Follow-Up Interview Guide

1. Walk me through the last time you turned interview notes into a roadmap update.
2. Where did evidence get lost or become hard to defend?
3. What artifacts did stakeholders ask for before they trusted your recommendation?
4. Which parts of synthesis felt mechanical, and which parts required judgment?
5. What would make an AI-generated research synthesis trustworthy enough to review?

## Risks and Unknowns

- The sample is too small to estimate frequency across a broader PM audience.
- The evidence points to traceability pain, but not yet to willingness to adopt a new workflow.
- The skill should be tested on longer transcripts with contradictions and mixed sentiment.
