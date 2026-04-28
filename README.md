# Agent Skills For Real Engineers

My agent skills that I use every day to do real engineering - not vibe coding.


## Skills used for implementing a task
These skills aim for setting up agents that work across every phase of development.

```
  DEFINE         PLAN          BUILD         VERITY      REVIEW     
 ┌──────┐      ┌──────┐      ┌──────┐      ┌───────┐      ┌──────┐   
 │ Idea │ ───▶ │ Spec │ ───▶ │ Code │ ───▶ │ Test  │ ───▶ │  QA  │
 │Refine│      │  PRD │      │ Impl │      │ Debug │      │ Gate │   
 └──────┘      └──────┘      └──────┘      └───────┘      └──────┘   
```
| Step      | Skill                         | Description                                                                                                                                            |
|-----------|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. Define | mattpocock/skills/grill-me    | First use `/grill-me` to flesh out the idea.                                                                                                           |
| 1.1. Plan | mattpocock/skills/to-prd      | Once there is shared understanding, use `/to-prd` to convert the conversation into a PRD GitHub issue (for smaller changes, use `/to-issues` directly) |
| 1.2. Plan | mattpocock/skills/to-issues   | Break the PRD GitHub issue into a series of smaller GitHub issues that can be worked on.                                                               |
| 3. Build  | mattpocock/skills/tdd         | Use TDD to implement a high-quality solution with a red-green-refactor loop.                                                                           |
| 4. Review | mattpocock/skills/code-review | Review the changes made and ensure they are up to standard.                                                                                            |

## Other daily work
