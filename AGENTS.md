# AGENTS.md

## Purpose

This box is an agnostic project template. `code/` contains the project; `context/` contains the information needed to explore and work on it. No language, technology, architecture, domain, or deployment approach is assumed.

## Project language

- Always write all content added to or changed in the project in English, regardless of the language used in the chat. This applies to documentation, code comments, identifiers, and other project files.

## Getting oriented

- Start with [`context/README.md`](context/README.md) and [`context/project.md`](context/project.md) to understand the project.
- To start or resume a guided definition, follow [`context/commands/box-start.md`](context/commands/box-start.md). To review the documents already defined, follow [`context/commands/box-review.md`](context/commands/box-review.md).
- Inspect the files in `code/` and any local instructions before proposing or making changes.
- Consult only the context documents relevant to the current work.
- Treat the profiles in `context/agents/` as input for the coordinator; the coordinator conducts the interview and consolidates questions and results.

## How to work

- Distinguish verified facts from hypotheses, proposals, and open questions. Label them when there could be confusion.
- Do not present a technology, architecture, or rule as decided unless the project has confirmed it.
- Keep `context/` consistent with the project: update affected documents when exploration or a change adds relevant information.
- Record significant decisions in `context/decisions/`, based on [`context/decisions/template.md`](context/decisions/template.md).
- Add more specific instructions in subdirectories only when there is a clear local need.
- Before destructive changes, external actions, or decisions with difficult-to-reverse effects, explain the impact and ask for authorization unless it has already been granted.

## Box structure

- `code/`: project code and artifacts. Its internal structure depends on the project.
- `context/`: project description, exploration, architecture, constraints, and decisions.
- This file: general guidance for working in any box. Project-specific rules should be documented once they are known.
