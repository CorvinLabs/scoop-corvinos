# scoop-corvinos

Official [Scoop](https://scoop.sh) bucket for [CorvinOS](https://github.com/CorvinLabs/CorvinOS) on Windows.

## Install

```powershell
scoop bucket add corvinos https://github.com/CorvinLabs/scoop-corvinos
scoop install corvinos
```

**Requires Python 3.10+.** If not installed: `scoop install python`

Then:

```powershell
corvin-serve      # Start the web console
corvin-install    # Interactive bridge setup (Discord, Telegram, WhatsApp, Slack, Email)
```

## What is CorvinOS?

Self-hosted agentic AI assistant that connects local [Ollama](https://ollama.com) models
or cloud providers to Discord, Telegram, WhatsApp, Slack, and Email.

EU AI Act 2026 and GDPR compliance are structural — built into the architecture, not
configured on top of it.

- **GitHub:** https://github.com/CorvinLabs/CorvinOS
- **Docs:** https://corvin-labs.com/docs
- **PyPI:** https://pypi.org/project/corvinos/
