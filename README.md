<h1 align="center">Prashant Chaudhari</h1>

<p align="center">
  <b>Frontend engineer building verifiable fintech on Solana: interfaces that show their work.</b>
</p>

<p align="center">
  <a href="https://prashantchaudhari.dev">prashantchaudhari.dev</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/pandaa880">X</a>
  &nbsp;·&nbsp;
  <a href="mailto:prashantchaudhari881@gmail.com">Email</a>
</p>

---

Senior frontend engineer based in Bengaluru, India. I work on **real-time trading UIs,
private-credit infrastructure, TEE-backed oracles, and on-chain attestation on Solana**.

## How I Think About Fintech Products

```txt
Private financial data -> verifiable computation (TEE) -> on-chain attestation -> UI anyone can check
```

Trust should be checkable, not claimed:

- Sensitive data stays private; only the minimum result leaves the enclave
- Every output carries a receipt a third party can verify independently
- Money is integers, never floats: paise, lamports, basis points
- Real-time UIs stream directly and degrade gracefully when feeds stall
- Systems are monitored in production, not just demoed

## Featured Project

**[TEE Income Oracle](https://github.com/pandaa880/tee-income-oracle)** · [live demo](https://tee-income-oracle-web.vercel.app)

Per-loan income receipts for NBFC funders. India's Account Aggregator bank data is checked
against a funder's criteria inside an AWS Nitro enclave; the resulting tier is attested on
Solana and verifiable by anyone.

- Stack: TypeScript, Rust, Solana (Anchor), AWS Nitro / Marlin Oyster, React + Vite
- Status (2026-10): v0.5.3, Colosseum hackathon entry, demo live with 30-min health monitor
- License: Apache-2.0

## Other Work

- **[depth-view](https://github.com/pandaa880/depth-view)**: real-time crypto market terminal (order book, trade tape, candles) streaming from Binance WebSocket, no backend. React, TypeScript.
- **[prashantchaudhari.dev](https://github.com/pandaa880/prashantchaudhari.dev)**: personal site and blog. Astro.
- **Writing:** [Money without floats: parsing rupees as integer paise](https://prashantchaudhari.dev/posts/money-without-floats) (2026-10)

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,vite,astro,tailwind,nodejs,rust,aws,vercel,githubactions,neovim&theme=dark"
       alt="TypeScript, JavaScript, React, Vite, Astro, Tailwind CSS, Node.js, Rust, AWS, Vercel, GitHub Actions, Neovim" />
</p>

Frontend: React, TypeScript, Vite, Astro, Tailwind · Web3: Solana (Anchor), on-chain attestation, TEEs (AWS Nitro) · Infra: Vercel, GitHub Actions

## Current Interests

- Private credit and lending rails on Solana
- TEE-backed oracles and verifiable off-chain computation
- India's Account Aggregator ecosystem
- High-frequency trading and market-data interfaces

## Contact

Open to remote Solana / fintech frontend roles and collaborations on verifiable credit infrastructure.
