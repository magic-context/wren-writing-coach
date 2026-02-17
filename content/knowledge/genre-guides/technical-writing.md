# Technical Writing Guide

## Core Principles
- **Accuracy** above all — wrong information is worse than no information
- **Clarity** over elegance — if it's ambiguous, it's wrong
- **Task-oriented** — readers want to DO something, not learn theory
- **Scannable** — nobody reads technical docs linearly

## Document Types

### Tutorials (Learning-oriented)
- Guide the reader through a complete task
- Concrete steps with expected outcomes
- "Build a REST API in 15 minutes"
- Include every step — don't assume knowledge

### How-to Guides (Task-oriented)
- Solve a specific problem
- Assume some baseline knowledge
- "How to deploy to AWS Lambda"
- Steps are practical and goal-directed

### Reference (Information-oriented)
- Complete, accurate descriptions
- API docs, configuration options, specifications
- Organized for lookup, not reading
- Consistent format across entries

### Explanations (Understanding-oriented)
- Why things work the way they do
- Architecture decisions, design philosophy
- Readable prose, not just steps
- Context and background

## Technical Writing Style
- **Use imperative mood:** "Click the button" not "You should click the button"
- **Be specific:** "Enter your API key in the `config.yml` file" not "Configure authentication"
- **One instruction per step** — don't combine actions
- **Use code blocks** for anything the reader types or sees on screen
- **Define acronyms** on first use
- **Consistent terminology** — pick one term and stick with it

## Structure
```
# Title (what this doc covers)

## Overview (1-2 sentences: what and why)

## Prerequisites (what they need before starting)

## Steps
### Step 1: [Action]
### Step 2: [Action]

## Troubleshooting (common issues)

## Next Steps (where to go from here)
```

## Common Technical Writing Mistakes
1. **Assuming knowledge** — curse of expertise; explain what they need
2. **Missing steps** — you tested the process, right?
3. **Outdated screenshots** — UI changes faster than docs
4. **Passive voice** — "The file is opened" → "Open the file"
5. **No examples** — show, don't just describe
