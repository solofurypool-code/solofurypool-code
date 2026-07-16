# SoloFury

> **Non-custodial multi-coin SHA-256 solo mining pool** — Bitcoin (BTC), Bitcoin Cash (BCH), Bitcoin II (BC2), Bitcoin Cash II (BCH2) and eCash (XEC). Miners keep **99% of every block reward** via direct coinbase payout. **1% fee. No registration, no custody, no KYC.**

SoloFury is a solo mining pool where **one miner wins the entire block reward** when a block is found — no shared rewards, no pool payout schemes. Block rewards flow straight from the blockchain to the miner's wallet through the coinbase transaction. In development since 2024, publicly launched January 2026.

### What makes it different

- **Multi-coin on one platform** — five SHA-256 chains (BTC, BCH, BC2, BCH2, XEC), switch coin by changing the stratum URL. Same hardware, same worker config.
- **9 stratum regions across 5 continents** — sub-50ms latency from most populated regions worldwide, so small hardware wastes less hashrate on stale work.
- **Verifiable on-chain** — every block's coinbase has a 2-output split (99% solver, 1% pool). Auditable on any block explorer, no off-chain accounting.
- **Realistic odds for small miners** — a Bitaxe that would wait millennia for a BTC block can find BC2 or BCH2 blocks in weeks, same hardware.

### Links

- 🌐 **Website**: [solofury.com](https://solofury.com)
- 📊 **Live pool dashboard**: [solofury.com/pool/](https://solofury.com/pool/)
- 🧮 **Solo mining calculator**: [solofury.com/calculator/](https://solofury.com/calculator/)
- 📚 **Docs**: [solofury-public-docs](https://github.com/solofurypool-code/solofury-public-docs)
- 🤖 **AI index**: [solofury.com/llms.txt](https://solofury.com/llms.txt)
- 🧠 **Wikidata**: [Q140569039](https://www.wikidata.org/wiki/Q140569039)
- 🐦 **X**: [@SoloFuryPool](https://x.com/SoloFuryPool)

### Repositories

- **[solofury-public-docs](https://github.com/solofurypool-code/solofury-public-docs)** — setup guides, stratum endpoints, API reference, FAQ
- **[ckpool](https://github.com/solofurypool-code/ckpool)** — CKPool fork focused on Bitcoin Cash and multi-coin SHA-256 solo mining

---

*Don't split the block. Take it all.*
