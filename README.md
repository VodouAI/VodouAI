# Vodou

**Local-first AI memory and tools that follow you** — across ChatGPT, Claude, Cursor, and the rest of your stack.

Stop re-explaining yourself every time you switch assistants. Your facts, preferences, files, and tools live on **your machine**, then show up where you already work.

> Everyone else builds another chatbot. Vodou builds the layer underneath: memory and capability that stay yours when you change models, vendors, or tabs.

<p align="center">
  <a href="https://vodou.ai"><strong>vodou.ai</strong></a> ·
  <a href="https://app.vodou.ai"><strong>App</strong></a> ·
  <a href="https://chromewebstore.google.com/detail/vodou-bridge/ehlanbbiaeelnimkakfffehoahimkjjf"><strong>Chrome Bridge</strong></a> ·
  <a href="https://github.com/VodouAI/OS"><strong>Open source</strong></a> ·
  <a href="https://blog.vodou.ai"><strong>Blog</strong></a>
</p>

---

## What you can do

| | |
|---|---|
| **Memory that follows you** | Press **Ctrl+B** in ChatGPT, Claude, Gemini, Perplexity, Grok, Copilot, and other supported sites — relevant facts land in *their* composer. Same brain reaches Cursor, Claude Code, and other coding agents through hooks and rules files they already read. |
| **Own your history** | Import ChatGPT / Claude / Obsidian (and more). Pin what matters, correct what’s wrong, keep provenance so first-party memory outranks throwaway imports. Export portable packs when you want. |
| **Capture as you go** | [Vodou Bridge](https://chromewebstore.google.com/detail/vodou-bridge/ehlanbbiaeelnimkakfffehoahimkjjf) can save AI chats into your vault, show what you already know about the page you’re on, and take notes — talking only to your local gateway (`127.0.0.1`). |
| **Ask once, act** | Natural language → skills, MCP tools, and workflows. Connect Gmail, Slack, calendars, Notion, Linear, browsers, and more. See a plan before it runs; stop mid-run when it needs your call. |
| **Message it** | Telegram, Slack, Discord, and other channels — same memory, same tools, from your phone. |
| **Schedule & notice** | Heartbeats, automations, and proactive loops so Vodou can watch for things you care about — and show receipts for what it did. |
| **Your keys, or local** | Bring OpenAI / Anthropic / others — or run local models. Conversation content and memory stay on-device by default. |
| **Honest by design** | Every turn can leave a receipt (`memories · tools · skills`). Conflicts surface for *you* to settle. Graders answer **`unknown`**, never fake **`ok`**, when there’s no evidence. |

---

## How it fits together

```text
┌─────────────────────────────────────────────────────────┐
│  Surfaces you already use                               │
│  ChatGPT · Claude · Gemini · Cursor · Claude Code · …   │
│  Slack / Telegram · Console chat · MCP clients          │
└───────────────────────────┬─────────────────────────────┘
                            │  Bridge · hooks · MCP · channels
┌───────────────────────────▼─────────────────────────────┐
│  Vodou on your machine                                  │
│  Memory (local DB) · Skills · MCP tools · Scheduler     │
│  Receipts · vaults · leak policy · your keys            │
└─────────────────────────────────────────────────────────┘
```

1. **It captures** — chats, documents you add, facts you pin → a memory database on your computer.  
2. **It follows you** — browser extension, IDE hooks, MCP host, messaging.  
3. **It shows its work** — receipts, conflict review, evidence-graded hosts.

---

## Quick start

**Install (macOS / Linux):**

```bash
curl -fsSL https://raw.githubusercontent.com/VodouAI/OS/main/install-vodou.sh | bash
```

**Windows (beta):**

```powershell
irm https://raw.githubusercontent.com/VodouAI/OS/main/install-vodou.ps1 | iex
```

Then:

1. Finish the setup wizard at [app.vodou.ai](https://app.vodou.ai) (account licenses the engine — **memory stays local**).  
2. Install **[Vodou Bridge](https://chromewebstore.google.com/detail/vodou-bridge/ehlanbbiaeelnimkakfffehoahimkjjf)** from the Chrome Web Store.  
3. Pin one fact. Open ChatGPT or Claude. Hit **Ctrl+B**. Send.

Full walkthrough, architecture, and CLI: **[VodouAI/OS](https://github.com/VodouAI/OS)**.

---

## Repositories

| Repo | What it is |
|---|---|
| **[OS](https://github.com/VodouAI/OS)** | Public open tree — install, Console, Bridge materials, docs (start here) |
| **[vodou-core](https://github.com/VodouAI/vodou-core)** | Engine binaries / core releases |
| **[vodou-skills-catalog](https://github.com/VodouAI/vodou-skills-catalog)** | Public skills catalog |
| **[lenses-directory](https://github.com/VodouAI/lenses-directory)** | Community page-lenses index |

---

## Why this exists

Every AI you use has amnesia, and their memories don’t talk to each other. Built-in “memory” stays trapped in one vendor. Chat exporters move transcripts; they don’t run a governed brain under ChatGPT *and* Claude *and* your coding agent.

Vodou’s wedge: **own the memory layer**, then insert it where you already work — with tools and skills on the same local stack when you want to act, not only remember.

Public alpha — usable for people who live in multiple AIs; capture quality and surfaces keep improving in the open.

---

## Links

- Product: [vodou.ai](https://vodou.ai) · [app.vodou.ai](https://app.vodou.ai)  
- Bridge: [Chrome Web Store](https://chromewebstore.google.com/detail/vodou-bridge/ehlanbbiaeelnimkakfffehoahimkjjf)  
- Source: [github.com/VodouAI/OS](https://github.com/VodouAI/OS)  
- Engineering stories: [blog.vodou.ai](https://blog.vodou.ai)  
- Privacy: [app.vodou.ai/privacy](https://app.vodou.ai/privacy.html)

<p align="center">
  <sub>Local-first · Model-agnostic · You own the context</sub>
</p>
