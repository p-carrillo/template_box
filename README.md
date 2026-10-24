# Box

A **box** is a directory structure for developing and exploring a project. It separates the space where the project lives (`code/`) from the context that explains what it is, what has been learned, and how to work on it (`context/`).

A box is agnostic about language, technology, and project type. It does not define an architecture or an internal structure for `code/`.

## Structure

```text
.
├── AGENTS.md
├── README.md
├── code/
│   └── README.md
└── context/
    ├── README.md
    ├── project.md
    ├── exploration.md
    ├── architecture.md
    ├── constraints.md
    ├── coding.md
    ├── database.md
    ├── agents/
    ├── commands/
    └── decisions/
        └── template.md
```

## Starting a project

1. Describe its purpose, scope, and vocabulary in [`context/project.md`](context/project.md).
2. Use [`context/exploration.md`](context/exploration.md) to record findings, hypotheses, and open questions.
3. Fill in the architecture and constraints as they become known; make anything that remains undecided explicit.
4. Record decisions that shape the project in `context/decisions/`.
5. Add the project's code and artifacts to `code/`, organized in whatever way makes sense for that project.

Start or resume the guided definition with [`context/commands/box-start.md`](context/commands/box-start.md), and review consistency with [`context/commands/box-review.md`](context/commands/box-review.md). Brainstorming profiles are in `context/agents/`.

See [`AGENTS.md`](AGENTS.md) for working guidelines and [`context/README.md`](context/README.md) for guidance on which document to use in each situation.
