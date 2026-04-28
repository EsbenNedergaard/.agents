# Agent Skills For Real Engineers

My agent skills that I use every day to do real engineering - not vibe coding.

## Skills

### Skills used for implementing a task
These skills aim for setting up agents that work across every phase of development.

```
  DEFINE         PLAN          BUILD         VERITY      REVIEW     
 ┌──────┐      ┌──────┐      ┌──────┐      ┌───────┐      ┌──────┐   
 │ Idea │ ───▶ │ Spec │ ───▶ │ Code │ ───▶ │ Test  │ ───▶ │  QA  │
 │Refine│      │  PRD │      │ Impl │      │ Debug │      │ Gate │   
 └──────┘      └──────┘      └──────┘      └───────┘      └──────┘   
```
| Step      | Skill                                      | Description                                                                                                                                            |
|-----------|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. Define | [grill-me](skills/grill-me/SKILL.md)       | First use `/grill-me` to flesh out the idea.                                                                                                           |
| 2.1. Plan | [to-prd](skills/to-prd/SKILL.md)           | Once there is shared understanding, use `/to-prd` to convert the conversation into a PRD GitHub issue (for smaller changes, use `/to-issues` directly) |
| 2.2. Plan | [to-issues](skills/to-issues/SKILL.md)     | Break the PRD GitHub issue into a series of smaller GitHub issues that can be worked on.                                                               |
| 3. Build  | [tdd](skills/tdd/SKILL.md)                 | Use TDD to implement a high-quality solution with a red-green-refactor loop.                                                                           |
| 4. Review | [code-review](skills/code-review/SKILL.md) | Review the changes made and ensure they are up to standard.                                                                                            |

### Other daily work
Skills I use daily for code work.

| Skill                                                                          | What It Does                                          | Use When                                                                            |
|--------------------------------------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------------------------------------|
| [improve-codebase-architecture](skills/improve-codebase-architecture/SKILL.md) | Looks for oppurtinies for improving code base         | Every so often to clean up code                                                     |
| [ubiquitous-language](skills/ubiquitous-language/SKILL.md)                     | Creates UBIQUITOUS_LANGUAGE.md with terms definitions | When entering new repo. This file is also great to be in when calling `/grill-me`   |


### Misc skills

General workflow tools, not code-specific.
- **[caveman](./skills/productivity/caveman/SKILL.md)** — Ultra-compressed communication mode. Cuts token usage ~75% by dropping filler while keeping full technical accuracy.
- **[git-guardrails-claude-code](./skills/misc/git-guardrails-claude-code/SKILL.md)** — Set up Claude Code hooks to block dangerous git commands (push, reset --hard, clean, etc.) before they execute.


## Installation

1. Copy the `/skills` & `/instructions` folders into your `%USER_PROFILE%/.agent` or `%USER_PROFILE%/.github` folder. 
2. Copy the `copilot-instrctions.md` into your global location for your IDE. This means they sho


## Sources:
https://github.com/mattpocock/skills/tree/main


https://github.com/github/awesome-copilot/blob/main/skills/java-springboot/SKILL.md





## TODO:
- Consider moving over to newest version of https://github.com/mattpocock/skills/tree/main where he added:
  - Context.MD setup and tasks that use this file 
  - Made the code not depend on using Github as backlog 
- Refactor TDD examples to use JAVA examples. 
- Refactor guard rails function to work with AI tool used at my workplace