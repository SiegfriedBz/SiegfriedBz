# Siegfried Bozza
### Full-Stack Engineer · React · Next.js · TypeScript · Web3 · AI Agents

Scientist-turned-engineer. Fifteen years in molecular biology (MSc.) and environmental engineering (MEng.) across France 🇫🇷, Canada 🇨🇦 and Switzerland 🇨🇭 — building fullstack software since 2022.

Currently Full-Stack Engineer at **Prismo.io** (Next.js / TypeScript, CQRS, hexagonal architecture, Supabase). Recent personal work: three end-to-end DApp case studies on Base and Ethereum Sepolia — Solidity + Foundry, Chainlink oracles, durable LangGraph + Inngest agents — and one full-stack Web2 auction platform.

📍 France · Open to remote roles and global relocation

[Portfolio](https://siegfried-bozza-portfolio-next.vercel.app) · [Articles](https://siegfried-bozza-portfolio-next.vercel.app/articles) · [LinkedIn](https://www.linkedin.com/in/siegfriedbozza) · [Email](mailto:siegfried.bozza@protonmail.com)

---

## Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React, Next.js (App Router), TypeScript, TanStack Query / Table, Zod, shadcn/ui, Tailwind CSS, nuqs, Recharts, Lingui |
| **Web3** | Solidity, Foundry, OpenZeppelin, Chainlink (VRF, Price Feeds, Automation), wagmi, viem, Reown AppKit, Alchemy, Tenderly, IPFS |
| **AI / Agents** | LangGraph.js, Inngest, Gemini, Exa AI |
| **Backend** | Supabase (Realtime, Edge Functions, CRON), Neon Postgres, Drizzle ORM, Stripe |
| **Testing** | Foundry, Vitest, Cypress, Jest |

---

## Recent Projects

### [BioVerify — Agentic DeSci DApp](#) · [Repo](https://github.com/SiegfriedBz/BioVerify_Agentic_DApp) · [Live](https://bio-verify-ai-dapp.vercel.app) · [Article](https://siegfried-bozza-portfolio-next.vercel.app/articles/bioverify)
*Peer review as a trust-minimised coordination game — deployed on Base Sepolia & Ethereum Sepolia.*

- Authors stake ETH; a LangGraph submission agent screens for plagiarism (Exa AI + Gemini); Chainlink VRF selects reviewers from the staked pool; human verdicts settle on-chain via EIP-712 signatures; research artifacts pinned to IPFS.
- Durable orchestration: Inngest `step.run` + LangGraph checkpointers carry multi-day human-in-the-loop review across serverless cold starts.
- Alchemy Notify webhooks (HMAC-SHA256) project contract events into Neon Postgres (Drizzle) via optimistic concurrency; viem WebSockets + TanStack Query drive the live UI.
- 50 Foundry tests across 12 suites — 100% lines / statements / branches / functions.

### [Bet2Gether — Chainlink-settled prediction market](#) · [Repo](https://github.com/SiegfriedBz/Bet2Gether-DApp) · [Live](https://bet2gether-alpha.vercel.app/)
*Oracle-driven settlement with time-weighted payouts — Ethereum Sepolia.*

- Chainlink Automation calls `performUpkeep` to resolve rounds at deadline without operator intervention; settlement reads Chainlink Price Feeds.
- Chainlink VRF v2.5 for unpredictable ERC-1155 reward token IDs; a Tenderly Web3 Action bridges resolution events to a role-gated mint. CEI pattern + OpenZeppelin `nonReentrant` on `claimReward`.

### [Forge — ERC-1155 crafting DApp](#) · [Repo](https://github.com/SiegfriedBz/Forge-DApp) · [Live](https://forge-tokens.vercel.app)
*Atomic burn–mint composition with 100% Foundry coverage on project-owned contracts.*

- Separate rules contract (Forge) vs ledger (FToken) with immutable ownership; composite IDs 3–6 minted via atomic `burnBatch` + `mint` in a single transaction. Cooldown-gated basic mints (IDs 0–2).
- Event-driven Next.js UI with wagmi, Alchemy WebSockets and TanStack Query.

### [GavL (Next Auctions) — Real-time auction platform](#) · [Repo](https://github.com/SiegfriedBz/Next-Auctions) · [Live](https://next-auctions.vercel.app/en)
*Real-time bidding with automated lifecycle and Stripe payments — full Web2 stack.*

- Supabase Realtime for live bids, CRON-triggered Edge Function for scheduled auction closure, Stripe webhooks for async payment state.
- i18n FR / EN / DE (Lingui), URL-driven filters (nuqs), TanStack Table, Recharts dashboards, Jest tests.

---

## Publications

- Dromard et al., [J. Neurosci. Res. 2008](https://pubmed.ncbi.nlm.nih.gov/18335522) — Stem cells · INSERM Montpellier, France
- Tanguay, Bozza, Breuil, [Fungal Genet. Biol. 2006](https://pubmed.ncbi.nlm.nih.gov/16859936/) — RNAi in *Ophiostoma* · UBC Vancouver, Canada
- Fisher et al., [Dev. Biol. 2010](https://pubmed.ncbi.nlm.nih.gov/19833123/) — Epigenetics · UBC Vancouver, Canada

---

## Background

Before software: environmental remediation project management (KIBAG, SERPOL, SITA/SUEZ — France & Switzerland) and genomic research (INSERM France, University of British Columbia). The habit of designing controlled experiments and stress-testing hypotheses transfers directly to smart-contract security and agent reliability.

---

## Interests & Target Roles

Web3 full-stack · Smart-contract engineering · Agentic / AI-augmented backends · DeSci

Available for full-time or part-time engagements — *remote or global relocation*
