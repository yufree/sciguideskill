# Skill Template

Use this template to create new AI Skills for the SciGuide repository.

## Frontmatter
Every `SKILL.md` should start with YAML frontmatter:

```yaml
---
name: Skill Name
description: A short description of what this skill does.
author: Your Name/GitHub Handle
---
```

## SKILL.md Structure

### 1. Goal / 目标
Define the primary purpose of this skill.

### 2. Core Principles / 核心原则
List 3-5 guiding principles for the AI when performing this skill.

### 3. Workflow / 工作流
Steps the AI should take to execute the skill.

### 4. Reference Links / 参考链接
Link to files in the `references/` folder if applicable.

## Rules for References
- Keep reference files in Markdown format.
- Use relative links: `[Link Text](references/filename.md)`.
- Ensure files are concise and focused.
