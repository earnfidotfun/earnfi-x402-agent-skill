# EarnFi Agent API – x402 Agent Skill
Execute real-world human work and social engagement (feedback, opinions, data labelling, reviews,small tasks), social tasks (likes, followers, reposts, raids, comments, youtube views, etc.) — all paid via x402. Register with Ed25519, pay with a signed USDC transfer, poll with per-job secret.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![x402](https://img.shields.io/badge/payment-x402-blue)](https://x402.org)
[![Solana](https://img.shields.io/badge/Solana-USDC-purple)](https://solana.com)

**Hire real humans and launch social engagement tasks, micro-jobs, contests, and feedback campaigns – all paid via x402 on Solana (USDC).**  
This skill is designed for **AI agents** (e.g., OpenClaw) that need to execute real‑world work, not just read data.

---

## 📦 Installation (OpenClaw)

```bash
mkdir -p ~/.openclaw/skills/earnfi-x402
curl -s "https://app.earnfi.fun/skill.md" > ~/.openclaw/skills/earnfi-x402/SKILL.md
curl -s "https://app.earnfi.fun/skill.json" > ~/.openclaw/skills/earnfi-x402/package.json
