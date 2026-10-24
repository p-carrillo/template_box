# box-review — Review the project definition

Review whether the project definition and documents are consistent, sufficient for the next step, and faithful to the decisions made.

## Review scope

1. Read `AGENTS.md` and the documents in `context/`. Also inspect files in `code/` that may confirm or contradict the documentation.
2. Check that the purpose, stakeholders, workflows, and success criteria are connected.
3. Look for contradictions among architecture, constraints, technologies, `coding.md`, and `database.md`.
4. Check that choices marked as confirmed are supported by the conversation or a project source; distinguish proposals from accepted decisions.
5. Identify assumptions presented as facts, questions that block important decisions, and outdated documentation.
6. If a technology recommendation depends on current versions, support, compatibility, or price, verify those details with primary sources and link to them.

## Result

Return:

- **Overall status:** ready to proceed, proceed with open questions, or needs clarification.
- **Contradictions:** link to the affected documents.
- **Technical decisions:** confirmed choices, proposals, and pending items.
- **Priority questions:** up to five, ordered by impact.
- **Suggested documentation changes:** specific changes tied to evidence.

Do not turn a recommendation into an accepted decision. You may correct clear link errors or synchronize documents with confirmed information; present any new choice to the user as a proposal.
