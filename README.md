# project-explore-skill

A standalone Claude Code skill for explore mode — extracted from [OpenSpec](https://github.com/Fission-AI/OpenSpec).

## Installation

```bash
npx skills add bakabird/project-explore-skill@explore-in-project
```

## Why this exists

[OpenSpec](https://github.com/Fission-AI/OpenSpec) is a fantastic project. Its `explore` skill is one of the most thoughtfully designed thinking/comprehension aids, deep, adaptive, and genuinely helpful for understanding complex codebases.

But sometimes you just want the explore functionality. No other commands and skills of OpenSpec. You want `/explore-in-project`, enter, and start thinking through a problem with your codebase as context.

This skill extracts that core capability into a single, self-contained `SKILL.md`. No dependencies, no config beyond what you already have.

```
/explore-in-project real-time collaboration
/explore-in-project the auth system is getting unwieldy
/explore-in-project   # just enter, no topic
```

## Credit

The philosophy and structure of this skill are directly inspired by [OpenSpec](https://github.com/Fission-AI/OpenSpec) by Fission-AI. The idea of framing exploration as a distinct "mode" with guardrails — no implementation, think deeply, visualize — is their contribution. I just pulled out the piece I wanted.
