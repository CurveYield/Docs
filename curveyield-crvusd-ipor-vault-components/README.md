---
description: CurveYield crvUSD cy-crvUSD IPOR Fusion Vault Components
---

# CurveYield crvUSD IPOR Vault Components

[**CurveYield crvUSD Base Vault (cy-crvUSD)**](https://app.ipor.io/fusion/base/0x574D968Dea29F6D488E03392A28A3E230D0f76d9) - an IPOR Fusion vault on Base that accepts crvUSD and allocates into a Curve and StakeDAO yield route.

[**CurveYield crvUSD Ethereum Vault (cy-crvUSD)**](https://app.ipor.io/fusion/ethereum/0xe31aa86e21e420d03e52aaa06c349bdc525a664f) - an IPOR Fusion vault on Ethereum mainnet created for the same crvUSD strategy design, with collateral-specific strategy routes to be added after the final approved pool set is selected.

[**StakeDAO Route on Base**](curveyield-crvusd-base-vault-cy-crvusd.md) - the first active strategy route, using crvUSD exposure through a Curve pool and StakeDAO vault.

[**IPOR Fusion Vault Infrastructure**](ipor-fusion-vault-infrastructure.md) - the vault framework used for asset accounting, roles, fuses, oracle routing, fees, and controlled strategy execution.

The vault uses a strict set of approved assets and routes. New strategy routes are added through vault governance and must be supported by the correct IPOR fuses, substrates, and price sources before they can be used.
