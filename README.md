# Self-Study OS

**A structured notebook, strategic coach, and critical editor for learning, execution, and business growth.**

Self-Study OS is a Claude skill designed to help you keep track of meaningful work, make better decisions, identify bottlenecks, and choose practical next actions. It combines a lightweight personal operating system with candid, evidence-aware coaching.

## What it helps you do

- **Build a working profile:** Gradually capture your objectives, active projects, platforms, preferences, constraints, and risks without assuming information you have not provided.
- **Keep useful context:** Organize durable goals, project details, decisions, experiments, skills, problems, metrics, and opportunities.
- **Create Notebook Reports:** Review direction, evidenced progress, project status, strengths, weaknesses, opportunities, skill gaps, priorities, and the next measurable action.
- **Choose daily focus:** Identify one high-impact outcome, supporting tasks, a definition of done, and what to postpone.
- **Run weekly reviews:** Examine what shipped, what produced evidence, what was learned, what stalled, and what to change.
- **Diagnose problems:** Separate evidence from unknowns and hypotheses before recommending a practical test.
- **Validate niches and offers:** Assess audience access, pain, alternatives, willingness to pay, credibility, distribution, and low-cost validation experiments.
- **Review content:** Evaluate relevance, specificity, clarity, usefulness, originality, proof, platform fit, and calls to action.
- **Recommend reusable Claude skills:** Identify repeated tasks and bottlenecks, then recommend a focused skill only when the evidence supports it.

## Design principles

Self-Study OS is built around a few operating principles:

1. Accuracy before confidence: do not invent progress, analytics, revenue, validation, or decisions.
2. Evidence over assumptions: distinguish confirmed information, user-reported information, hypotheses, and recommendations.
3. Execution over planning: turn ideas into small, measurable actions.
4. Focus over fragmentation: identify competing priorities and recommend a clear primary focus.
5. Candid and constructive feedback: explain weaknesses, consequences, and possible corrections without generic praise.
6. User agency: explain recommendations; the user remains responsible for consequential decisions.
7. Honest capability boundaries: never claim that something was saved, scheduled, published, monitored, or sent unless that action actually happened.

## Installation

This repository contains a Claude skill in the `self-study-os/` directory.

1. Download the repository or its ZIP archive from GitHub.
2. Locate the `self-study-os` skill folder, which contains `SKILL.md` and the `references/` directory.
3. Add the skill to Claude using the skills management/import options available in your Claude account. Follow Anthropic's current instructions for importing custom skills, as the interface and availability may change.
4. Enable the skill in Claude.

## How to use it

After installation, describe what you want to work on in normal language. You do not need to memorize commands. Examples include:

- “Create my Notebook Report.”
- “Help me decide what to focus on today.”
- “Run my weekly review.”
- “Diagnose why this project is stalled.”
- “Help me validate this niche and offer.”
- “Review this draft before I publish it.”
- “Which repeated task should I turn into a Claude skill?”

On first use, if no profile is available, the skill asks one essential question: what you are building or trying to improve right now? It builds the working profile gradually from your answers.

## Persistence and privacy

The skill's instructions do not themselves guarantee persistent storage. It checks whether memory or a storage tool is available. If neither is available, it should say so and provide a portable note that you can save in your own notes. Do not treat a drafted note or report as automatically saved.

Avoid putting passwords, account credentials, or other sensitive information into your notebook.

## Repository structure

```text
self-study-os/
├── SKILL.md
└── references/
    └── skill-ideas.md
```

- `SKILL.md` contains the skill's instructions, modes, operating principles, recommendation criteria, and boundaries.
- `references/skill-ideas.md` is an inspiration catalog of possible reusable skills across research, content, distribution, sales, operations, and learning. Recommendations should be based on the user's actual evidence, not this catalog alone.

## Contributing

Suggestions, issue reports, and improvements are welcome. When proposing changes, aim to preserve the project's core principles: evidence-based reasoning, practical execution, user agency, and honest capability boundaries.

## License

No license has been included yet. Unless a license is added, the repository is publicly viewable but standard copyright restrictions still apply; public visibility does not automatically grant permission to reuse, modify, or redistribute the contents.
