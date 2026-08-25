<h1 align="center">Rithvik Burki</h1>
<h3 align="center">I build the trust layer voice AI is missing: the machinery that decides whether an agent's action should fire, and the auth that lets it act at all.</h3>

<p align="center">I love building end-to-end automation systems: pipelines where the entire job runs itself.</p>

<p align="center">Silicon Valley, CA · <a href="mailto:rithvik1788@gmail.com">rithvik1788@gmail.com</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white">
</p>

---

## Projects with VoiceOS

### [VoiceOS Native OAuth Engine](https://github.com/rithvik-bk/voiceos-oauth-engine) · `auth infrastructure`
- Build custom VoiceOS integrations with real OAuth. No Composio, no third-party broker.
- Say "connect Slack": the provider's own approval page opens, the token is minted straight into the macOS Keychain.
- One config file per provider. Zero auth code per integration. 625 tests.
- [Read the docs](https://github.com/rithvik-bk/voiceos-oauth-engine/blob/main/docs/GETTING-STARTED.md) to build on it.

### [VoiceOS Pre-Verification](https://github.com/rithvik-bk/voiceos-preverification) · `AI trust infrastructure`
- A deterministic gate that runs before a voice agent fires any irreversible action.
- Every routing parameter (recipient, amount, destination) must trace to something the user actually said, or the call does not fire.
- Zero LLM in the hot path: same input, same verdict, in microseconds.
- Drops in front of any MCP tool server in shadow mode. Catches wrong-target calls without changing your product.

### [Downloadable Slack Integration](https://github.com/rithvik-bk/voiceos-slack-integration) · `voice productivity`
- Real Slack work by voice: catch-up digests, read, search, send, schedule, threads, status.
- 16 tools. One-tap OAuth on Slack's own approval page. Zero lines of auth code.

## Machine Learning

### [Aneurysm Rupture ML](https://github.com/rithvik-bk/aneurysm-rupture-ml) · `research`
- Predicts cerebral aneurysm rupture risk: **AUC 0.834, 80% sensitivity**, with per-patient explanations.
- Automated end to end: patient geometry → CFD driven through the SimScale API → interpretable ML. Zero specialist personnel in the loop.
- Replaces a commercial workflow that costs $20k to $40k a year and takes hours per case. This one is free and takes about 24 minutes per aneurysm.
- 🥇 **1st place, Biomedical Engineering, Silicon Valley (Synopsys) regional**
- 🏅 **5th in California, Medicine and Physiology, California Science and Engineering Fair**
- 📄 [Read the research paper](https://github.com/rithvik-bk/aneurysm-rupture-ml/blob/main/paper.pdf)

## Personal Projects

### [Mycelium](https://github.com/arav-rithvik/mycelium) · `dev tool`
- Collective intelligence for AI agents: solve a task once, and it becomes a trust-scored, executable skill any agent can discover and reuse.
- npm for agent knowledge. Built with Arav Dharnikota.

### [Whyboard](https://github.com/arav-rithvik/whyboard) · `ed tech`
- Say "open a whiteboard and explain transformers": a glass lightboard opens beside your call.
- A live AI tutor draws while it talks, in realtime. Built with Arav Dharnikota.
