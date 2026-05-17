---
name: superpowers
description: Agentic development framework for planning, TDD, debugging, and coordination. Use when starting new features, fixing bugs, or managing complex development workflows.
---

# Superpowers: Agentic Development Framework

Superpowers provides disciplined workflows to ensure high-quality software development. When this skill is active, you must follow the appropriate workflow for your current task.

## Core Workflows

### 1. Planning & Brainstorming
**Use when:** Starting any new feature or significant change.
- Explore context first.
- Ask clarifying questions one at a time.
- Present a design and get user approval before writing any code.
- **Reference:** `skills/brainstorming/SKILL.md`

### 2. Test-Driven Development (TDD)
**Use when:** Implementing any code change.
- **The Iron Law:** No production code without a failing test first.
- Follow the Red-Green-Refactor cycle.
- **Reference:** `skills/test-driven-development/SKILL.md`

### 3. Systematic Debugging
**Use when:** Encountering bugs or test failures.
- **The Iron Law:** Find root cause before attempting fixes.
- Trace data flow and form hypotheses before changing code.
- **Reference:** `skills/systematic-debugging/SKILL.md`

### 4. Subagent-Driven Development
**Use when:** Executing complex plans with multiple independent tasks.
- Dispatch fresh subagents for each task to maintain clean context.
- Use two-stage reviews (spec compliance then code quality).
- **Reference:** `skills/subagent-driven-development/SKILL.md`

## How to Use
1. **Identify the task type** (Planning, Implementing, Debugging, or Coordinating).
2. **Invoke the corresponding sub-skill** by reading its `SKILL.md` from the `skills/` directory.
3. **Follow the instructions exactly.** Discipline is the key to Superpowers.

## Red Flags (Stop and Re-evaluate)
- Writing code before a design is approved.
- Writing code before a test fails.
- Proposing a fix before finding the root cause.
- Skipping the review process.
