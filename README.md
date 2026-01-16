# Zanarkand Skills

A collection of specialized skills for Claude and the OpenCode system. This repository serves as a database of reusable patterns, workflows, and knowledge indices designed to enhance agent capabilities.

## 🛠 Available Skills

### [transfer-learn](./transfer-learn/SKILL.md)
Extracts patterns from mature codebases into reusable skill reference files. It guides an agent through analyzing a source repository, extracting its best patterns, and using `skill-creator` to build a new, standalone skill.

## 📂 Structure

- `[skill-name]/SKILL.md`: The entry point for the skill, defining its purpose, workflow, and metadata.
- `[skill-name]/references/`: Detailed documentation, pattern indices, and implementation guides.
- `_ralph/`: System coordination and research cache for the repository itself.

## 📜 License
MIT
