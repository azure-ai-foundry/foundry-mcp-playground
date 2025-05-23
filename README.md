# 🧪 Foundry MCP Playground

Welcome to **Foundry MCP Playground**, your streamlined dev environment for rapidly prototyping with **MCP Server that can interact with Azure AI Foundry**, including the ability to explore and use **state-of-the-art AI models** from [Azure AI Foundry Catalog](https://ai.azure.com/explore/models) and [Azure AI Foundry Labs](https://ai.azure.com/labs), to **manage and query knowledge** using [Azure AI Search](https://learn.microsoft.com/azure/search/search-what-is-azure-search) and to **evaluate text and agent responses** with [Observability features in Azure AI Foundry](https://learn.microsoft.com/azure/ai-foundry/concepts/observability) — all without the hassels of getting set up with these resources.

By using this template, you'll be up and running with GitHub Copilot and connected to powerful backend tools in just **one click**.

---

## 🚀 One-Click Setup

Start building instantly:

[![Use this template](https://img.shields.io/badge/-Use%20this%20template-grey?style=for-the-badge&logo=github)](https://github.com/azure-ai-foundry/foundry-mcp-playground/generate)

> Click this if you like to create your new repository from this template

[![Open in GitHub Codespaces](https://img.shields.io/badge/-Open%20in%20Codespaces-blue?style=for-the-badge&logo=github)](https://github.com/codespaces/new?template_repository=azure-ai-foundry/foundry-mcp-playground/generate)

> Click this if you like to start clean using current repository in GitHub Codespaces

---

## 🧠 What’s Inside?

Foundry MCP Playground gives you everything you need to prototype AI-based solutions **inside GitHub Copilot**.

When you open this workspace, it will automatically start the MCP server for Azure AI Foundry:

- **MCP Server for Azure AI Foundry (experimental)** – exposes tools to interact with Azure AI Foundry

This server is automatically started inside a devcontainer and communicate via `stdio` with GitHub Copilot.

---

## 🧰 Available Tools in GitHub Copilot

When GitHub Copilot is running in this environment, it will be equipped with all the tools — no extra config needed. See [MCP Server for Azure AI Foundry (experimental)](https://github.com/azure-ai-foundry/mcp-foundry) for more details.:

These tools are automatically discovered by Copilot and can be used in natural language prompts while coding.

---

## 💡 Getting Started

1. **Use this template** to create your own repository. If you already did that, you can skip to the next step.
1. **Open in Codespaces** or **VS Code** (with devcontainer support).
    1. If you use VS Code with devcontainer, you'll need Docker engine running locally.
1. Once the environment is ready, open **Settings** (Ctrl+,) and search for "chat.agent.enable" and enable Agent Mode.
1. Open Chat view (Ctrl+Alt+I) and click Use Copilot. Change to **Agent Mode** and Copilot automatically discovers the MCP Servers.
1. To load MCP Servers, click icon "**New tools available**", if not loaded already.
1. (Optional) you can click "**Tools**" icon on Chat view to see loaded MCP servers and tools. Also open `.vscode/mcp.json` to see preconfigured servers.
1. Start by asking Copilot about what it can help on Azure AI Foundry.

## Example Prompts

### Explore models
- What can you do?
- How can you help me find the right model?
- What models can I use from Azure AI Foundry?
- What OpenAI models are available in Azure AI Foundry?
- What are the most popular models in Azure AI Foundry? Pick me 10 models.
- What models are good for reasoning? Show me some examples in two buckets, one for large models and one for small models.
- Can you compare Phi models and explain differences?
- Show me the model card for Phi-4-reasoning.
- Can you show me how to test a model?
- What does free playground in Azure AI Foundry mean?
- Can I use GitHub token to test models?
- Show me latest models that support GitHub token.
- Who are the model publishers for the models in Azure AI Foundry?
- Show me models from Meta.
- Show me models with MIT license.

### Build prototypes
- Can you describe how you can help me build a prototype using the model?
- Describe how you can build a prototype that uses an OpenAI model with my GitHub token. Don't try to create one yet.
- Recommend me a few scenarios to build prototypes with models.
- Tell me about Azure AI Foundry Labs.
- Tell me more about Magentic One
- What is Omniparser and what are potential use cases?
- Can you help me build a prototype using Omniparser?
- I need to build an application that can analyze my web UX designs and advise me of any areas that may be difficult for users to navigate or might create a cognitive overload.
- I'd like to build a model comparison app to compare Azure AI Foundry Catalog models. The user should be able to select from about 8-10 different catalog models. From there, the user enters a prompt, which each of the selected models will respond to. The output should be side by side. The user can also select a specific model from a set of "evaluator" models that are good at evaluation, that will evaluate the outputs of user-selected models. The evaluator should provide a short written evaluations to each models' response, as well as a numerical score.

### Deploy OpenAI models
- Can you help me deploy OpenAI models?
- What steps do I need to take to deploy OpenAI models on Azure AI Foundry?
- Can you help me understand how I can use OpenAI models on Azure AI Foundry using GitHub token? Can I use it for production?
- I already have an Azure AI services resource. Can I deploy OpenAI models on it?
- What does quota for OpenAI models mean on Azure AI Foundry?
- Get me current quota for my AI services resource.
