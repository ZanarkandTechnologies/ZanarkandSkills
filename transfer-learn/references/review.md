# Phase 4: REVIEW

## Goal
Critique the new skill from an agent's perspective.

## Steps

### 4.1 Load Skill Fresh
Pretend you're an agent loading this new skill for the first time. Read its `SKILL.md` and browse the `references/` folder.

### 4.2 Score Agent Experience
Rate 1-10 on each dimension:

| Dimension | Score | Notes |
|-----------|-------|-------|
| **Clarity** | /10 | Can I immediately find what I need? |
| **Navigation** | /10 | Is there a decision tree? |
| **Noise** | /10 | Are there redundant sections/files? |
| **Completeness** | /10 | Are key patterns covered? |
| **File Focus** | /10 | Is each reference file focused? |

### 4.3 Identify Issues
Check for these problems:
- **SKILL.md**: Too long, missing decision tree, too many links.
- **References**: Files too long (>400 lines), overlapping content, unclear names.
- **Structure**: Too many files (>10), missing "When to Use" sections.

### 4.4 Create Improvement List
Update `transfer-log.md`:

```markdown
## Phase 4: REVIEW
Status: Complete
Overall Score: [X]/10

### Improvements Needed
1. [Issue]: [How to fix]
2. ...
```

## Output
- Agent experience score.
- Prioritized improvement list in `transfer-log.md`.
- Phase 4 marked complete.
