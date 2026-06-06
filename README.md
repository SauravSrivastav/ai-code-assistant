# AI Code Assistant

> Intelligent coding assistant powered by **Code Llama** — available as both a Gradio web app and a Streamlit interface. Supports code generation, debugging, explanation, and multi-language programming assistance.

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Code Llama](https://img.shields.io/badge/Code_Llama-7B%2F13B%2F34B-FF6B35?style=flat-square)](https://ai.meta.com/llama/)
[![Gradio](https://img.shields.io/badge/Gradio-UI-FF7C00?style=flat-square&logo=gradio)](https://gradio.app)
[![Streamlit](https://img.shields.io/badge/Streamlit-UI-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Stars](https://img.shields.io/github/stars/SauravSrivastav/ai-code-assistant?style=flat-square)](https://github.com/SauravSrivastav/ai-code-assistant)

---

## Overview

This project provides two production-ready interfaces for **Code Llama** — Meta's state-of-the-art open-source code generation model. Built for developers who want a self-hosted, privacy-first AI coding assistant without API costs.

Supports **Python, JavaScript, TypeScript, Java, C++, C#, PHP, Bash** and more.

---

## Projects

| # | Interface | Description | Stack |
|---|-----------|-------------|-------|
| 01 | **Gradio Code Bot** | Fast, minimal coding assistant with chat interface | Code Llama · Gradio · Python |
| 02 | **Streamlit Code Bot** | Feature-rich IDE-style assistant with syntax highlighting | Code Llama · Streamlit · Python |

---

## Features

- **Code Generation** — Describe what you need, get working code instantly
- **Code Explanation** — Paste any code, get a clear explanation
- **Debugging Assistant** — Share errors, get targeted fixes
- **Multi-language Support** — Python, JS, TS, Java, C++, Go, Rust, PHP, Bash
- **Zero API Cost** — Runs locally on your machine or cloud VM
- **Privacy First** — Your code never leaves your environment

---

## Quick Start

### Prerequisites

```bash
pip install transformers accelerate bitsandbytes
pip install gradio streamlit
```

### Gradio Interface

```bash
cd Project01-Code\ Bot\ Using\ Gradio
pip install -r requirements.txt
python app.py
# Open: http://localhost:7860
```

### Streamlit Interface

```bash
cd Project02-Code\ Bot\ Using\ Streamlit
pip install -r requirements.txt
streamlit run app.py
# Open: http://localhost:8501
```

---

## Model Options

| Model | Parameters | Best For | VRAM Required |
|-------|-----------|----------|---------------|
| Code Llama 7B | 7B | Fast responses, low hardware | ~8GB |
| Code Llama 13B | 13B | Balanced performance | ~16GB |
| Code Llama 34B | 34B | Complex tasks, best quality | ~32GB |

---

## Architecture

```
ai-code-assistant/
├── Project01-Code Bot Using Gradio/    # Minimal chat interface
│   ├── app.py                          # Main Gradio app
│   └── requirements.txt
└── Project02-Code Bot Using Streamlit/ # Full-featured IDE assistant
    ├── app.py                          # Main Streamlit app
    └── requirements.txt
```

---

## Built By

**Saurav Srivastav** — Cloud & DevSecOps Leader | Azure · AKS · MLOps · LLMOps | Dubai, UAE

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sauravsrivastav2205/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0078D4?style=flat-square&logo=vercel)](https://saurav-srivastav-portfolio.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/SauravSrivastav)

---

## Related Projects

- [llama2-ai-toolkit](https://github.com/SauravSrivastav/llama2-ai-toolkit) — Llama 2 powered AI apps (SQL, Email, Invoice)
- [ultimate-mcp-setup-guide](https://github.com/SauravSrivastav/ultimate-mcp-setup-guide) — Best MCP servers for Claude Code
- [fridgefusion-st](https://github.com/SauravSrivastav/fridgefusion-st) — AI recipe generator with Gemini API

---

<sub>Code Llama · LLM · AI · MLOps · LLMOps · Python · Gradio · Streamlit · Coding Assistant · Generative AI · Azure AI · Dubai UAE</sub>
