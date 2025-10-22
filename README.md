# Awesome Privacy Protocols [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) ![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg)

A curated list of **Web3 privacy protocols**: networks, rollups, libraries, wallets, and infra focused on confidential transactions, private state, and metadata minimization.

> **Goal:** practical, no-nonsense directory. Clear sections per project, consistent attributes, and links that work.

---

## Table of Contents

* [Scope & Inclusion](#scope--inclusion)
* [Project Template (copy-paste)](#project-template-copy-paste)
* [Projects](#projects)
  * [Tornado Cash](#tornado-cash)
  * [Zcash](#zcash)
  * [Aztec](#aztec)
  * [Railgun](#railgun)
  * [Zama](#zama)
  * [Inco](#inco)
  * [0xBow](#0xbow)
  * [Nillion](#nillion)
  * [Oasis Network](#oasis-network)
  * [Arcium](#arcium)
  * [Fhenix](#fhenix)
* [Contributing](#contributing)

---

## Scope & Inclusion

**In-scope:** on-chain confidentiality (tx data, state), cryptographic privacy (ZK, FHE, MPC), TEE-assisted privacy, privacy wallets/UX, metadata-resistant infra, and interop for private state. Projects should have public docs or code.

**Out of scope:** generic non-Web3 privacy tools (VPNs, password managers), abandoned repos without usable artifacts, marketing-only pages.

---

## Project Template (copy-paste)

> Add new projects by copying this block and placing under **Projects**. Keep the one-liner crisp.

```markdown
### Project Name

**Summary:** One sentence on what it does and how it achieves privacy.

- **Website:** <url>
- **Docs:** <url>
- **Repo(s):** <url(s)>
- **Category:** (e.g., Privacy L1/L2, Private DeFi, Wallet/UX, Tooling/SDK, Infra)
- **Core Technology (Trust Model):** ZK | FHE | MPC | TEE | Hybrid
- **Chains / Targets:** (EVM, Cosmos, Solana, Multi, etc.)
```

---

## Projects

### Tornado Cash

**Summary:** Non-custodial mixer using zero-knowledge proofs to break transaction linkability between deposit and withdrawal addresses.

* **Website:** [https://tornado.cash](https://tornado.cash) (availability may vary)
* **Docs:** [https://docs.tornado.cash](https://docs.tornado.cash) (archival/mirrors may exist)
* **Repo(s):** [https://github.com/tornadocash](https://github.com/tornadocash)
* **Category:** Mixer
* **Core Technology (Trust Model):** ZK
* **Chains / Targets:** EVM

---

### Zcash

**Summary:** Layer-1 cryptocurrency with shielded transactions using zk-SNARKs; supports selective disclosure via viewing keys.

* **Website:** [https://z.cash](https://z.cash)
* **Docs:** [https://z.cash/learn/technology/](https://z.cash/learn/technology/)
* **Repo(s):** [https://github.com/zcash](https://github.com/zcash)
* **Category:** Privacy L1
* **Core Technology (Trust Model):** ZK
* **Chains / Targets:** Native L1

---

### Aztec

**Summary:** Privacy-preserving smart contract platform using zero-knowledge proofs with a custom programming model and rollup architecture.

* **Website:** [https://aztec.network](https://aztec.network)
* **Docs:** [https://docs.aztec.network](https://docs.aztec.network)
* **Repo(s):** [https://github.com/AztecProtocol](https://github.com/AztecProtocol)
* **Category:** Privacy L2, Tooling/SDK
* **Core Technology (Trust Model):** ZK
* **Chains / Targets:** EVM-aligned environment

---

### Railgun

**Summary:** Shielded account system for DeFi that enables private ERC-20 transfers and interactions via zero-knowledge proofs.

* **Website:** [https://railgun.org](https://railgun.org)
* **Docs:** [https://docs.railgun.org](https://docs.railgun.org)
* **Repo(s):** [https://github.com/Railgun-Community](https://github.com/Railgun-Community)
* **Category:** Private DeFi, Shielded Pools / Note Systems
* **Core Technology (Trust Model):** ZK
* **Chains / Targets:** EVM

---

### Zama

**Summary:** Open-source FHE tooling and infrastructure (TFHE-rs, Concrete) plus FHE-for-EVM stacks enabling encrypted smart contract logic.

* **Website:** [https://zama.ai](https://zama.ai)
* **Docs:** [https://docs.zama.ai](https://docs.zama.ai)
* **Repo(s):** [https://github.com/zama-ai](https://github.com/zama-ai)
* **Category:** Tooling/SDK, fhEVM / Coprocessor, Research
* **Core Technology (Trust Model):** FHE
* **Chains / Targets:** EVM integrations; general FHE libraries

---

### Inco

**Summary:** Based private rollup and tooling that brings encrypted computation to EVM chains; aims for composable, auditor-friendly flows.

* **Website:** [https://inco.org](https://inco.org)
* **Docs:** [https://docs.inco.org](https://docs.inco.org)
* **Repo(s):** [https://github.com/Inco-fhevm](https://github.com/Inco-fhevm)
* **Category:** Infra, Tooling/SDK
* **Core Technology (Trust Model):** TEE (+ FHE)
* **Chains / Targets:** EVM (multi-chain posture)

---

### 0xBow (Privacy Pools)

**Summary:** A zero-knowledge “privacy pool” system for Ethereum that enables private withdrawals while proving membership in a compliant association set—aiming to balance user privacy with illicit-flow screening. ([0xbow.io][1])

* **Website:** [https://0xbow.io](https://0xbow.io) • [https://privacypools.com](https://privacypools.com) ([0xbow.io][1])
* **Docs:** [https://docs.privacypools.com](https://docs.privacypools.com) ([docs.privacypools.com][2])
* **Repo(s):** [https://github.com/0xbow-io](https://github.com/0xbow-io)
* **Category:** Shielded Pools
* **Core Technology (Trust Model):** ZK
* **Chains / Targets:** Ethereum Mainnet

---

### Nillion

**Summary:** Privacy compute network implementing a novel MPC-like paradigm (Nil Message Compute) for decentralized private computation.

* **Website:** [https://www.nillion.com](https://www.nillion.com)
* **Docs:** [https://docs.nillion.com](https://docs.nillion.com)
* **Repo(s):** [https://github.com/NillionNetwork](https://github.com/NillionNetwork) (if/when public components available)
* **Category:** MPC Network / Compute, Tooling/SDK, Private AI
* **Core Technology:** MPC
* **Chains / Targets:** Nillion Network

---

### Oasis Network

**Summary:** Privacy-enabled L1 with ParaTimes (execution environments) including confidential EVM (e.g., Sapphire) and data tokenization.

* **Website:** [https://oasisprotocol.org](https://oasisprotocol.org)
* **Docs:** [https://docs.oasis.io](https://docs.oasis.io)
* **Repo(s):** [https://github.com/oasisprotocol](https://github.com/oasisprotocol)
* **Category:** Privacy L1, TEE-assisted Execution
* **Core Technology:** TEE + ZK (varies by ParaTime)
* **Chains / Targets:** Native L1 with EVM-compatible ParaTimes

---

### Arcium

**Summary:** Network for privacy-preserving data collaboration and compute, leveraging advanced MPC to run programs over private inputs.

* **Website:** [https://www.arcium.com](https://www.arcium.com)
* **Docs:** [https://docs.arcium.com/](https://docs.arcium.com/)
* **Repo(s):** [https://github.com/arcium-hq](https://github.com/arcium-hq)
* **Category:** MPC Network / Compute
* **Core Technology:** MPC
* **Chains / Targets:** Chain-agnostic integrations

---

### Fhenix

**Summary:** FHE-powered EVM-compatible environment for encrypted smart contracts, enabling contracts to compute directly on ciphertexts.

* **Website:** [https://www.fhenix.io](https://www.fhenix.io)
* **Docs:** [https://docs.fhenix.io](https://docs.fhenix.io)
* **Repo(s):** [https://github.com/fhenixprotocol](https://github.com/fhenixprotocol)
* **Category:** Privacy L2 / Rollup, Tooling/SDK
* **Core Technology:** FHE
* **Chains / Targets:** EVM

---

## Contributing

**PRs welcome!** Please:

1. Use the **Project Template** above for new entries.
2. Keep descriptions factual and concise; link to docs/papers/repos.
3. Place projects in the **order defined above** (adjust in PR if the list evolves).
4. If info is uncertain, mark fields `(TBD)` and open an Issue.
5. One project per section. Multi-repo orgs: link the org + primary repo.

---

*Inspired by the spirit of [awesome lists](https://awesome.re). Keep entries sharp, sources linked, and claims minimal.*
