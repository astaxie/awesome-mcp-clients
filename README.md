# Awesome MCP Clients [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

A curated list of awesome Model Context Protocol (MCP) clients.

* [What is MCP?](#what-is-mcp)
* [Community](#community)
* [Clients](#clients)
* [Servers](#servers)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Clients

- [Awesome MCP Clients ](#awesome-mcp-clients-)
  - [What is MCP?](#what-is-mcp)
  - [Community](#community)
  - [Clients](#clients)
    - [5ire](#5ire)
    - [ChatMCP](#chatmcp)
    - [Claude Desktop](#claude-desktop)
    - [ClaudeMind](#claudemind)
    - [Cline](#cline)
    - [console-chat-gpt](#console-chat-gpt)
    - [Copilot-MCP](#copilot-mcp)
    - [Cursor](#cursor)
    - [Continue](#continue)
    - [Goose](#goose)
    - [HyperChat](#hyperchat)
    - [kibitz](#kibitz)
    - [LibreChat](#librechat)
    - [MCP Chatbot](#mcp-chatbot)
    - [MCP CLI client](#mcp-cli-client)
    - [MCP Simple Slackbot](#mcp-simple-slackbot)
    - [oterm](#oterm)
    - [Superinterface](#superinterface)
    - [SeekChat](#seekchat)
    - [Tester MCP Client](#tester-mcp-client)
    - [Witsy](#witsy)
    - [Enconvo](#enconvo)
    - [y-cli](#y-cli)
    - [Zed](#zed)
  - [Servers](#servers)

### 5ire

<table>
<tr><th align="left">GitHub</th><td>https://github.com/nanbingxyz/5ire</td></tr>
<tr><th align="left">Website</th><td>https://5ire.app/</td></tr>
<tr><th align="left">License</th><td>GNU v3</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

5ire is a cross-platform desktop AI assistant, MCP client. It compatible with major service providers, supports local knowledge base and tools via model context protocol servers.

<details>
<summary>Screenshots</summary>

https://github.com/user-attachments/assets/a27494c5-437d-481c-a25f-74cfa5a2bc45

</details>

### ChatMCP

<table>
<tr><th align="left">GitHub</th><td>https://github.com/daodao97/chatmcp</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Dart</td></tr>
</table>

ChatMCP is an AI chat client implementing the Model Context Protocol (MCP).

<details>
<summary>Screenshots</summary>

![](./screenshots/chatmcp/preview.png)
![](./screenshots/chatmcp/settings.png)

</details>

### Claude Desktop

<table>
<tr><th align="left">GitHub</th><td>-</td></tr>
<tr><th align="left">Website</th><td>https://claude.ai/download</td></tr>
<tr><th align="left">License</th><td>Proprietary</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>-</td></tr>
</table>

The Claude desktop app brings Claude's capabilities directly to your computer, allowing for seamless integration with your workflow.

<details>
<summary>Screenshots</summary>

![](./screenshots/claude-desktop/claude-desktop.png)

</details>

### ClaudeMind

<table>
<tr><th align="left">GitHub</th><td>-</td></tr>
<tr><th align="left">Website</th><td>https://claudemind.com/</td></tr>
<tr><th align="left">License</th><td>Proprietary</td></tr>
<tr><th align="left">Type</th><td>Desktop app, JetBrains extension</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Per seat (from $29)</td></tr>
<tr><th align="left">Programming Languages</th><td>-</td></tr>
</table>

Experience Claude AI without limits. Use our desktop app for everyday AI assistance, or boost your coding productivity with our JetBrains plugin.

<details>
<summary>Screenshots</summary>

![](./screenshots/claudemind/ClaudeMind_Desktop_Chat_History.png)
![](./screenshots/claudemind/ClaudeMind_Desktop_NewChatPage.png)
![](./screenshots/claudemind/ClaudeMind_Desktop_Projects.png)

</details>

### Cline

<table>
<tr><th align="left">GitHub</th><td>https://github.com/cline/cline</td></tr>
<tr><th align="left">Website</th><td>https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>VSCode extension</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

Cline can handle complex software development tasks step-by-step. With tools that let him create & edit files, explore large projects, use the browser, and execute terminal commands (after you grant permission), he can assist you in ways that go beyond code completion or tech support. Cline can even use the Model Context Protocol (MCP) to create new tools and extend his own capabilities. While autonomous AI scripts traditionally run in sandboxed environments, this extension provides a human-in-the-loop GUI to approve every file change and terminal command, providing a safe and accessible way to explore the potential of agentic AI.

<details>
<summary>Screenshots</summary>

![](./screenshots/cline/cline-demo.gif)

</details>

### console-chat-gpt

<table>
<tr><th align="left">GitHub</th><td>https://github.com/amidabuddha/console-chat-gpt</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>CLI</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Python</td></tr>
</table>

Enjoy seamless interactions with ChatGPT, MistralAI, Claude by Anthropic, Grok by xAI, Gemini by Google and DeepSeek directly from your command line. Elevate your chat experience with efficiency and ease.

<details>
<summary>Screenshots</summary>

![](./screenshots/console-chat-gpt/markdown_preview.gif)
![](./screenshots/console-chat-gpt/python_for_loop.gif)
![](./screenshots/console-chat-gpt/settings_preview.gif)

</details>

### Copilot-MCP

<table>
<tr><th align="left">GitHub</th><td>https://github.com/VikashLoomba/copilot-mcp</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>GPL-v3</td></tr>
<tr><th align="left">Type</th><td>VSCode Extension</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Any</td></tr>
</table>

VSCode extension that acts as a Model Context Protocol (MCP) client, enabling integration between MCP servers and GitHub Copilot Chat

<details>
<summary>Screenshots</summary>

![](./screenshots/copilot-mcp/preview.png)

</details>

### Cursor

<table>
<tr><th align="left">GitHub</th><td>https://github.com/getcursor/cursor</td></tr>
<tr><th align="left">Website</th><td>https://cursor.com</td></tr>
<tr><th align="left">License</th><td>Proprietary</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Freemium</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

Cursor is an AI-first code editor fork of VS Code that helps you code faster with built-in chat, edit, and debugging AI features. It supports MCP for enhanced AI capabilities and tool integration.

<details>
<summary>Screenshots</summary>

![Main Interface](./screenshots/cursor/cursor.png)
![Adding New MCP Server](./screenshots/cursor/new-server.png)
![Settings Interface](./screenshots/cursor/settings.png)
![Calling MCP Server](./screenshots/cursor/calling.png)
![MCP Server Response](./screenshots/cursor/called.png)

</details>

### Continue

<table>
<tr><th align="left">GitHub</th><td>https://github.com/continuedev/continue</td></tr>
<tr><th align="left">Website</th><td>https://continue.dev/</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>VSCode extension, JetBrains extension</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

Continue is the leading open-source AI code assistant. You can connect any models and any context to build custom autocomplete and chat experiences inside VS Code and JetBrains.

<details>
<summary>Screenshots</summary>

![](./screenshots/continue/continue-demo.gif)

</details>

### Goose

<table>
<tr><th align="left">GitHub</th><td>https://github.com/block/goose</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>AI Agent</td></tr>
<tr><th align="left">Platforms</th><td>MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Rust</td></tr>
</table>

Goose is a general-purpose AI agent that can dynamically plug into new extensions and learn how to use them. It solves higher-level problems using tools from multiple extensions and can interact with multiple extensions at once.

<details>
<summary>Screenshots</summary>

![Goose Logo](./screenshots/goose/goose.png)
![Custom Extension Chat](./screenshots/goose/custom-extension-chat.png)
![Custom Extension Tools](./screenshots/goose/custom-extension-tools-9d440447ae99b18ae92819e652148abe.png)
![Extension Settings](./screenshots/goose/extension%20settings.png)
![List Tools](./screenshots/goose/list%20tools.png)

</details>

### HyperChat

<table>
<tr><th align="left">GitHub</th><td>https://github.com/BigSweetPotatoStudio/HyperChat</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>Apache 2.0<a href="https://github.com/BigSweetPotatoStudio/HyperChat/blob/main/LICENSE">*</a></td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>JavaScript</td></tr>
</table>

HyperChat is an open Chat client that can use various LLM APIs to provide the best Chat experience and implement productivity tools through the MCP protocol.

<details>
<summary>Screenshots</summary>

![](./screenshots/hyperchat/image13.png)
![](./screenshots/hyperchat/image21.png)
![](./screenshots/hyperchat/image22.png)
![](./screenshots/hyperchat/image33.png)
![](./screenshots/hyperchat/image34.png)
![](./screenshots/hyperchat/image35.png)
![](./screenshots/hyperchat/image36.png)
![](./screenshots/hyperchat/image42.png)
![](./screenshots/hyperchat/image43.png)
![](./screenshots/hyperchat/image44.png)
![](./screenshots/hyperchat/image45.png)
![](./screenshots/hyperchat/image46.png)
![](./screenshots/hyperchat/image48.png)

</details>

### kibitz

<table>
<tr><th align="left">GitHub</th><td>https://github.com/nick1udwig/kibitz</td></tr>
<tr><th align="left">Website</th><td>https://kibi.tz</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>Mobile app, Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Mobile, Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

kibitiz is the free and open-source Replit. Minimally, it is a lightweight chat interface to the popular LLM APIs (Anthropic and OpenAI API formats supported). Experience automated tool loops: try asking your agent to use [wcgw](https://github.com/rusiaaman/wcgw) to make a change to a local repository, then fix linter and compiler errors, make a commit, and push to remote, all without user intervention! Even better, code on-the-go by setting up MCP servers on your laptop, then connecting from your mobile through [Kinode](https://github.com/kinode-dao/kinode).

<details>
<summary>Screenshots</summary>
  
https://github.com/user-attachments/assets/3f8df448-1c81-4ff2-8598-c48283a4dc00

</details>

### LibreChat

<table>
<tr><th align="left">GitHub</th><td>https://github.com/danny-avila/LibreChat</td></tr>
<tr><th align="left">Website</th><td>https://www.librechat.ai/</td></tr>
<tr><th align="left">License</th><td>MIT license</td></tr>
<tr><th align="left">Type</th><td>Web app</td></tr>
<tr><th align="left">Platforms</th><td>-</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

Enhanced ChatGPT Clone: Features Agents, Anthropic, AWS, OpenAI, Assistants API, Azure, Groq, o1, GPT-4o, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, AI model switching, message search, Code Interpreter, langchain, DALL-E-3, OpenAPI Actions, Functions, Secure Multi-User Auth, Presets, open-source for self-hosting.

<details>
<summary>Screenshots</summary>

![](./screenshots/librechat/librechat.webp)

</details>

### MCP Chatbot

<table>
<tr><th align="left">GitHub</th><td>https://github.com/3choff/mcp-chatbot</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>CLI</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Python</td></tr>
</table>

This chatbot example demonstrates how to integrate the Model Context Protocol (MCP) into a simple CLI chatbot. The implementation showcases MCP's flexibility by supporting multiple tools through MCP servers and is compatible with any LLM provider that follows OpenAI API standards.

### MCP CLI client

<table>
<tr><th align="left">GitHub</th><td>https://github.com/adhikasp/mcp-client-cli</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>CLI</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Python</td></tr>
</table>

A simple CLI to run LLM prompt and implement MCP client.

<details>
<summary>Screenshots</summary>

![](./screenshots/mcp-cli-client/usage.png)

</details>

### MCP Simple Slackbot

<table>
<tr><th align="left">GitHub</th><td>https://github.com/sooperset/mcp-client-slackbot</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>Slack Bot</td></tr>
<tr><th align="left">Platforms</th><td>Slack</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Python</td></tr>
</table>

A simple Slack bot that uses LLMs and the Model Context Protocol (MCP) tools.

<details>
<summary>Screenshots</summary>

![](./screenshots/mcp-simple-slackbot/demo.gif)

</details>

### oterm

<table>
<tr><th align="left">GitHub</th><td>https://github.com/ggozad/oterm</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>CLI</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Python</td></tr>
</table>

A terminal client for Ollama, with support for MCP servers.

<details>
<summary>Screenshots</summary>

![](./screenshots/oterm/chat.png)
![](./screenshots/oterm/mcp.svg)

</details>

### Superinterface

<table>
<tr><th align="left">GitHub</th><td>https://github.com/supercorp-ai/superinterface</td></tr>
<tr><th align="left">Website</th><td>https://superinterface.ai</td></tr>
<tr><th align="left">License</th><td>Proprietary</td></tr>
<tr><th align="left">Type</th><td>Web app</td></tr>
<tr><th align="left">Platforms</th><td>Web</td></tr>
<tr><th align="left">Pricing</th><td>Freemium</td></tr>
<tr><th align="left">Programming Languages</th><td>TypeScript</td></tr>
</table>

Superinterface is AI infrastructure and a developer platform to build in-app AI assistants with support for MCP, interactive components, client-side function calling and more.

Key features:

- Use tools from MCP servers in assistants embedded via React components or script tags
- SSE transport support
- Use any AI model from any AI provider (OpenAI, Anthropic, Ollama, others)

<details>
<summary>Screenshots</summary>

![](./screenshots/superinterface/mcp-chat.png)
![](./screenshots/superinterface/interfaces.png)
![](./screenshots/superinterface/setup-1.png)
![](./screenshots/superinterface/setup-2.png)
![](./screenshots/superinterface/setup-3.png)

</details>

### SeekChat

<table>
<tr><th align="left">GitHub</th><td>https://github.com/seekrays/seekchat</td></tr>
<tr><th align="left">Website</th><td>https://seekrays.com/chat/</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Javascript</td></tr>
</table>

✨ A Sleek and Powerful AI Chat Desktop Application ✨

SeekChat supports MCP tool execution, enabling AI to directly control your computer and perform various tasks. Easily automate file management, data analysis, code development, and more, turning AI into a truly intelligent assistant.

<details>
<summary>Screenshots</summary>

![](./screenshots/seekchat/screenshot-chat.png)
![](./screenshots/seekchat/screenshot-setting-mcp.png)
</details>

### Tester MCP Client

<table>
<tr><th align="left">GitHub</th><td>https://github.com/apify/tester-mcp-client</td></tr>
<tr><th align="left">Website</th><td>https://apify.com/jiri.spilka/tester-mcp-client</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>Web app</td></tr>
<tr><th align="left">Platforms</th><td>Web</td></tr>
<tr><th align="left">Pricing</th><td>Freemium</td></tr>
<tr><th align="left">Programming Languages</th><td>JavaScript</td></tr>
</table>

A client that connects to any MCP server using Server-Sent Events (SSE) and displays conversations in a chat-like UI.  
It is a standalone Apify Actor for testing MCP servers over SSE, with support for Authorization headers.  
Built with plain JavaScript (old-school style) and hosted on Apify, it requires no setup to run.  

Key features:

- Connects to any MCP server via Server-Sent Events (SSE).  
- Works with the [Apify MCP Server](https://apify.com/apify/actors-mcp-server) to interact with one or more Apify [Actors](https://apify.com/store).  
- Dynamically utilizes tools based on context and user queries (if supported by the server).  
- Open-source—review, suggest improvements, or modify as needed.

<details>
<summary>Screenshots</summary>

![](./screenshots/tester-mcp-client/setup.png)
![](./screenshots/tester-mcp-client/chat-ui.png)

</details>

### Witsy

<table>
<tr><th align="left">GitHub</th><td>https://github.com/nbonamy/witsy</td></tr>
<tr><th align="left">Website</th><td>https://witsyai.com</td></tr>
<tr><th align="left">License</th><td>Apache 2.0</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Typescript, Vue</td></tr>
</table>

Witsy is an AI desktop assistant supporting models from all major providers and one keyboard shortcut away!

<details>
<summary>Screenshots</summary>

![](./screenshots/witsy/main.jpg)
![](./screenshots/witsy/mcp.jpg)

</details>

### Enconvo

<table>
<tr><th align="left">GitHub</th><td>https://github.com/Enconvo</td></tr>
<tr><th align="left">Website</th><td>https://enconvo.com</td></tr>
<tr><th align="left">License</th><td>Proprietary</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td> MacOS </td></tr>
<tr><th align="left">Pricing</th><td>Freemium</td></tr>
<tr><th align="left">Programming Languages</th><td>Typescript, Python , Swift</td></tr>
</table>

Enconvo is your AI Agent Launcher that revolutionizes productivity. With instant access, automate your daily tasks effortlessly. Our intelligent AI Agent system, powered by 150+ built-in tools and MCP support, learns and adapts to your workflow. Experience seamless automation and enhanced productivity with the most versatile AI assistant for macOS.

<details>
<summary>Screenshots</summary>

![](./screenshots/enconvo/agent_use_mcp.png)
![](./screenshots/enconvo/mcp_config.png)

</details>

### y-cli

<table>
<tr><th align="left">GitHub</th><td>https://github.com/luohy15/y-cli</td></tr>
<tr><th align="left">Website</th><td>-</td></tr>
<tr><th align="left">License</th><td>MIT</td></tr>
<tr><th align="left">Type</th><td>CLI</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Python</td></tr>
</table>

A tiny command-line interface chat application that brings AI conversations to your terminal. Features include chat data storage in JSONL files, interactive chat interface, support for multiple bot configurations compatible with OpenAI chat completion streaming format, Deepseek-r1 reasoning content support, and MCP client support with multiple server configurations.

<details>
<summary>Screenshots</summary>

![Interactive Chat](./screenshots/y-cli/interactive-chat.png)
![MCP Server Configurations](./screenshots/y-cli/multi-mcp-server.png)
![MCP Demo](./screenshots/y-cli/mcp.gif)

</details>

### Zed

<table>
<tr><th align="left">GitHub</th><td>https://github.com/zed-industries/zed</td></tr>
<tr><th align="left">Website</th><td>https://zed.dev/</td></tr>
<tr><th align="left">License</th><td>GNU</td></tr>
<tr><th align="left">Type</th><td>Desktop app</td></tr>
<tr><th align="left">Platforms</th><td>Windows, MacOS, Linux</td></tr>
<tr><th align="left">Pricing</th><td>Free</td></tr>
<tr><th align="left">Programming Languages</th><td>Rust</td></tr>
</table>

Zed is a high-performance, multiplayer code editor from the creators of Atom and Tree-sitter.

<details>
<summary>Screenshots</summary>

https://github.com/user-attachments/assets/95624731-5469-4b58-a21f-bbb31d9838fa

</details>

## Servers

Looking for MCP servers? Check out the [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) repository.
