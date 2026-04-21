# 🔧 DevTools MCP

<div align="center">
  <img src="https://img.shields.io/badge/Status-Active-success.svg" alt="Status Active" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT" />
  <p><strong>A Model Context Protocol (MCP) server for deep Chrome DevTools integration with LLMs.</strong></p>
</div>

## ✨ Overview

DevTools MCP bridges the gap between Large Language Models and frontend debugging. By wrapping the Chrome DevTools Protocol (CDP) into an MCP server, it allows AI coding assistants to actively inspect the DOM, monitor network requests, evaluate JavaScript within the browser context, and take screenshots—all autonomously.

## 🚀 Key Capabilities

- **DOM Inspection**: Provide LLMs with real-time access to the DOM tree for accessibility and structure analysis.
- **Network Monitoring**: Intercept and analyze network requests and responses directly via the LLM.
- **Console Logs**: Capture and stream browser console logs (warnings, errors) to your AI agent.
- **JavaScript Execution**: Safely execute JavaScript in the browser context to test fixes or manipulate state.
- **Screenshots & Tracing**: Take automated screenshots and performance traces for diagnostic purposes.

## 📦 Installation

```bash
npm install -g devtools-mcp
```

## 🛠️ Configuration (Claude Desktop)

To use this with Claude Desktop or any other MCP client, add it to your configuration file (e.g., `~/.config/claude/config.json`):

```json
{
  "mcpServers": {
    "devtools-mcp": {
      "command": "npx",
      "args": ["devtools-mcp"]
    }
  }
}
```

## 💻 Usage Example

Once connected, your LLM can execute commands like:

*   "Take a snapshot of the currently active page."
*   "Monitor the network tab for failing API calls."
*   "Click the button with ID `submit-form`."
*   "Evaluate `document.title` and return the result."








---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Stackaura Hub](https://github.com/RanaAhmar/stackaura-hub)** - The central index for all 100 repositories.
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **LinkedIn:** [Ahmar Hussain](https://www.linkedin.com/in/ahmar204/)
- **Facebook:** [Ahmar Hussain](https://www.facebook.com/Ahmar204)
- **GitHub:** [@RanaAhmar](https://github.com/RanaAhmar)

---







