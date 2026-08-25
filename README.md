<h1 align="center">Rithvik Burki</h1>
<h3 align="center">I build the trust layer voice AI is missing: the machinery that decides whether an agent's action should fire, and the auth that lets it act at all.</h3>

<p align="center">Silicon Valley, CA · <a href="mailto:rithvik1788@gmail.com">rithvik1788@gmail.com</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
</p>

---

### Projects: VoiceOS (YC X25)

Production infrastructure I built for VoiceOS, a YC-backed voice assistant platform.

- **[VoiceOS Native OAuth Engine](https://github.com/rithvik-bk/voiceos-oauth-engine)**. A native OAuth engine for building custom VoiceOS integrations without relying on Composio or any third-party broker. Say "connect Slack" and the provider's own approval page opens; the token is minted straight into the macOS Keychain and never touches an external server. One config file per provider, zero auth code per integration, 625 tests. [Read the docs](https://github.com/rithvik-bk/voiceos-oauth-engine/blob/main/docs/GETTING-STARTED.md) to build on it.
- **[VoiceOS Pre-verification](https://github.com/rithvik-bk/voiceos-preverification)**. A deterministic gate that runs before a voice agent fires any irreversible action. It checks that every routing parameter (the recipient, the amount, the destination) traces back to something the user actually said, and blocks the call if it cannot. No LLM in the hot path, so the same input always gives the same verdict in microseconds. Drop it in front of any MCP tool server in shadow mode and it starts catching wrong-target calls without changing your product.
- **[Downloadable Slack integration](https://github.com/rithvik-bk/voiceos-slack-integration)**. Real Slack work by voice: catch-up digests, read, search, send, schedule, threads, status. 16 tools, one-tap OAuth on Slack's own approval page, zero lines of auth code.

### Machine Learning

- **[Aneurysm Rupture ML](https://github.com/rithvik-bk/aneurysm-rupture-ml)**. A computational framework for rapid, zero-cost analysis of hemodynamic and structural factors in cerebral aneurysms. The accurate clinical tools cost tens of thousands of dollars per seat and take hours per case; this pipeline automates mesh generation and CFD through the SimScale API, extracts hemodynamic features, and predicts rupture risk at AUC 0.834 with 80% sensitivity, free, in 24 minutes per aneurysm, on any computer, with per-patient explanations. **1st place, Biomedical Engineering, Silicon Valley (Synopsys) regional. 5th in California, Medicine and Physiology, California Science and Engineering Fair.** [Research paper](https://github.com/rithvik-bk/aneurysm-rupture-ml/blob/main/paper.pdf).

### Also built

- **[Mycelium](https://github.com/arav-rithvik/mycelium)**. A collective-intelligence MCP server: when one AI agent solves a task, the solution is distilled into a trust-scored, executable skill that any other agent can discover, reuse, and verify. npm for agent knowledge. Built with Arav Dharnikota.
- **[Whyboard](https://github.com/arav-rithvik/whyboard)**. Say "open a whiteboard and explain transformers" and a glass lightboard opens beside your call: a live AI tutor draws while it talks, in realtime. Built with Arav Dharnikota.
