# Sitefinity AI Agents

A collection of free, open-source [custom AI agents](https://www.progress.com/documentation/sitefinity-cms/custom-ai-agents) for Sitefinity CMS, shared by [Enso DX](https://www.ensodx.com).

Sitefinity CMS lets administrators configure custom AI agents that analyze content fields during authoring and surface inline suggestions, with a human always in the loop before any change is applied. Each agent in this repo is a ready-to-use instruction set you can paste straight into your Sitefinity backend.

## Available agents

| Agent | Description |
| --- | --- |
| [Legal, compliance & semantic markup](compliance-agent/legal-compliance-and-semantic-markup.md) | Flags legal/regulatory risk in content claims and checks correct `<dfn>`/`<abbr>` semantic markup. |

## How to use an agent

1. Open the agent file you want to use and copy its contents.
2. In Sitefinity, go to **Administration > AI agents** and create a new agent.
3. Fill in a descriptive **Agent Name**, **Short Name**, and **Agent ID**.
4. Paste the agent file's contents into the **Instructions** field.
5. Configure the **scope** (sites, content types, and fields the agent should apply to) and enable it.

Read the [Sitefinity custom AI agents article](https://www.ensodx.com/resources/posts/item/2026/06/18/beyond-the-built-in-sitefinity-agents--a-custom-compliance-agent-we-built) for full details.

## Contributing

Contributions of new agents and improvements to existing ones are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for the agent template and submission guidelines.

## License

Licensed under the [MIT License](LICENSE). Free to use, copy, and modify; attribution back to this repo is appreciated but not required.
