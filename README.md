# Changlu Liang — Web3 Frontend / Full-Stack Engineer

8 years shipping production frontends and full-stack products; the last three focused on Web3: wallets, on-chain payments, NFT minting, and event-verified backends. Currently Frontend Lead at **Heurist AI** (remote), taking heurist.ai from technology selection through production AI × Web3 workflows.

**Reach:** zhangwenzhu998@gmail.com

## What I do

- **dApps & wallets** — React/Next.js, Reown AppKit, WalletConnect, ethers.js v6; explicit modeling of account/network/chain drift, chain-switch error states, and post-reload transaction recovery
- **Smart contracts** — Solidity 0.8.x, OpenZeppelin 5, ERC-20/721, EIP-712 typed-data signing, Chainlink Data Feeds; contracts built test-first (fuzz + state coverage)
- **Backends for on-chain products** — Node.js/TypeScript, Koa2, Zod, PostgreSQL/SQLite; receipt- and event-verified crediting, idempotency keys (`chainId+txHash+logIndex`), `reserve → settle` billing with concurrency-safe conditional updates
- **Protocol engineering** — reading specs and contracts before building on them: state-machine audits, invariant-driven testing, responsible disclosures

## Featured work

- 🔭 **[xchain-lifecycle-explorer](https://github.com/flashclub/xchain-lifecycle-explorer)** — multi-chain event indexer + lifecycle reducer + anomaly detectors over a cross-chain intent protocol, born from a protocol audit that the Across Security team confirmed in writing. [Live dashboard](https://flashclub.github.io/xchain-lifecycle-explorer/).
- 🧾 **AI Compute Access NFT Gateway** — end-to-end Web3 product: ERC-721 gating, Chainlink-priced on-chain credits, API-key issuance, event-verified backend accounting, Cloudflare Workers + D1 at the edge. 20 contract/fuzz + 19 service tests.
- 🪙 **TSI Token** — ERC-20 with capped minting, pausing, two-step ownership, EIP-712 signed authorization; unified `_update` override so pause semantics govern every supply path.
- 🧩 **ChatGPT to Markdown** — Chrome extension, **19,000+ active users**, Chrome Web Store Featured, paid subscriptions (React/Next.js + Firebase).

## How I work

Test-first on anything that touches money; explicit state machines over inferred progress; public decisions over private conclusions (see any of my project READMEs — boundaries and trade-offs are documented, not hidden). Comfortable owning ambiguity: architecture, delivery, and production troubleshooting across time zones.

## Currently

Open to Web3 frontend / full-stack / protocol-adjacent roles. Recent security research: ERC-7683 integration defects disclosed to and confirmed by Across Protocol (informational, never-deployed code).
