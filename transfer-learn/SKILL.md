---
name: transfer-learn
version: 2.0.0
description: "Extract patterns from mature codebases into reusable skills using skill-creator."
---

# Transfer Learn

Extract patterns from high-quality codebases into reusable skill reference files. This skill guides you through analyzing a source repository, extracting its best patterns, and using `skill-creator` to build a new, standalone skill.

## Quick Start

1. **Identify Source**: Find a repository with interesting patterns (e.g., a mature Convex backend, a complex auth system).
2. **Initialize**: Create a new skill using `skill-creator`.
3. **Execute Workflow**: Follow the 5-phase process to populate the new skill.

## Workflow Phases

### Phase 1: ANALYZE
**Goal**: Understand source codebase structure and identify patterns.
**Reference**: [analyze.md](references/analyze.md)

### Phase 2: POPULATE  
**Goal**: Create reference files for each pattern in the new skill.
**Reference**: [populate.md](references/populate.md)

### Phase 3: ENRICH
**Goal**: Add external sources (official docs, example repos).
**Reference**: [enrich.md](references/enrich.md)

### Phase 4: REVIEW
**Goal**: Critique the new skill from an agent's perspective.
**Reference**: [review.md](references/review.md)

### Phase 5: OPTIMIZE
**Goal**: Restructure for better agent experience and finalize.
**Reference**: [optimize.md](references/optimize.md)

## Decision Tree

| I need to... | Load this |
|--------------|-----------|
| Start a new extraction | `references/analyze.md` |
| Write pattern files | `references/populate.md` |
| Add official docs | `references/enrich.md` |
| Check skill quality | `references/review.md` |
| Finalize/Polish | `references/optimize.md` |

## Guidelines

- **Use skill-creator**: Always use the official `skill-creator` skill to initialize and manage the new skill's structure.
- **Generalize**: Don't just copy-paste; remove project-specific logic to make patterns reusable.
- **Real Examples**: Keep actual code snippets (commented with source paths) to provide concrete context.
- **Backpressure**: Ensure the new skill's examples are syntactically correct.
