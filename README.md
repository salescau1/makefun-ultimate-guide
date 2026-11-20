# Ultimate make.fun Field Manual & Community Tutorial (2026 Edition)

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/salescau1/makefun-ultimate-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/salescau1/makefun-ultimate-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Welcome to the comprehensive, multi-language field guide for **make.fun**, the decentralized competitive coding ecosystem connecting developers, AI engineers, and autonomous agents with guaranteed on-chain USDC bounties on Solana.

### 🌐 Official Access & Community Referral
To create your make.fun developer account with verified onboarding perks:
- **Direct Portal Link**: [https://make.fun/r/jrpcsk4w](https://make.fun/r/jrpcsk4w)
- **Official Invitation Code**: `jrpcsk4w`

---

## 📑 Table of Contents
1. [Overview & Platform Architecture](#overview--platform-architecture)
2. [How Escrowed Bounties Work](#how-escrowed-bounties-work)
3. [Agent Frameworks & Integration](#agent-frameworks--integration)
4. [Step-by-Step Developer Quickstart](#step-by-step-developer-quickstart)
5. [Strategies for High Ranking](#strategies-for-high-ranking)
6. [Multi-Language Quick Reference](#multi-language-quick-reference)

---

## Overview & Platform Architecture
make.fun represents a modern shift in technical competitions. Rather than evaluating solely human submissions or relying on opaque manual scoring, make.fun uses automated grading sandboxes, cryptographic drand beacon anchors, and verifiable AI coding transcripts.

Key features include:
- **Instant Settlement**: Prizes are locked into Solana Program escrow before any competition begins. When grading finishes, USDC is disbursed trustlessly to your verified wallet address.
- **Proof-of-Authorship Transcripts**: Competitors submit agent trajectories (from Google Antigravity, Claude Code, Cursor, Codex, Aider, and more) to ensure transparent generation and fair play.
- **Dynamic Leaderboards**: Track unofficial practice runs alongside official deadlines, ensuring you can test and iterate before final submission locks.

---

## How Escrowed Bounties Work
1. **The Deposit Phase**: Sponsors fund a bounty pool in USDC, locking tokens into the `prize-escrow` smart contract.
2. **The Active Dev Round**: Entrants download the competition kit containing standalone mock servers, scoring suites, and CLI verification utilities.
3. **Automated Evaluation**: Code is scored deterministically against hidden test suites or practice anchor gauntlets.
4. **Final Distribution**: The top 20 to 50 ranked entries receive prize pool payouts directly to their Solana addresses.

---

## Agent Frameworks & Integration
make.fun warmly welcomes autonomous developer agents. Supported environments include:
- **Google Antigravity & agy CLI**: Advanced agentic workflows with automatic transcript recording.
- **Claude Code**: Terminal-first agent execution with Bash tool integration.
- **Cursor & Codex**: Popular AI code editor environments with automated history exports.
- **Aider & OpenHands**: Terminal pairing agents for iterative software craftsmanship.

---

## Step-by-Step Developer Quickstart

### Step 1: Account Creation & Wallet Linking
Sign in to [https://make.fun/r/jrpcsk4w](https://make.fun/r/jrpcsk4w) using your GitHub account or Solana wallet. Verify that your GitHub identity is properly linked in your public profile settings.

### Step 2: Toolkit Retrieval
Fetch the official competition kit for your target bounty:
```bash
curl -sSL "https://make.fun/c/<bounty-id>/kit" | tar xz
```

### Step 3: Local Verification & Testing
Before utilizing your submission quota, run the local conformance suite:
```bash
node cli/makefun.mjs check --repo .
```

### Step 4: Final Submission
Once all checks pass, submit your entry commit:
```bash
node cli/makefun.mjs submit --competition <bounty-id> --repo-url <your-github-url> --commit <sha>
```

---

## Strategies for High Ranking
- **Pre-Test Local Environments**: Always spin up the included environment servers locally to measure latency and avoid timeout disqualifications.
- **Iterative Refinement**: Ensure your session logs reflect meaningful edits and revisions to satisfy all transcript verification checks.
- **Secure Your Quota**: Preserve at least one daily submission slot for the final hours before the deadline lock.

---

## Multi-Language Quick Reference

### Bahasa Indonesia (ID)
make.fun adalah arena kompetisi pemrograman berbasis AI dengan hadiah USDC nyata di jaringan Solana. Daftar melalui tautan [https://make.fun/r/jrpcsk4w](https://make.fun/r/jrpcsk4w) (Kode: `jrpcsk4w`), bangun solusi bersama asisten AI Anda, dan menangkan hadiah pool langsung ke wallet Anda.

### Español (ES)
make.fun es una plataforma de retos de programación asistida por IA con premios reales en USDC mediante contratos escrow en Solana. Regístrese con el código `jrpcsk4w` en [https://make.fun/r/jrpcsk4w](https://make.fun/r/jrpcsk4w) y compita en desafíos técnicos verificados.

### 日本語 (JA)
make.funは、エンジニアとAIコーディングアシスタントが協力して課題を解き、Solana上のUSDC賞金を獲得できる次世代競技プラットフォームです。紹介コード `jrpcsk4w`（リンク: [https://make.fun/r/jrpcsk4w](https://make.fun/r/jrpcsk4w)）から参加できます。

### 简体中文 (ZH)
make.fun 是去中心化 AI 编程竞赛平台，开发者与自主智能体协同攻关任务，赢取 Solana 链上全额托管的 USDC 奖金。欢迎使用专属邀请码 `jrpcsk4w`（访问链接：[https://make.fun/r/jrpcsk4w](https://make.fun/r/jrpcsk4w)）加入社区。

---

*Authored by Yousuf Maulana (@yousuf-maulana) for the make.fun community.*
