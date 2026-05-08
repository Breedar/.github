# Breedar

Paying a distributed team across 30 countries should not require 14 vendor accounts, a spreadsheet, and two days of finance-team time every month. We are fixing that.

## The stack we are building

**[paystream](https://github.com/Breedar/paystream)** is our flagship: a global payroll API on Stellar that batches USDC payouts to 1,000 recipients and settles them in 47 local currencies through SEP-31 anchor corridors. One API call, one approval, one on-chain transaction.

The surrounding infrastructure paystream depends on:

- **[StellarRemit](https://github.com/Breedar/StellarRemit)**: cross-border remittance rails on Stellar anchors
- **[StellarID](https://github.com/Breedar/StellarID)**: decentralized identity and KYC attestation for Stellar accounts
- **[PayVault](https://github.com/Breedar/PayVault)**: multi-sig treasury management for teams and DAOs
- **[AssetsUp](https://github.com/Breedar/AssetsUp)**: tokenized asset issuance and lifecycle management

## Why Stellar

The Stellar network settles in 3 to 5 seconds at fractions of a cent per transaction. SEP-31 gives us last-mile local currency delivery without building banking relationships in every corridor ourselves. Fast finality, a global anchor network, and an open protocol. That combination is why we build here and not elsewhere.

## Work with us

We review PRs across all repos. If you are interested in fintech infrastructure, Stellar anchor integrations, or Go and TypeScript backend work, there is meaningful open work to pick up. Check the `good first issue` label or open a Discussion.
