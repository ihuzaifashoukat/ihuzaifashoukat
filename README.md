# Huzaifa Shoukat

**Open-source engineer building AI agents, MCP servers, browser automation, and developer tools.**

I build the parts that still matter after the demo ends: tool boundaries, state, approvals, retrieval, packaging, docs, and the automation around them.

Most of my public work is in Python and TypeScript. I care about useful abstractions, safe automation, and software people can actually install and run.

[Website](https://huzaifashoukat.me) · [LinkedIn](https://www.linkedin.com/in/huzaifashoukat/) · [X](https://x.com/ihuzaifashoukat) · [Email](mailto:ihuzaifashoukat@gmail.com)

---

## Featured project: x-use

[![GitHub stars](https://img.shields.io/github/stars/ihuzaifashoukat/x-use?style=flat-square&logo=github&label=stars)](https://github.com/ihuzaifashoukat/x-use/stargazers)
[![PyPI](https://img.shields.io/pypi/v/x-use-mcp?style=flat-square&logo=pypi&label=PyPI)](https://pypi.org/project/x-use-mcp/)
[![CI](https://img.shields.io/github/actions/workflow/status/ihuzaifashoukat/x-use/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/ihuzaifashoukat/x-use/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/ihuzaifashoukat/x-use?style=flat-square)](https://github.com/ihuzaifashoukat/x-use/blob/main/LICENSE)

**An MCP server for X research, outreach, and inbox management. No X API key required.**

x-use connects AI agents to X through a Patchright Chromium browser using your own account session. Agents can research profiles, read conversations, prepare personalized messages, and manage posts and replies through structured tools.

**[Version 3.0.0](https://github.com/ihuzaifashoukat/x-use/releases/tag/v3.0.0) is live** on [PyPI](https://pypi.org/project/x-use-mcp/3.0.0/) and the official MCP Registry as `io.github.ihuzaifashoukat/x-use`.

- **70 MCP tools, seven prompts, and seven agent skills** for setup, research, engagement, inbox management, content, daily review, and threads
- **Structured inbox and notifications:** conversations, unread/read filters, message request folders, visible message context, and notification actors and links
- **Reviewed outreach and threads:** individual draft approval for DMs, follows, and thread starts, with durable progress for multi-post workflows
- **Multiple accounts:** isolated browser sessions, per-account personas and proxies, action budgets, and recovery records for uncertain writes
- **Agent integrations:** Claude Code plugin, skills for Claude Code and Codex, and stdio MCP support for Claude Desktop, Cursor, Windsurf, and other clients
- **Cross-platform CI:** Windows, macOS, and Linux on Python 3.10–3.14, including installed-package checks and synthetic browser tests with Patchright and Playwright

Install the package and its browser:

```bash
python -m pip install --upgrade x-use-mcp
python -m patchright install chromium
```

Requires Python 3.10+. Follow the [setup guide](https://github.com/ihuzaifashoukat/x-use#install) for uv-based setup, account configuration, and MCP client registration.

[Repository](https://github.com/ihuzaifashoukat/x-use) · [MCP guide](https://github.com/ihuzaifashoukat/x-use/blob/main/docs/MCP_GUIDE.md) · [Agent skills](https://github.com/ihuzaifashoukat/x-use#agent-skills) · [Claude Code plugin](https://github.com/ihuzaifashoukat/x-use/blob/main/plugins/x-use/README.md) · [Changelog](https://github.com/ihuzaifashoukat/x-use/blob/main/CHANGELOG.md)

---

## Open source

| Project | What it does |
| :--- | :--- |
| [SpliceDeck](https://github.com/ihuzaifashoukat/splicedeck) | Local-first video editor built for AI agents. MCP + CLI control for cuts, templates, captions, vertical clips, delivery, and human-gated editing memory. |
| [wpaudit](https://github.com/ihuzaifashoukat/wpaudit) | Modular WordPress security auditing. Coordinates Nmap, WPScan, Nuclei, SQLMap, reporting, and scan profiles. |
| [llmoptimizer](https://github.com/ihuzaifashoukat/llmoptimizer) | Generates `llms.txt` and AI-ready site context from live sites, sitemaps, static builds, and Markdown/MDX docs. |
| [free-ai-router](https://github.com/ihuzaifashoukat/free-ai-router) | Routes across 150+ free AI models from 20+ providers with automatic fallback when providers hit limits. |
| [seo-analyzer](https://github.com/ihuzaifashoukat/seo-analyzer) | Python toolkit for on-page, technical, and content SEO audits with CLI, crawling, exports, and a Flask API. |
| [wordpress-vulnerability-database](https://github.com/ihuzaifashoukat/wordpress-vulnerability-database) | Open WordPress vulnerability data covering 27,000+ plugin, theme, and core issues in SQLite, CSV, and Excel. |

---

## What I work on

- **AI agents & MCP**: tool design, agent interfaces, human-in-the-loop workflows, and multi-agent infrastructure
- **Browser automation**: reliable browser-native workflows for systems where APIs are limited, expensive, or incomplete
- **Retrieval systems**: RAG pipelines, vector search, grounding, and source-aware applications
- **Developer tooling**: CLIs, packages, automation, docs, testing, and distribution
- **Agent-native media**: MCP-driven video workflows, FFmpeg pipelines, transcription, templates, and human-gated automation
- **Security automation**: practical scanners, vulnerability data, and repeatable auditing workflows

---

## Tech

<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,ts,js,nextjs,react,nodejs,fastapi,flask,postgres,mysql,mongodb,supabase,docker,aws,git,github,vercel&perline=17" alt="Huzaifa Shoukat's tech stack" />
  </a>
</p>

**AI / agents:** MCP · RAG · LangChain · Agent tooling  
**Data / retrieval:** PostgreSQL · MySQL · MongoDB · Supabase · pgvector · FAISS · Pinecone · Vector search  
**Backend:** FastAPI · Flask · Node.js  
**Shipping:** Docker · GitHub Actions · PyPI · npm · AWS · Vercel

### Open-source activity

[![x-use stars](https://img.shields.io/github/stars/ihuzaifashoukat/x-use?style=flat-square&logo=github&label=x-use%20stars)](https://github.com/ihuzaifashoukat/x-use/stargazers)
[![x-use forks](https://img.shields.io/github/forks/ihuzaifashoukat/x-use?style=flat-square&logo=github&label=forks)](https://github.com/ihuzaifashoukat/x-use/network/members)
[![GitHub followers](https://img.shields.io/github/followers/ihuzaifashoukat?style=flat-square&logo=github&label=followers)](https://github.com/ihuzaifashoukat?tab=followers)
[![PyPI](https://img.shields.io/pypi/v/x-use-mcp?style=flat-square&logo=pypi&label=x-use-mcp)](https://pypi.org/project/x-use-mcp/)

---

## Build with me

Issues, bug reports, and pull requests are welcome across my repositories.

If you are working on MCP tooling, browser agents, developer infrastructure, retrieval systems, or open-source security tools, I am always interested in comparing notes.

**Open to open-source collaborations, contract engineering, and full-time roles.**

[Book a 30 minute call](https://calendly.com/ihuzaifashoukat/30min) · [Email me](mailto:ihuzaifashoukat@gmail.com)
