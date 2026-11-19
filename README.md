<div align="center">

# LLM Playground

A fast, minimal AI playground powered by Groq.

[Live Demo](https://llm-playground-mu.vercel.app/)

</div>

<br />

## Overview

LLM Playground is a clean black-and-white interface for testing Groq language models directly in the browser. Add your own API key for the current session, write a prompt, tune the response settings, and inspect performance metrics.

## Features

- GPT-OSS 120B selected by default
- Bring-your-own Groq API key
- Session-only API key handling
- Model switching
- Temperature control
- Reasoning-level control for GPT-OSS
- Built-in browser search option
- Request code preview
- Latency and token-usage metrics
- Clear chat control
- Responsive interface
- Single-file static deployment, ready for Vercel

## Getting Started

1. Visit the [live playground](https://llm-playground-mu.vercel.app/).
2. Open the menu in the top-right corner.
3. Paste your Groq API key.
4. Click **Add key for this session**.
5. Send a prompt.

Your API key is used only for the active browser session. Reloading or closing the page clears it.

## Controls

| Control | Purpose |
| --- | --- |
| Model | Select the Groq model used for chat |
| Temperature | Adjust response creativity |
| Reasoning level | Set GPT-OSS reasoning depth |
| Browser search | Enable Groq browser search with supported GPT-OSS models |
| View code | Preview the generated API request structure |
| Latency | Shows the last request duration |
| Tokens used | Shows total tokens from the last response |

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Groq Chat Completions API
- Vercel

## Run Locally

Clone the project and open `index.html` in a browser.

```bash
git clone <your-repository-url>
cd <your-repository-name>
open index.html
