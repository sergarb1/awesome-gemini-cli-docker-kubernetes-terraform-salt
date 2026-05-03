# Claude Code Configuration

This repository is optimized for AI-driven DevOps. While it was built for Gemini CLI, the instructions are fully compatible with **Claude Code**.

## 🛠️ Usage with Claude
To use these DevOps agents with Claude, you can use the following methods:

### 1. Direct Reference
You can ask Claude to read the specific agent instructions when performing a task:
`Read .gemini/agents/kubernetes/instructions.md and help me create a deployment.`

### 2. Project Memory
If you want Claude to always act as a specific expert within this project, you can add a reference to your `CLAUDE.md` (if you are working in a derivative project):

```markdown
# DevOps Expertise
When working on [Docker/K8s/Terraform], refer to the standards in:
- .gemini/agents/docker/instructions.md
- .gemini/agents/kubernetes/instructions.md
```

## 📐 Build & Lint Commands
Claude often asks for project-specific commands. Since this is a documentation and agent repository, here are the relevant checks:

- **Validate Markdown:** `npx markdownlint-cli **/*.md` (if installed)
- **Check Links:** `npx markdown-link-check README.md AGENTS.md`

## 🧩 Agent Index
- **Docker:** `.gemini/agents/docker/instructions.md`
- **Kubernetes:** `.gemini/agents/kubernetes/instructions.md`
- **Terraform:** `.gemini/agents/terraform/instructions.md`
- **SaltStack:** `.gemini/agents/salt/instructions.md`
- **Vagrant:** `.gemini/agents/vagrant/instructions.md`
