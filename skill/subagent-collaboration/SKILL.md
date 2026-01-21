---
name: subagent-collaboration
description: Manage and read summaries of subagent work to facilitate collaboration.
---

# Subagent Collaboration Skill

This skill allows agents to communicate their progress and findings to each other by writing and reading summary files in the `.subagent/` directory of the current project.

## How to use:

### 1. Update your summary
When you complete a significant task or want to share your current state or need other agents to solve specific issues and/or make any decision, write a markdown summary to:
`.subagent/<your-agent-name>.summary.md`

Example:
If you are the `analyst` agent, write to `.subagent/analyst.summary.md`.

### 2. Read other summaries
Before starting your task, or when you need information from another specialized agent, read their summary from the `.subagent/` directory.

### 3. Summary Content
Your summary should include:
- **Status:** What is the current status of your task?
- **Key Findings:** What important information did you discover?
- **Technical Details:** Specific paths, names, or patterns discovered.
- **Recommendations:** Suggestions for the next agent in the workflow.
- **Blocking Issues:** Anything preventing progress.

## Benefits:
- Reduces redundant work.
- Provides a clear handoff between agents.
- Maintains a persistent record of the development process within the project.
