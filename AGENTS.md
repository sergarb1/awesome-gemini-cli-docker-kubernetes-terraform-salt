# 📖 Agents Catalog & Usage Guide

Welcome to the Awesome Gemini CLI DevOps Agents catalog. These agents are designed to provide expert-level context to your AI assistant.

## 🛠️ How to Use These Agents

### For Gemini CLI Users
1. **Direct Use:** Clone this repository and run `gemini` inside it. The CLI will automatically pick up the agents in `.gemini/agents/`.
2. **Importing into Your Project:** Copy the desired agent folder from `.gemini/agents/` into your own project's `.gemini/agents/` directory.

### For Claude Code / Other LLM Tools
Most modern AI CLI tools look for markdown instructions. You can:
1. Copy the content of an agent's `instructions.md` into your project's `CLAUDE.md` or equivalent.
2. Point your assistant to the relevant `instructions.md` file using a tool or by pasting the content.

---

## 🧩 Available Agents

### 🐳 Docker Expert
- **Location:** `./.gemini/agents/docker/`
- **Focus:** Optimized Dockerfiles, security (non-root), BuildKit caching, and layer minimization.
- **When to use:** When containerizing applications or troubleshooting builds.

### 🏗️ Docker Compose Specialist
- **Location:** `./.gemini/agents/docker-compose/`
- **Focus:** Multi-service orchestration, networking, and volume management.
- **When to use:** When managing local development environments with multiple containers.

### ☸️ Kubernetes Specialist
- **Location:** `./.gemini/agents/kubernetes/`
- **Focus:** YAML manifests, Kustomize, resource limits, and cluster security.
- **When to use:** When deploying to K8s or designing resilient architectures.

### 🌍 Terraform IaC Guru
- **Location:** `./.gemini/agents/terraform/`
- **Focus:** State management, modularity, and provider best practices.
- **When to use:** When managing infrastructure as code.

### 🧂 SaltStack Expert
- **Location:** `./.gemini/agents/salt/`
- **Focus:** Configuration management, event-driven automation, and state files.
- **When to use:** When automating server configuration and management.

### 📦 Vagrant & Virtualization Expert
- **Location:** `./.gemini/agents/vagrant/`
- **Focus:** Reproducible local VMs, automated provisioning, and optimized syncing.
- **When to use:** When creating standardized development environments on virtual machines.

---

## 🚀 Get Started
Simply choose an agent that fits your current task and provide its instructions to your AI assistant to elevate the quality of its suggestions and implementations.
