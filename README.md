# 🧪 Foundry Models Playground

Welcome to **Foundry Models Playground**, your streamlined dev environment for rapidly prototyping with **state-of-the-art AI models** from [Azure AI Foundry Catalog](https://ai.azure.com/explore/models) and [Azure AI Foundry Labs](https://ai.azure.com/labs) — all without the hassels of getting set up with these resources.

By using this template, you'll be up and running with GitHub Copilot and connected to powerful backend tools in just **one click**.

---

## 🚀 One-Click Setup

Start building instantly:

[![Use this template](https://img.shields.io/badge/-Use%20this%20template-blue?style=for-the-badge&logo=github)](https://github.com/azure-ai-foundry/foundry-models-playground/generate)

[![Open in GitHub Codespaces](https://img.shields.io/badge/-Open%20in%20Codespaces-lightgrey?style=for-the-badge&logo=github)](https://github.com/codespaces/new?template_repository=azure-ai-foundry/foundry-models-playground/generate)

---

## 🧠 What’s Inside?

Foundry Models Playground gives you everything you need to prototype AI-based solutions **inside GitHub Copilot**.

When you open this workspace, it will automatically start two backend servers:

- 🔹 **Foundry Catalog MCP Server** – exposes tools to browse and integrate models from Foundry Catalog
- 🔹 **Foundry Labs MCP Server** – lets you explore cutting-edge research projects and models by Microsoft Research from Azure AI Foundry Labs

These servers are automatically started inside a devcontainer and communicate via `stdio` with GitHub Copilot.

---

## 🧰 Available Tools in GitHub Copilot

When GitHub Copilot is running in this environment, it will be equipped with the following tools — no extra config needed:

### 🔸 From Foundry Catalog

- `get_foundry_models_list`

  > Lists available models in the Foundry Catalog.

- `get_implementation_details_for_foundry_model`
  > Provides detailed integration guidance for a specific model.

### 🔹 From Foundry Labs

- `get_azure_ai_foundry_labs_projects_list`

  > Lists available projects from Foundry Labs.

- `get_implementation_details_for_labs_project`
  > Gives implementation steps for a specific Labs project.

These tools are automatically discovered by Copilot and can be used in natural language prompts while coding.

---

## 💡 Getting Started

1. **Use this template** to create your own repository. If you already did that, you can skip to the next step.
2. **Open in Codespaces** or **VS Code** (with devcontainer support).
3. Once the environment boots, open **Settings** (Ctrl+,) and search for "chat.agent.enable" and enable Agent Mode.
4. Open Chat view (Ctrl+Alt+I) and click Use Copilot. Change to **Agent Mode** and Copilot automatically discovers the MCP Servers.
5. To load MCP Servers, click icon "**New tools available**".
6. (Optional) you can click "**Tools**" icon on Chat view to see loaded MCP servers and tools. Also open `.vscode/mcp.json` to see preconfigured servers.
7. Start by asking Copilot about models or guidance.
