# Project SPAC

A plain-English course on SPACs (special purpose acquisition companies), written in Markdown so people can read it and AI agents can use it as skills.

| Course | What you will learn | Reading time |
|---|---|---|
| [SPAC 101: History, Rules, Players and Deals](skills/spac-101/course.md) | What a SPAC is, why SPACs are back, history, key terms, the deal lifecycle, who does what, the rules, the money and real deals | About 60 minutes |
| [SPAC 102: What Happened After the Mergers](skills/spac-102/course.md) | How the 2020–22 deals turned out: the scorecard, the biggest collapses, the survivors, four case studies and a red-flag checklist | About 30 minutes |

Start with SPAC 101 if SPACs are new to you.

## Use the courses as agent skills

Each folder in `skills/` is an Agent Skill: a `SKILL.md` file that tells an agent what the course covers and when to use it, next to the full course.

- **Claude Code:** copy `skills/spac-101` and `skills/spac-102` into `~/.claude/skills/` (all your projects) or `.claude/skills/` (one project).
- **Claude apps:** zip a skill folder and upload it as a custom skill.
- **Other agents:** point the agent at the `SKILL.md` file.

## What's in the repo

```
skills/
  spac-101/
    SKILL.md     how and when an agent should use the course
    course.md    the full course
    images/      charts and diagrams
  spac-102/
    SKILL.md
    course.md
    images/
```

## About

Researched and written with Claude in November 2026. Every figure links to its source. Numbers change, so check the date before relying on one. This is education, not investment, legal or tax advice.
