## 🚀 Overview  
MCP-Server is a minimal, extensible Python server that follows the Model Context Protocol (MCP). It exposes server-side “tools” that can be called by MCP-compatible clients (e.g., LLM-powered agents).

This repository includes:  
- `main.py` — core MCP server implementation  
- `pyproject.toml` — Python packaging setup  
- `.python-version` — pinned Python version  
- Development notes and configuration files

## 🧰 Features  
- MCP-compatible tool discovery and tool invocation  
- Simple Python function → MCP tool interface  
- Easy extensibility for custom tools  
- Ready for local development or containerization
