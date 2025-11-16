# 🗒️ AI Sticky Notes — MCP Server

A lightweight **Model Context Protocol (MCP)** server that exposes a simple “sticky notes” system through **tools**, **resources**, and **prompts**.  
This server demonstrates how to build an MCP-compatible backend using **FastMCP**, enabling any MCP-enabled client (LLMs, agents, RAG systems) to read, write, and summarize notes.

---

## 🚀 Features

This MCP server provides four main capabilities:

### 🧰 Tools
| Tool | Description |
|------|-------------|
| `add_note(message: str)` | Appends a new note to `notes.txt` |
| `read_notes()` | Returns all notes as a single text block |

### 📦 Resources
| Resource | URI | Description |
|----------|-----|-------------|
| `notes://latest` | Returns the most recently added note |

### 💬 Prompts
| Prompt | Description |
|--------|-------------|
| `note_summary_prompt()` | Returns a ready-to-use prompt instructing an AI to summarize all notes |

---

## 📂 How It Works

The server stores notes in a local text file: notes.txt
All interactions—adding notes, reading them, getting the latest note, and generating an AI summary prompt—are routed through MCP.




