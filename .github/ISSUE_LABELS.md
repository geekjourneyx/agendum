# Issue Label Specification

Agendum uses labels to make the action queue machine-readable.

## Type

| Label | Meaning |
| --- | --- |
| action | A validated signal that requires a concrete next step |
| read | Deep reading |
| research | Research / investigation |
| experiment | Small experiment before commitment |
| build | Product / tool / open-source implementation |
| write | Article / long-form content |
| post | X post / social distribution |
| update | Website / README / existing project update |
| domain | Domain evaluation or acquisition |
| buy | Tool / service purchase |
| watch | Continue observing without commitment |

## Priority

| Label | Meaning |
| --- | --- |
| p0 | Act today |
| p1 | Worth doing this week |
| p2 | Useful backlog |

## Topic

| Label | Meaning |
| --- | --- |
| ai | AI / models |
| agent | Agent |
| harness | Agent Harness |
| opensource | Open source |
| product | Product / business opportunity |
| content | Content / distribution |
| website | Personal website |
| apple | Apple / iOS / Apple Watch |

## Status

GitHub's native open/closed state is the source of truth.

For work that needs finer-grained tracking, use the status field inside the Issue:

- TODO
- DOING
- BLOCKED
- DONE
- WATCHING
- DROPPED

## Labeling rule

Use:

**1 type + 1 priority + 0–3 topic labels**

Examples:

action + p1 + agent + harness

research + p1 + ai

experiment + p0 + product

Avoid adding labels merely for decoration.

## Title convention

[TYPE] YYYY-MM-DD · concise decision/action

Examples:

[RESEARCH] 2026-10-16 · Evaluate the new Agent Harness approach

[EXPERIMENT] 2026-10-16 · Test X bookmark into a 2-hour prototype

[WRITE] 2026-10-16 · Explain why Agent evaluation is shifting to Cost / Task

For P0/P1/P2, priority is represented by the label rather than duplicated in the title.