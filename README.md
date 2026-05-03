# 🚀 Awesome Gemini CLI DevOps Agents

[English](#english) | [Castellano](#castellano)

---

<a name="english"></a>
## 🇺🇸 English

[![Docker](https://img.shields.io/badge/Docker-Expert-2496ED?logo=docker&logoColor=white)](./.gemini/agents/docker)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Specialist-326CE5?logo=kubernetes&logoColor=white)](./.gemini/agents/kubernetes)
[![Terraform](https://img.shields.io/badge/Terraform-IaC_Guru-7B42BC?logo=terraform&logoColor=white)](./.gemini/agents/terraform)
[![SaltStack](https://img.shields.io/badge/Salt_Project-Automation-5DB95E?logo=saltstack&logoColor=white)](./.gemini/agents/salt)
[![Vagrant](https://img.shields.io/badge/Vagrant-Virtualization-1868F2?logo=vagrant&logoColor=white)](./.gemini/agents/vagrant)

Elevate your DevOps workflow with specialized **Context Agents**. This repository provides high-level expert instructions that transform Gemini (and other AI CLI tools) into a specialized senior engineer for your specific stack.

### 🌟 Why Use These Agents?
Standard AI models are generalists. These agents provide "Grounding Instructions" that enforce:
- **Security First:** Non-root users, secret mounts, and resource isolation.
- **Production Readiness:** Healthchecks, resource limits, and lifecycle probes.
- **Best Practices:** Multi-stage builds, modular IaC, and declarative configurations.

### 📂 Project Structure
```text
.
├── .gemini/agents/
│   ├── docker/          # 🐳 Dockerfiles, Security & BuildKit optimization
│   ├── docker-compose/  # 🏗️ Multi-container environments & Orchestration
│   ├── kubernetes/      # ☸️ K8s manifests, Helm & Kustomize
│   ├── terraform/       # 🌍 IaC, State management & Provider patterns
│   ├── salt/            # 🧂 Config management & Event-driven automation
│   └── vagrant/         # 📦 Reproducible development VMs
├── AGENTS.md            # 📖 Detailed Catalog & Cross-assistant guide
├── CLAUDE.md            # 🤖 Specialized guide for Claude Code users
└── CONTRIBUTING.md      # 🤝 How to add new agents
```

### 🛠️ Getting Started

#### Option A: Local Usage (Within this repo)
1. Clone the repository.
2. Run `gemini` (or your preferred AI CLI) inside this folder. The assistant will automatically adopt the context of all agents.

#### Option B: Global Usage (In your own projects)
1. Copy the desired agent folder (e.g., `.gemini/agents/kubernetes`) into your project's root.
2. The AI will immediately start applying the expert principles to your local files.

### 📖 Further Documentation
- **[AGENTS.md](./AGENTS.md):** Full list of agents and how to use them with other LLM tools.
- **[CLAUDE.md](./CLAUDE.md):** Specific tips for Claude Code users.
- **[GEMINI.md](./GEMINI.md):** Development standards for this repository.

---

<a name="castellano"></a>
## 🇪🇸 Castellano

[![Docker](https://img.shields.io/badge/Docker-Expert-2496ED?logo=docker&logoColor=white)](./.gemini/agents/docker)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Specialist-326CE5?logo=kubernetes&logoColor=white)](./.gemini/agents/kubernetes)
[![Terraform](https://img.shields.io/badge/Terraform-IaC_Guru-7B42BC?logo=terraform&logoColor=white)](./.gemini/agents/terraform)
[![SaltStack](https://img.shields.io/badge/Salt_Project-Automation-5DB95E?logo=saltstack&logoColor=white)](./.gemini/agents/salt)
[![Vagrant](https://img.shields.io/badge/Vagrant-Virtualización-1868F2?logo=vagrant&logoColor=white)](./.gemini/agents/vagrant)

Potencia tu flujo de trabajo DevOps con **Agentes de Contexto** especializados. Este repositorio proporciona instrucciones de experto de alto nivel que transforman a Gemini (y otras herramientas de IA CLI) en un ingeniero senior especializado en tu stack tecnológico.

### 🌟 ¿Por qué usar estos agentes?
Los modelos de IA estándar son generalistas. Estos agentes proporcionan "Instrucciones de Anclaje" que obligan a seguir:
- **Seguridad primero:** Usuarios no-root, montajes de secretos y aislamiento de recursos.
- **Listos para Producción:** Healthchecks, límites de recursos y probes de ciclo de vida.
- **Mejores Prácticas:** Builds multi-etapa, IaC modular y configuraciones declarativas.

### 📂 Estructura del Proyecto
```text
.
├── .gemini/agents/
│   ├── docker/          # 🐳 Dockerfiles, Seguridad y optimización de BuildKit
│   ├── docker-compose/  # 🏗️ Entornos multi-contenedor y Orquestación
│   ├── kubernetes/      # ☸️ Manifiestos K8s, Helm y Kustomize
│   ├── terraform/       # 🌍 IaC, Gestión de estado y patrones de proveedores
│   ├── salt/            # 🧂 Gestión de config. y automatización reactiva
│   └── vagrant/         # 📦 VMs de desarrollo reproducibles
├── AGENTS.md            # 📖 Catálogo detallado y guía para otros asistentes
├── CLAUDE.md            # 🤖 Guía especializada para usuarios de Claude Code
└── CONTRIBUTING.md      # 🤝 Cómo añadir nuevos agentes
```

### 🛠️ Cómo empezar

#### Opción A: Uso Local (Dentro de este repo)
1. Clona el repositorio.
2. Ejecuta `gemini` (o tu IA CLI preferida) dentro de esta carpeta. El asistente adoptará automáticamente el contexto de todos los agentes.

#### Opción B: Uso Global (En tus propios proyectos)
1. Copia la carpeta del agente deseado (ej. `.gemini/agents/kubernetes`) en la raíz de tu proyecto.
2. La IA comenzará inmediatamente a aplicar los principios de experto a tus archivos locales.

### 📖 Documentación Adicional
- **[AGENTS.md](./AGENTS.md):** Lista completa de agentes y cómo usarlos con otras herramientas LLM.
- **[CLAUDE.md](./CLAUDE.md):** Consejos específicos para usuarios de Claude Code.
- **[GEMINI.md](./GEMINI.md):** Estándares de desarrollo para este repositorio.

---
*Created with ❤️ for the DevOps community.*
