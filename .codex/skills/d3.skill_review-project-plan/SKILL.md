---
name: d3.skill_review-project-plan
description: Review an early-stage project topic, concept, brief, plan, proposal, product idea, research plan, implementation plan, or schedule for missing pieces, weak assumptions, unrealistic scope, timeline risk, unclear success criteria, dependency risk, and concrete improvements. Use when Codex is asked to critique or strengthen a project before execution, especially at the planning or proposal stage.
---

# Review Project Plan

## Purpose

Use this skill as an early project planning reviewer. Given a topic, brief, plan, schedule, or AI-generated proposal, identify what is missing, what is risky, what is unrealistic, and what should be clarified or changed before execution.

## Review Posture

- Be constructive but critical. Do not merely praise the plan.
- Prioritize issues that can cause failure, rework, missed deadlines, wrong scope, or unclear outcomes.
- Treat missing information as a finding when it blocks reliable judgment.
- Distinguish evidence from inference. Label assumptions explicitly.
- Do not invent unavailable facts to make the plan seem complete.
- Recommend smaller scope, staged delivery, or validation steps when the plan is too broad for the stated time or resources.

## Review Workflow

1. Identify the stated project goal, deliverables, timeline, audience, resources, and constraints.
2. Mark unknowns that materially affect feasibility.
3. Evaluate the plan across the review dimensions below.
4. Rank findings by severity:
   - Critical: likely to make the project fail or miss the deadline.
   - High: likely to cause major rework, scope drift, or quality loss.
   - Medium: should be clarified or improved before execution.
   - Low: useful polish or optional improvement.
5. Provide concrete fixes, not only diagnoses.
6. End with the next 3 to 5 actions the user should take.

## Review Dimensions

- Goal clarity: Is the problem, purpose, or target outcome clear?
- User or audience: Is it clear who the project is for and what they need?
- Success criteria: Are there measurable or observable completion standards?
- Scope: Are inclusions, exclusions, and non-goals defined?
- Deliverables: Are outputs specific enough to build, write, present, or evaluate?
- Timeline: Do tasks fit the schedule with buffer for review, testing, iteration, and delays?
- Dependencies: Are required tools, data, people, approvals, assets, APIs, or decisions identified?
- Assumptions: Which assumptions are untested, fragile, or hidden?
- Risk: What could block progress or invalidate the plan?
- Sequencing: Are tasks ordered so prerequisites happen before dependent work?
- Validation: Is there a way to test the idea early before full execution?
- Maintenance or handoff: If relevant, is ownership after delivery clear?

## Timeline Feasibility Checks

When a schedule is provided, check for:

- tasks with no duration estimate
- parallel work that likely requires the same person
- missing research, design, implementation, review, testing, deployment, or presentation time
- no contingency buffer
- dependencies scheduled after the work that needs them
- deliverables too large for the available time
- milestones that are descriptions rather than verifiable outputs

If the schedule appears unrealistic, explain why and propose a smaller feasible version.

## Output Format

Use this structure unless the user asks for another format:

1. Summary judgment: State whether the plan is ready, needs revision, or is not feasible as written.
2. Top findings: List the most important issues first, each with severity, issue, evidence or inference, and fix.
3. Missing pieces: Name information that must be added or clarified.
4. Timeline and scope check: State whether the schedule and scope match; propose cuts or sequencing changes if needed.
5. Recommended next actions: Give 3 to 5 concrete next steps.

## Question Rule

If the input is too thin to review responsibly, ask for the minimum missing information instead of fabricating a full review. Prefer asking for:

- desired outcome
- deadline or available time
- expected deliverables
- target audience or user
- available resources and constraints

Ask no more than three questions at once unless the user explicitly wants a full intake checklist.
