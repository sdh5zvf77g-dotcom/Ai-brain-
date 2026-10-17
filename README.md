# Agent World

**Multi-AI agent workspace** — put a problem in, agents work on it independently, compare answers, save findings, and synthesize a stronger solution.

## Features

- **Multi-agent mode**: Select any combination of free (and paid) models; they solve the problem in parallel
- **Side-by-side comparison** of answers
- **Save findings** from each agent into a persistent evidence log
- **Synthesize** a single improved resolution from all agent answers
- **Scientific roles** (Methodologist, Skeptic, etc.) that stack onto queries
- **Workflow templates** (Hypothesis, Appraisal, Methods, Uncertainty…)
- **Auto-save** of conversation, findings, and endpoint settings (localStorage)
- Works as a **Progressive Web App** on iPhone (Add to Home Screen)

## Included free endpoints (OpenRouter)

- OpenRouter Free (auto-router)
- Nemotron 3 Ultra / Super / 3.5 Lightning
- Gemma 4 31B
- Inkling
- North Mini Code
- Qwen3.8 27B (free)
- Qwen3.8 Max (paid)
- Ollama Local

Each agent has its own settings (URL, model, API key). Paste an OpenRouter key once and the free models work.

## Quick start

1. Open `agent-world.html` in a browser (or serve the folder).
2. Tap **⚙** on any free agent and paste your [OpenRouter](https://openrouter.ai/) API key.
3. Switch to **Multi-agent**, select agents (green checks), type a problem, send.
4. Compare answers → **Save finding** from useful ones → optionally **Synthesize**.

### iPhone 15 Pro Max / iOS

1. Open the page in Safari.
2. Share → **Add to Home Screen**.
3. The glowing brain icon will appear on your home screen.

## Files

```
agent-world.html          # Main app (single-file + icons)
manifest.webmanifest      # PWA manifest
icons/
  apple-touch-icon.png    # 180×180 (iOS home screen)
  icon-192.png
  icon-512.png
  icon-1024.png
  favicon-32.png
README.md
```

## License

Use freely. Agent World is user-controlled; it only calls the endpoints you configure and authorize.
