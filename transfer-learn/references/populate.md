# Phase 2: POPULATE

## Goal
Create reference files for each identified pattern in the new skill.

## Steps

### 2.1 Create Reference File Template
For each pattern category, create a file in the new skill's `references/` folder:

```markdown
# [Pattern Name]

## When to Use
[1-2 sentences describing the scenario]

## Pattern

### Structure
[Directory layout or file organization]

### Code Template
```typescript
// Key code pattern with comments
```

### Real Example
```typescript
// Actual code from source codebase
// Include file path as comment
```

## Key Points
- Point 1
- Point 2

## Anti-patterns
- What NOT to do
```

### 2.2 Extract Patterns (One at a Time)
For each pattern in priority order:

1. **Read source files** that demonstrate the pattern.
2. **Extract the key code** - schemas, helpers, structure.
3. **Generalize** - make it reusable, not project-specific.
4. **Add context** - explain when/why to use it.
5. **Save** to the new skill's `references/[pattern-name].md`.

### 2.3 Update SKILL.md Index
Update the new skill's `SKILL.md` to include links to the new reference files.

### 2.4 Log Progress
Update `transfer-log.md` after each file:

```markdown
## Phase 2: POPULATE
Status: In Progress
Files Created:
- [x] project-setup.md
- [x] schema-patterns.md
- [ ] user-system.md (in progress)
```

## Reference File Checklist
Each file should have:
- [ ] "When to Use" section
- [ ] Code template
- [ ] Real example from source
- [ ] Anti-patterns

## Output
- Reference files in the new skill's `references/` folder.
- `SKILL.md` updated with links.
- Phase 2 marked complete in `transfer-log.md`.
