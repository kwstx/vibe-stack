# Vibe Stack (Engram Edition) 🛡️

**The safest way to Vibe Code.**

This is a high-performance Next.js 14 boilerplate designed for **AI-First work**. It comes pre-hardened against common AI hallucinations using the [Engram](https://marketplace.visualstudio.com/items?itemName=use-engram.engram) protocol.

## Why this stack?

1.  **Memory**: Uses a `.cursorrules` file optimized for Engram, teaching your AI to respect your mistake history.
2.  **Shadow Guard**: Includes a `.vscode/extensions.json` that automatically sets up local regression protection (Engram) for anyone on your team.
3.  **Speed**: Next.js App Router + Tailwind + TypeScript.

## Quick Start

1.  Clone this repo:
    ```bash
    git clone https://github.com/YOUR_USERNAME/vibe-stack.git
    ```
2.  Open in VS Code.
3.  **Click "Install"** when VS Code asks to install recommended extensions.
4.  Run `npm install && npm run dev`.

## How it works

The `.cursorrules` file instructs Cursor/Copilot to check for `engram_context.md`. If you fix a bug once, Engram remembers it locally. If the AI tries to make that mistake again, the Shadow Guard blocks it.

**License**: MIT. Hack away.
