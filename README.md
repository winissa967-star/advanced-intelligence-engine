# Advanced Intelligence Engine (AIE) v2.0

A modular, reusable AI skill for adaptive reasoning, research, software
engineering, decision-making, and verification.

## Structure

- `SKILL.md` — activation metadata and core workflow.
- `references/research.md` — evidence-led research.
- `references/engineering.md` — software development and testing.
- `references/verification.md` — quality assurance and adversarial review.
- `references/decision-making.md` — strategy and trade-off analysis.
- `references/communication.md` — response style and clarification.
- `evals/benchmark.md` — repeatable evaluation cases.

## Installation

### Claude Code
Copy the `advanced-intelligence-engine` folder into:
`.claude/skills/advanced-intelligence-engine/`

For a user-wide installation, use the corresponding skills directory supported
by your Claude Code version.

### Codex
Copy the folder into:
`.agents/skills/advanced-intelligence-engine/`

For a user-wide installation, use the corresponding skills directory supported
by your Codex version.

Follow the current product documentation if directory conventions change.

## Usage
Ask the agent to use `advanced-intelligence-engine` for a complex task, or
describe the task in a way that matches the skill's metadata description.
Automatic activation depends on the host agent and its skill-loading behavior.

## Design notes
The core file stays concise. Detailed procedures live in reference files and
should be consulted only when relevant. This reduces unnecessary context use.

## Limitations
A skill is an instruction package, not model fine-tuning. It does not create
new tools, permissions, memory, autonomy, or guaranteed accuracy.

## Evaluation
Run the cases in `evals/benchmark.md` with and without the skill under
comparable conditions. Record results before claiming that the skill improves
performance.
