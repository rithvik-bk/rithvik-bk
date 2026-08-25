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
- Build custom VoiceOS integrations with real OAuth. No Composio, no third parties.
- Say "Connect [App]" and the provider's own approval page opens.
- The token is minted straight into the macOS Keychain.
- One config file per provider, zero auth code needed. Tested with 625 tests.
- [Read the docs.](https://github.com/rithvik-bk/voiceos-oauth-engine/blob/main/docs/GETTING-STARTED.md)

### [VoiceOS Pre-Verification](https://github.com/rithvik-bk/voiceos-preverification) · `ai trust infra`
- A deterministic gate for VoiceOS that runs before an agent fires any irreversible action.
- Provenance tracing: every routing parameter (recipient, amount, destination) must trace back to a span of what the user actually said. Content an agent reads can never become a destination, which structurally blocks prompt injection and hallucinated targets.
- Pure string and number matching over plain data: same input, same verdict, in microseconds, no added latency in the agent loop.
- Wraps any MCP tool server in shadow mode first: it logs what it would have caught, then you flip it to enforce.
- [Read the docs.](https://github.com/rithvik-bk/voiceos-preverification/blob/main/AGENTS.md) Written so an AI agent can install and wire it for you end to end.

### [Slack x VoiceOS Integration](https://github.com/rithvik-bk/voiceos-slack-integration) · `voice productivity`
- Use Slack by voice through VoiceOS.
- Catch-up digests, read any channel or DM, search, send, schedule, reply in thread, set status. 16 tools.
- One-tap OAuth on Slack's own approval page. Zero lines of auth code.

## ML/AI Research

### [Aneurysm ML Pipeline](https://github.com/rithvik-bk/aneurysm-ml-pipeline) · `research`
- Automated end-to-end pipeline for zero-cost detection of aneurysm rupture risk: **AUC 0.834, 80% sensitivity**, with per-patient explanations.
- Drives CFD through the SimScale API, feeds structural FEA, and trains an interpretable Random Forest with a SHAP explanation engine. Zero specialist personnel in the loop.
- Replaces commercial workflows that cost $20k to $40k a year and take hours per case. This one is free and takes about 24 minutes per aneurysm.
- 🥇 **1st Award, Biological Science and Engineering @ Synopsys Silicon Valley**
- 🏅 **5th in California, Medicine & Physiology @ CSEF 2026**
- 📄 [Read the research paper.](https://github.com/rithvik-bk/aneurysm-ml-pipeline/blob/main/PAPER.md)

## Personal Projects

### [Mycelium](https://github.com/arav-rithvik/mycelium) · `dev tool`
- Collective intelligence for AI agents. Solve a task once, and it becomes a named, versioned, executable skill any agent can discover and reuse.
- Every skill earns a live trust score from real pass or fail outcomes only, so good knowledge rises and broken knowledge fades, with no curator.
- Savings are counted in real tokens that were never generated, then converted to energy, water, and CO2 through published, cited factors.
- npm for agent knowledge. [Live demo.](https://mycelium-mcp.vercel.app/) Built with Arav Dharnikota.

### [Whyboard](https://github.com/arav-rithvik/whyboard) · `ed tech`
- Say "open a whiteboard and explain transformers": a glass lightboard opens beside your call.
- A live AI tutor drives the board through tool calls while it speaks, so the drawing and the explanation are one continuous performance.
- Built with Arav Dharnikota. Won at the VoiceOS Hackathon, August 2026.
