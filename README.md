# Brian Sparker: AI agents, MCP servers & macOS apps

**Product @ [You.com](https://you.com).** I build open-source AI-agent infrastructure, MCP (Model Context Protocol) tools, and native macOS utilities for people who want their software to feel faster, cheaper, and more useful.

My work clusters around two ideas: making AI agents **more capable and portable**, and removing **everyday friction** from the software people use all day.

[![Website](https://img.shields.io/badge/sparker.ai-000000?style=for-the-badge&logo=safari&logoColor=white)](https://sparker.ai)
[![X](https://img.shields.io/badge/@PeerReview-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/PeerReview)
[![You.com](https://img.shields.io/badge/building_at_You.com-6C47FF?style=for-the-badge)](https://you.com)

---

## ⭐ Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [you.md](https://github.com/brainsparker/you.md)
**Stop reintroducing yourself to AI.**

An open protocol for portable AI context: one human-readable Markdown file that tells Claude, Cursor, Windsurf, Codex, Gemini, and any `AGENTS.md` agent how you think, work, and want to be helped. Local-first, user-owned, versioned in Git.

```text
~/.you.md ─┬─ MCP ────→ Claude · Cursor · Windsurf
           └─ export ─→ CLAUDE.md · AGENTS.md · GEMINI.md
```

```bash
npm i -g @brainsparker/you-md
you-md init -i ~/.you.md && you-md skill install
```

[![npm](https://img.shields.io/npm/v/@brainsparker/you-md?logo=npm&color=cb3837)](https://www.npmjs.com/package/@brainsparker/you-md)
[![Stars](https://img.shields.io/github/stars/brainsparker/you.md?style=flat&logo=github)](https://github.com/brainsparker/you.md/stargazers)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-blue)

</td>
<td width="50%" valign="top">

### [SuperPaste](https://github.com/brainsparker/superpaste)
**Press ⌥V. The right text appears wherever you're typing.**

A native macOS AI paste app. One hotkey captures the active window, generates the right reply (a Slack message, an email, the next line of code), and pastes it at your cursor. No app switching, no prompting.

```text
cursor in any text field
  → ⌥V
  → active window captured
  → AI writes the reply
  → pasted in place
```

Bring your own key (Anthropic, OpenAI, OpenRouter, or local models via Ollama / LM Studio) and it's free. No telemetry.

[![Download](https://img.shields.io/badge/Download-macOS_DMG-000000?logo=apple&logoColor=white)](https://github.com/brainsparker/superpaste/releases/latest/download/SuperPaste.dmg)
[![Release](https://img.shields.io/github/v/release/brainsparker/superpaste?logo=github)](https://github.com/brainsparker/superpaste/releases/latest)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-lightgrey?logo=apple)
[![superpaste.ai](https://img.shields.io/badge/superpaste.ai-site-111111)](https://superpaste.ai)

</td>
</tr>
</table>

## 🔭 Also building

| Project | What it does |
| --- | --- |
| **[YouAgent](https://github.com/brainsparker/youagent)** | CLI-first, open-source AI agent framework with A2A agent cards, You.com web search, and knowledge graphs |
| **[frugal](https://github.com/brainsparker/frugal)** | Open routing layer for AI tools: an MCP server that routes agent tool calls (search, extract, browse) across 8 providers by cost, latency, and policy, with failover. One Go binary, BYOK |
| **[MCP-Profiles](https://github.com/brainsparker/MCP-Profiles)** | Context-aware web search MCP server that reads your project's `AGENTS.md` and turns it into agent-shaped queries (`npx -y @brainsparker/you-aware`) |
| **[PromptLens](https://github.com/brainsparker/PromptLens)** | Lightweight open-source prompt & LLM agent evaluation tool |
| **[youcom-haystack](https://github.com/brainsparker/youcom-haystack)** | You.com web search component for Haystack RAG pipelines, with a keyless free tier |
| **[skills](https://github.com/brainsparker/skills)** | Claude skills for product builders: GTM positioning, messaging & narrative |
| **[free-mail-merge](https://github.com/brainsparker/free-mail-merge)** | Upload a CSV → get a mail-merged PDF (great for mailing labels) |

## 🧪 You.com API examples

Small MIT-licensed apps and starters for building with the You.com Search and Research APIs. Start with **[you-101](https://github.com/brainsparker/you-101)**: seven runnable, zero-dependency scripts in Node and Python.

[you-deep-research](https://github.com/brainsparker/you-deep-research) · [you-chat](https://github.com/brainsparker/you-chat) · [you-fact-checker](https://github.com/brainsparker/you-fact-checker) · [you-sheets](https://github.com/brainsparker/you-sheets) · [you-company-researcher](https://github.com/brainsparker/you-company-researcher) · [you-market-researcher](https://github.com/brainsparker/you-market-researcher) · [you-news-brief](https://github.com/brainsparker/you-news-brief) · [you-site-research](https://github.com/brainsparker/you-site-research) · [you-meeting-prep](https://github.com/brainsparker/you-meeting-prep) · [you-app-template](https://github.com/brainsparker/you-app-template)

## 🧰 Mostly working in

![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111)
![A2A](https://img.shields.io/badge/A2A-111111)
![LLMs](https://img.shields.io/badge/LLMs-111111)
![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)

<!-- Optional: one stats card, dark theme to match a dark profile. Delete these two lines if you want it cleaner. -->
![Brian Sparker's GitHub stats](https://github-readme-stats.vercel.app/api?username=brainsparker&show_icons=true&count_private=true&hide_border=true&theme=github_dark)
