# 🚀 Awesome Gemini CLI DevOps Agents: Development Guide

This file provides instructions for maintaining and extending this repository. If you are a user looking for how to use these agents, see [AGENTS.md](./AGENTS.md).

## 📂 Project Architecture
The repository is a collection of "Context Agents"—specialized Markdown instructions that provide domain-specific expertise to LLM-based CLI tools (specifically Gemini CLI).

### Directory Structure
- `.gemini/agents/<topic>/`: Contains the agent definition.
    - `instructions.md`: The core logic, principles, and common tasks for the agent.
- `GEMINI.md`: This file (Project-wide instructions).
- `AGENTS.md`: User-facing catalog and usage guide.

## 🛠️ Development Workflow

### Adding a New Agent
1. **Scaffold:** Create `.gemini/agents/<new-agent>/`.
2. **Define Instructions:** Create `instructions.md` following the established pattern:
    - **Role Definition:** Who is the agent? (e.g., "You are an expert in...")
    - **Core Principles:** High-level architectural and technical rules.
    - **Advanced Patterns:** Complex scenarios and specialized knowledge.
    - **Common Tasks:** What should the agent be able to help with?
3. **Update Documentation:**
    - Add a badge and entry to `README.md`.
    - Add to the "Available Agents" list in `GEMINI.md` and `AGENTS.md`.
    - Update the "Engineering Standards" section in `GEMINI.md`.

### Validating Instructions
- **Clarity:** Ensure instructions are unambiguous and avoid "fluff".
- **Actionability:** Every principle should lead to better code or configuration.
- **Accuracy:** Verify that the "Core Principles" align with industry best practices (e.g., Docker security, K8s resource limits).

## 📐 Engineering Standards & Conventions

### Style Guide for Instructions
- **Markdown Headers:** Use `##` for main sections and `###` for sub-sections.
- **Bullet Points:** Use `-` for lists.
- **Code Blocks:** Use backticks for symbols, commands, and file paths.
- **Tone:** Professional, direct, and authoritative.

### Multi-language Support
- Maintain the `README.md` with both English and Castellano sections.
- Primary documentation (like `GEMINI.md`, `AGENTS.md`, and agent `instructions.md`) should be in English for maximum compatibility, but summary READMEs can be bilingual.

## 🔄 Maintenance Tasks
- Periodically review agents to ensure they reflect the latest versions of the tools (e.g., updating Docker BuildKit patterns or K8s API versions).
- Ensure all badges in `README.md` point to the correct internal directories.
