# Phase 3: ENRICH

## Goal
Add external knowledge sources (official docs, example repos) to the new skill.

## Steps

### 3.1 Identify Official Documentation
Find authoritative sources for the skill's domain:
- Official documentation URLs
- Best practices pages
- Platform limits/constraints
- API references

### 3.2 Add Doc Links to SKILL.md
Create an "Official Docs" section in the new skill's `SKILL.md`:

```markdown
## Official Docs

**Essential**:
- [Main Docs](https://...)
- [Best Practices](https://...)
- [Limits](https://...)

**Key Topics**:
- [Topic 1](https://...) - Brief description
```

### 3.3 Extract Patterns from Example Repos
If official example repos exist:
1. **Identify repo** (e.g., `github.com/org/examples`).
2. **Find workflow patterns** not in the source codebase.
3. **Add to existing references** or create new ones.

### 3.4 Create Gotchas/Limits Reference
If the domain has constraints (timeouts, rate limits), create a `gotchas.md` in the new skill's `references/` folder.

### 3.5 Log Progress
Update `transfer-log.md`:

```markdown
## Phase 3: ENRICH
Status: Complete
Added:
- Official docs section in SKILL.md
- Gotchas reference: [yes/no]
- External patterns: [list any]
```

## Output
- Official docs links in the new skill's `SKILL.md`.
- Gotchas/best practices reference (if applicable).
- External patterns integrated.
