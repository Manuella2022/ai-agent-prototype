# Iteration 1 — Faster Transition to Alternatives

## What we observed
During testing with Alex, the agent continued asking Socratic questions even after Alex had already identified his own problem ("I relied on AI too much and forgot to double check"). It took too long to offer a concrete alternative.

## What we changed
Updated ai-use-reflection/SKILL.md to:
- Transition to /better-prompting within 1-2 turns once the student names their problem
- Added specific signals that the problem is named (self-diagnosis, "yeah" confirmation)
- Named the failure mode: continuing to question after the student already has the insight

## Why
More questioning after the student has already arrived at their insight feels like interrogation, not curiosity. Once they've named it, move.
