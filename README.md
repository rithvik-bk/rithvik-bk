<h1 align="center">Rithvik Burki</h1>
<h3 align="center">I build the trust layer voice AI is missing — the machinery that decides whether an agent's action should fire, and the auth that lets it act at all.</h3>

<p align="center">Sophomore · BASIS Independent Silicon Valley · Silicon Valley, CA · <a href="mailto:rithvik1788@gmail.com">rithvik1788@gmail.com</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
</p>

---

### The VoiceOS suite — infrastructure for voice agents

A family of production-grade layers I built for a voice-AI platform, each attacking the same question from a different side: *why don't people trust AI to act for them yet — and what would fix it?*

- **[voiceos-oauth-engine](https://github.com/rithvik-bk/voiceos-oauth-engine)** · *Handshake* — one provider-agnostic OAuth engine: spoken "connect Slack" → the provider's own approval page → token minted straight into the macOS Keychain. Zero auth code per integration; 625 tests, zero runtime dependencies.
- **[voiceos-preverification](https://github.com/rithvik-bk/voiceos-preverification)** · *Preflight* — a deterministic, zero-LLM gate that runs before any irreversible action: every routing parameter (the who / where / how-much) must trace to something the user actually *said*. A type system on provenance — there is no classifier to fool.
- **[voiceos-eval](https://github.com/rithvik-bk/voiceos-eval)** — a tool-calling eval harness + pre-execution safety gate: scores whether the right tool was called with the right parameters, and blocks wrong money / recipient / destructive-target calls. Zero-dependency Node.
- **[voiceos-slack-integration](https://github.com/rithvik-bk/voiceos-slack-integration)** — real Slack work by voice: 16 tools, one-tap OAuth, zero lines of auth code — proof the engine drives the cost of the *next* integration to config, not code.

### Also shipped

- **[Mycelium](https://github.com/arav-rithvik/mycelium)** — a collective-intelligence MCP server: when one AI agent solves a task, it's distilled into a trust-scored, executable skill any other agent can discover and reuse. *npm for agent knowledge.* w/ Arav Dharnikota
- **[Whyboard](https://github.com/arav-rithvik/whyboard)** — say *"open a whiteboard and explain transformers"* and a glass lightboard opens beside your call: a live AI tutor draws while it talks, in realtime. w/ Arav Dharnikota
- **Aneurysm-rupture ML** — a clinical-feature model predicting intracranial aneurysm rupture risk (AUC 0.834), presented at Bay Area science fairs.

### Now

Building an agentic research pipeline that mines NeurIPS / ICML / ICLR review data at corpus scale — measuring what actually separates accepted papers from rejected ones, and hunting an open problem worth a year of work. Public research log lands here soon.
