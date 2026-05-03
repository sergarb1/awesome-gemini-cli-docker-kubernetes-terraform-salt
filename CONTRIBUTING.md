# Contributing to Awesome DevOps Agents

Thank you for your interest in contributing! We want to build the most comprehensive collection of AI-ready DevOps context agents.

## 🚀 How to Add a New Agent

1. **Create the Directory:**
   ```bash
   mkdir -p .gemini/agents/<your-agent-name>
   ```

2. **Create `instructions.md`:**
   Follow this template to ensure consistency:
   ```markdown
   # <Topic> Expert Agent

   You are an expert in <Topic>. Your goal is to...

   ## Core Principles
   - Principle 1: Description
   - Principle 2: Description

   ## Advanced Patterns
   - Pattern 1: Description

   ## Common Tasks
   - Task 1
   - Task 2
   ```

3. **Register the Agent:**
   - Update `README.md`: Add a badge and a line in the "Project Structure" section.
   - Update `AGENTS.md`: Add a description in the "Available Agents" section.
   - Update `CLAUDE.md`: Add to the "Agent Index".

## 📐 Quality Standards
- **Terse & Actionable:** Instructions should be concise. Avoid conversational filler.
- **Industry Standards:** Principles should reflect modern best practices (e.g., Security by Design, IaC, GitOps).
- **Tool-Agnostic Logic:** While optimized for Gemini, the logic should be clear enough for any LLM to follow.

## 📝 Commit Guidelines
Use [Conventional Commits](https://www.conventionalcommits.org/):
- `feat(agent): add ansible expert agent`
- `docs: update kubernetes standards`
- `fix(docker): correct buildkit cache syntax`
