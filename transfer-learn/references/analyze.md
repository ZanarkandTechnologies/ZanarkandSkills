# Phase 1: ANALYZE

## Goal
Understand the source codebase and identify extractable patterns.

## Steps

### 1.1 Initialize New Skill
Use the `skill-creator` skill to initialize the target skill.
```bash
# Example (if using a tool that supports it)
# skill-creator create [skill-name]
```

### 1.2 Analyze Codebase Structure
Explore the source repository to find high-signal files.
```bash
# Get directory tree
find [codebase-path] -maxdepth 3 -not -path '*/.*'

# Look for key files
# - Schema definitions (schema.ts, models/)
# - Auth logic (auth.ts, middleware.ts)
# - Core business logic
# - Documentation (README.md, AGENTS.md)
```

### 1.3 Identify Pattern Categories
Look for these in the codebase:

| Category | What to Look For |
|----------|------------------|
| **Directory Structure** | How files are organized (systems, features) |
| **Schema Patterns** | Validators, type exports, table definitions |
| **Auth Patterns** | Helper functions, access control |
| **Documentation** | Header comments, internal guides |
| **System Modules** | Reusable domain systems (chat, user, etc.) |
| **Orchestration** | Workflows, task tracking, scheduling |

### 1.4 Log Findings
Create a `transfer-log.md` in your current working directory to track progress:

```markdown
# Transfer Learn: [skill-name]
Source: [codebase-path]

## Phase 1: ANALYZE
Status: Complete
Patterns Found:
- [ ] Directory Structure: [brief description]
- [ ] Schema Patterns: [brief description]
- [ ] Auth/User System: [brief description]
- [ ] Custom: [list any unique patterns]

Priority Order for Phase 2:
1. [highest value pattern]
2. [second pattern]
```

## Output
- List of 3-8 pattern categories to extract.
- Priority order for reference file creation.
- Phase 1 marked complete in `transfer-log.md`.
