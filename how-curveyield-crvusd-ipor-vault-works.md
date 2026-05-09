---
description: CurveYield crvUSD cy-crvUSD IPOR Fusion Vault Documentation
---

# How CurveYield crvUSD IPOR Vault Works

CurveYield crvUSD is an IPOR Fusion vault that accepts crvUSD and issues cy-crvUSD as the vault share token.

The vault is designed to allocate deposited crvUSD into approved Curve ecosystem yield routes. These routes are built around Curve stable pools and StakeDAO vaults, allowing crvUSD deposits to earn yield from liquidity provisioning, external rewards, and vault-level compounding.

Depositors receive cy-crvUSD, which represents a share of the vault. As the vault earns and realizes yield, that value is reflected through the vault share price.

The Base deployment is the first live example of this design. It deposits crvUSD into a Curve pool route and then into a StakeDAO vault, while using IPOR Fusion fuses, price feeds, fee controls, and keeper automation to manage the position.

The Ethereum deployment uses the same cy-crvUSD vault design and has been created through the IPOR Fusion factory. Collateral-specific Curve and StakeDAO routes on Ethereum are intended to be added only after the approved collateral and pool set is finalized.

**This structure gives CurveYield a flexible crvUSD vault that can route deposits into whitelisted Curve ecosystem yield strategies while keeping the vault accounting and permissions inside the IPOR Fusion framework.**<br>
