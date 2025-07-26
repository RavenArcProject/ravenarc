# 🛡️ RavenArc Vault Constitution v1.0

> “A vault for the Arc. A shield for the flame.”

---

## 📜 Summary

This document establishes the foundational rules, custody model, and signer quorum for the **RavenArc Vault**, a smart contract treasury deployed via [Safe{Wallet}](https://safe.global) on the Base L2 network.

The RavenArc Vault is designed to ensure resilience, transparency, and survivor-aligned stewardship of funds, assets, and mission-aligned actions.

---

## 🔐 Vault Metadata

- **Safe Name:** RavenArc Vault
- **Chain:** Base (Ethereum Layer 2)
- **Safe Address:** `0x38e3245138961e1018a957d97546d1568A33bA61`
- **ENS (Primary):** `ravenarc.eth`

---

## 🧱 Ownership & Signer Quorum

### 🧾 Threshold
- **Approval Required:** `2 of 3` signers must confirm any transaction.

### 👥 Signers

| # | Name         | Type           | Address                  | Notes |
|--|--------------|----------------|--------------------------|-------|
| 1 | RAVEN_LEDGER | Hardware Wallet (Ledger Nano X) | `0x...` | Cold storage |
| 2 | RAVEN_TREZOR | Hardware Wallet (Trezor Model T) | `0x...` | Cold storage |
| 3 | RAVEN_HOT | Hot Wallet (MetaMask)     | `0x...` | Operational wallet |

 

---

## 🧮 Vault Use and Philosophy

The RavenArc Vault exists to:

1. **Protect community funds** allocated toward:
   - Survivor relief
   - Artistic commissions and revenue sharing
   - Network infrastructure (Arc Lanterns, Arc Flares)
   - Legal, hosting, treasury or infrastructure operations

2. **Prevent unauthorized access**
   - No single signer can act unilaterally.
   - Lost or compromised keys do **not** result in total loss.

3. **Ensure graceful continuity**
   - Signers may be rotated by multisig vote (2 of 3)
   - Safe modules may be added to enhance future governance (e.g. Snapshot, Zodiac)

---

## 🔄 Rotation and Emergency Policy

If a signer becomes compromised, unreachable, or needs replacement:

1. Remaining two signers will:
   - Propose a signer removal and replacement
   - Approve via 2-of-3 vote
   - Log the rotation in this Constitution and/or vault changelog

2. In the event of total signer compromise:
   - Public emergency address recovery instructions will be broadcast via:
     - GitHub: `github.com/ravenarc`
     - ENS text records at `ravenarc.eth`
     - Signed statement via Mirror.xyz and/or IPFS

---

## 🏷️ Tagline and Symbolism

- **Symbol:** Raven flying with key in beak, flame below
- **Motto:** *Not your quorum, not your crypto.*
- **Hash Tagline (optional):** #VaultByArc

---

## ✅ Confirmed and Acknowledged

This constitution is ratified by the initial 2-of-3 multisig deployment and may be versioned in future by an on-chain or signed vote of the Vault’s owners.
