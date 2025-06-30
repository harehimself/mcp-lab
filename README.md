<p align="center">
   <img src="https://raw.githubusercontent.com/harehimself/mcp-lab/master/mcp-lab.png">
</p>
<p align="center">
   Lab for developing custom MCP (Multi-Component Protocol) servers integrated with AI tooling. Enables modular AI workflows via VS Code-compatible servers. Designed for one-person developers building structured agent pipelines. Supports prompt design, sampling control, and tool orchestration. Includes example agents and tools for rapid iteration. Great for creating and debugging advanced agent infrastructure.
</p>
<br>
<p align="center">
  <a href="https://github.com/harehimself/mcp-lab/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/harehimself/mcp-lab" alt="Contributors"></a>
  <a href="https://github.com/harehimself/mcp-lab/network/members">
    <img src="https://img.shields.io/github/forks/harehimself/mcp-lab" alt="Forks"></a>
  <a href="https://github.com/harehimself/mcp-lab/stargazers">
    <img src="https://img.shields.io/github/stars/harehimself/mcp-lab" alt="Stars"></a>
  <a href="https://github.com/harehimself/mcp-lab/issues">
    <img src="https://img.shields.io/github/issues/harehimself/mcp-lab" alt="Issues"></a>
  <a href="https://github.com/harehimself/mcp-lab/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/harehimself/mcp-lab" alt="MIT License"></a>
</p>

---

## Table of Contents
- [🔧 MCP Lab](#-mcp-lab)
  - [Features](#features)
  - [Installation](#installation)
  - [Quick Start](#quick-start)
  - [Project Structure](#project-structure)
  - [Example Servers](#example-servers)
  - [Benefits](#benefits)
  - [How It Compares](#how-it-compares)
  - [License](#license)

# 🔧 MCP Lab
A development environment for building and testing custom MCP (Multi-Component Protocol) servers that integrate seamlessly with AI tooling and VS Code-compatible environments.

## Features
- ✅ Custom MCP server development framework
- 🔄 VS Code and Claude Desktop integration
- 🧠 Structured agent pipeline architecture
- 🎯 Prompt design and sampling control
- 🛠️ Tool orchestration and debugging
- 📝 Example agents for rapid iteration
- 🔧 Modular AI workflow components

## Installation
1. Clone the repository:
```bash
git clone https://github.com/harehimself/mcp-lab.git
cd mcp-lab
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure your environment:
```bash
cp .env.example .env
# Edit .env with your API keys and settings
```

## Quick Start
1. Start a basic MCP server:
```bash
python src/servers/basic_server.py
```

2. Test server functionality:
```bash
python tests/test_server.py
```

3. Integrate with Claude Desktop by adding to your configuration:
```json
{
  "mcpServers": {
    "mcp-lab": {
      "command": "python",
      "args": ["path/to/mcp-lab/src/servers/main_server.py"]
    }
  }
}
```

## Project Structure
- `src/servers/`: MCP server implementations
- `src/tools/`: Custom tool definitions
- `src/agents/`: Example agent configurations
- `src/utils/`: Utility functions and helpers
- `tests/`: Testing framework and examples
- `examples/`: Sample workflows and integrations

## Example Servers
The lab includes several pre-built servers:

- **File Operations**: File system interaction and management
- **Database Tools**: Database query and manipulation tools
- **API Integration**: External API connection handlers
- **Data Processing**: Text and data transformation utilities
- **Code Analysis**: Code parsing and analysis tools

## Benefits
- Accelerates MCP server development with proven patterns
- Provides structured approach to agent pipeline creation
- Enables rapid prototyping and debugging of AI workflows
- Offers reusable components for common AI tasks
- Simplifies integration with existing development environments

## How It Compares
- Purpose-built for solo developers creating agent infrastructure
- Focuses on modularity and rapid iteration over enterprise features
- Lightweight alternative to complex agent frameworks
- Seamless VS Code and Claude Desktop integration
- Emphasizes debugging and development experience

## License
MIT License © 2025 [HareLabs](https://github.com/harehimself)
