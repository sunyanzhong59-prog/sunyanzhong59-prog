# Hi, I'm MirSun (孙言中) 👋

🔐 Smart Contract Security Researcher & Bug Bounty Hunter
📍 China · Discord: `suiyanzhong5519`

I hunt vulnerabilities in Web3 protocols and turn my findings into reusable methodology.

## 🎯 Bounty Hunting Record

| Platform | Submission | Status | Severity |
|----------|-----------|--------|----------|
| Sherlock | #94828 (OZ Stellar) | ⏳ Pending | High |
| Cantina | #104 (Robinhood) | ⚠️ Invalid (Medium) | Medium |

**Discipline:**&#8203; zero PoC → never submit (Iron Rule §1)
**Methodology:**&#8203; 4-lens audit (second-layer / economic / permission / lifecycle)

## 📚 Open Datasets (Apache-2.0)

I publish training data so anyone can build auditors that reason like I do.

### 🤗 [smart-contract-audit-methodology](https://huggingface.co/datasets/sunyanzhong59-prog/smart-contract-audit-methodology)

18 battle-tested examples across 4 task types:

| File | What it teaches | Size |
|------|-----------------|------|
| `oz_stellar_94828_baseline.jsonl` | Soroban auth model + Critical → High downshift | 20 KB |
| `oz_community_n2_oos_baseline.jsonl` | Out-of-scope (Iron Rule §1.5) — what NOT to submit | 17 KB |
| `methodology_system_prompts.jsonl` | 11 core skills as system prompts | 99 KB |
| `failure_cases_negative_examples.jsonl` | 5 bugs that DON'T make it (admin trigger, false-positive CEI, etc.) | 31 KB |

Use it to: fine-tune a Solidity auditor · benchmark your tooling · adopt a 4-lens method.

## 🛠️ Stack

- **Lang:**&#8203; Solidity (main), Rust, Soroban, TypeScript
- **Frameworks:**&#8203; Foundry, Hardhat, Echidna, Aderyn (detector proposals)
- **Vuln classes covered:**&#8203; 48 known, applied across 4 real protocols (OUSD / OETH / Twyne / ModularAcctV2)

## 📫 Reach me

- Discord: `suiyanzhong5519`
- X: [@SunYanzhong61056](https://twitter.com/SunYanzhong61056)
- Email: sunyanzhong59@gmail.com
