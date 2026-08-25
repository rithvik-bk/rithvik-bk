<h1 align="center">Rithvik Burki</h1>

<p align="center"><b>1.</b> Building agentic infra and auth, focused on reliability, trust, and verification.<br><b>2.</b> Building end-to-end pipelines for AI-native automation, from agent harnesses to biomedical engineering.</p>

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

### [VoiceOS Native OAuth Engine](https://github.com/rithvik-bk/voiceos-oauth-engine) · `auth infra`
- Build custom VoiceOS integrations with real OAuth, no Composio and no third parties: say "Connect [App]" and the provider's own approval page opens, with the token minted straight into the macOS Keychain
- One config file per provider and zero auth code needed, held to 625 tests
- [Read the docs](https://github.com/rithvik-bk/voiceos-oauth-engine/blob/main/AGENTS.md), written so an AI agent can install and wire it for you end to end

### [VoiceOS Pre-Verification](https://github.com/rithvik-bk/voiceos-preverification) · `ai trust infra`
- A deterministic gate for VoiceOS that runs before an agent fires any irreversible action: every routing parameter (recipient, amount, destination) must trace back to a span of what the user actually said, blocking prompt injection structurally
- Pure string and number matching gives the same verdict for the same input in microseconds, wrapping any MCP tool server in shadow mode until you flip it to enforce
- [Read the docs](https://github.com/rithvik-bk/voiceos-preverification/blob/main/AGENTS.md), written so an AI agent can install and wire it for you end to end

### [Slack x VoiceOS Integration](https://github.com/rithvik-bk/voiceos-slack-integration) · `voice productivity`
- Use Slack by voice through VoiceOS: catch-up digests, read any channel or DM, search, send, schedule, reply in thread, set status
- 16 tools behind one-tap OAuth on Slack's own approval page, built on the VoiceOS Native OAuth Engine with zero lines of auth code

## ML/AI Research

### [Zero-Cost Machine Learning for Cerebral Aneurysm Rupture Prediction](https://github.com/rithvik-bk/aneurysm-ml-pipeline) · `research`
- Automated end-to-end pipeline for zero-cost detection of aneurysm rupture risk at **AUC 0.834 and 80% sensitivity**, with a per-patient explanation behind every decision
- Drives CFD through the SimScale API, feeds structural FEA, and trains an interpretable Random Forest with a SHAP explanation engine, replacing commercial workflows that cost $20k to $40k a year and take hours per case with a free pipeline that takes about 24 minutes per aneurysm
- 🥇 **1st Award, Biomedical Engineering @ Synopsys Silicon Valley**
- 🏅 **5th in California, Medicine & Physiology @ CSEF 2026**
- 📄 [Read the research paper](https://github.com/rithvik-bk/aneurysm-ml-pipeline/blob/main/PAPER.md)

## Personal Projects

### [Mycelium](https://github.com/arav-rithvik/mycelium) · `dev tool`
- Collective intelligence for AI agents: solve a task once, it becomes a skill any agent can reuse
- Skills earn live trust scores from real pass or fail outcomes, savings counted in tokens never generated
- npm for agent knowledge, built with Arav Dharnikota: [live demo](https://mycelium-mcp.vercel.app/)

### [Whyboard](https://github.com/arav-rithvik/whyboard) · `edtech`
- Say "open a whiteboard and explain transformers" and a glass lightboard opens beside your call
- A live AI tutor draws on it while it talks, one continuous performance driven by tool calls
- Built with Arav Dharnikota at the VoiceOS Hackathon, August 2026
