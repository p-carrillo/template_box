# box-start — Define a project

Start or resume guided exploration of a box. This document defines the workflow; it can be adapted into commands callable by a specific agent or editor.

## Preparation

1. Read the applicable instructions, `context/README.md`, and existing context documents.
2. Inspect `code/` to identify any code, configuration, and documentation already available.
3. Do not overwrite confirmed decisions or ask again about questions that have already been answered. Distinguish observed facts, user responses, hypotheses, and proposals.
4. If the project already has materials, summarize the current state and ask what the person wants to continue with.

## Interview and brainstorming

1. Start with the problem, stakeholders, desired outcome, and main workflows. Ask conversationally, in small batches; prioritize questions that could change the scope or later decisions.
2. Use the profiles in `context/agents/` as specialists. Give each the same project summary and have it return relevant facts, assumptions, priority questions, and options worth considering. Specialists do not interview the user separately.
3. The coordinator removes duplicate questions, prioritizes those that unblock decisions, and asks no more than three questions per batch. Accept partial answers and record unknowns.
4. Explore architecture and constraints based on the domain information. Then begin technology selection with the technology and persistence profiles. Revisit the architecture if a technical choice changes system boundaries or workflows.
5. For each technology choice, compare up to three relevant options based on requirements, team skills, operations, cost, availability, and risks. When a recommendation depends on changing information, explain trade-offs and use current primary sources. Do not choose based on popularity.
6. Present decisions as proposals and record choices as confirmed only after the user accepts them. The user can choose an alternative, suggest another option, or leave the decision pending.

## Documents to maintain

- `context/project.md`: purpose, stakeholders, scope, main workflows, and success criteria.
- `context/exploration.md`: session summaries, confirmed findings, hypotheses, open questions, and next steps.
- `context/architecture.md`: boundaries, components, relationships, and confirmed technologies.
- `context/constraints.md`: supported constraints and requirements, including team experience, cost, and timeline.
- `context/coding.md`: derive development agreements from accepted technologies. Add commands only if configured or verified.
- `context/database.md`: derive the data and persistence strategy from known needs. If there is no persistence, document that it does not apply and why.
- `context/decisions/`: add a decision when alternatives have significant consequences. Do not record a mere recommendation as accepted.
- `AGENTS.md`: update the context index and project-specific rules when there is enough information; keep valid links and remove instructions that are still only template guidance.

Save useful progress between sessions. Do not fill pending sections with assumptions to make them look complete.

## Closing a session

Summarize what has been confirmed, what is proposed, what remains open, and the next question or task. If the person wants to continue, proceed with the highest-impact item; there is no need to complete every section in one session.
