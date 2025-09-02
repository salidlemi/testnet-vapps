# vApp Proposal: NFT Mystery Box for USer

## Metadata
| Field           | Value                                                                 |
|-----------------|-----------------------------------------------------------------------|
| title           | NFT Mystery Box for USer                                              |
| NFT Collection  | Echoes of Soundness                                                   |
| category        | NFTs                                                                  |
| developer       | Salidlemi                                                             |
| githubUsername  | Salidlemi                                                             |
| discordId       | 849556380041084928                                                    |
| short tagline   | A next-gen NFT mystery box powered by Soundness Layer                 |

---

## Summary
**NFT Mystery Box for USer** is an experimental NFT collection that combines the excitement of mystery box reveals with transparent, verifiable randomness.  
Each mint produces a unique piece from the **Echoes of Soundness** collection, with traits that are provably fair.

---

## Description
The NFT space is full of "mystery drops" that often feel rigged or opaque.  
**NFT Mystery Box for USer** aims to change that.  

The collection — *Echoes of Soundness* — draws inspiration from the idea of sound waves as unique digital artifacts.  

Here’s the difference:
- Every reveal runs inside the **zkVM**, generating randomness that cannot be manipulated.  
- Proofs are attached on-chain and stored in **WALRUS**, so anyone can check the fairness.  
- Collectors know that when they mint, the rarity and attributes are **truly luck-based**.  

This not only delivers a fun and fair NFT experience, but also highlights the strength of Soundness Layer.

---

## Technical Architecture
| Component      | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Frontend       | Clean web app for box purchase & reveal                                     |
| Smart Contracts| Manage minting, rarity assignment, and ownership                            |
| RNG & Proofs   | Random outcomes generated inside **SP1 zkVM** with proofs exported          |
| Storage        | Proofs stored in **WALRUS** for transparency                                |
| Verifier       | Soundness Layer validates every proof                                       |

---

## Flow
1. User mints a mystery box.  
2. zkVM executes randomness logic.  
3. RNG is generated & verified by Soundness Layer.  
4. NFT is revealed with traits/rarity.  
5. Proof stays publicly verifiable on-chain.  

---

## Development Timeline
| Phase             | Duration  | Milestone                                     |
|-------------------|-----------|-----------------------------------------------|
| Proposal          | 1 day     | Submit repo PR                                |
| Smart Contracts   | 2 weeks   | Base mint & reveal logic                      |
| zk Integration    | 2 weeks   | RNG + proof system inside SP1 zkVM            |
| SL Integration    | 1 week    | Connect verifier with Soundness Layer         |
| Testing & Launch  | 1 week    | Public testnet drop                           |

---

## Goal
To create an **NFT mystery box that people can actually trust** — where collectors know the randomness is fair and verifiable.  

The project also doubles as a **showcase app for Soundness Labs**, demonstrating the potential of transparent, zk-powered NFTs.  

---

## Contacts
- **Discord Username: salidlemi
- **GitHub:** [@salidlemi](https://github.com/salidlemi)
