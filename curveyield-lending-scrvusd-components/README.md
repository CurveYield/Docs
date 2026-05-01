---
description: CurveYield Lending scrvUSD cylscrvUSD Morpho Vault Token Documentation
---

# CurveYield Lending scrvUSD Components

[**CurveYield Lending scrvUSD (cylscrvUSD)**](https://app.morpho.org/ethereum/vault/0x594Be6816Ff2EEae7Db4f3EA8F9e81F0CCc94444) — a liquid, yield-bearing vault share token built on scrvUSD and a V2 Morpho vault that allocates scrvUSD across select lending and borrowing markets.

[**aCRV Lending/Borrowing Market**](https://app.morpho.org/ethereum/market/0x5a9a736feaefa36d605af46ca54ee1640b127285e9763e9668dd91b1c91bca28/acrv-scrvusd) — a market with aCRV as collateral, which is a vault token composed of cvxCRV, a liquid wrapper for CRV locked by Convex that earns boosted CRV revenue.

[**yvyCRV Lending/Borrowing Market**](https://app.morpho.org/ethereum/market/0xa6e1ba01b1ae2b8f73e026596a6c11551efe07ed55314cb12abfc1e76a4b6f14/yvycrv-scrvusd) — a market with yvyCRV as collateral, which is a Yearn vault share token composed of yCRV, a liquid wrapper for CRV that earns yield from Curve fees and bribe incentives.

[**asdCRV Lending/Borrowing Market**](https://app.morpho.org/ethereum/market/0x7832d00f0294515e97ccdbe10282dd768b4c016d8ee4a8e7ad29b6cdcc167a4d/asdcrv-scrvusd#overview) — a market with asdCRV as collateral, which is a vault token composed of sdCRV, a liquid wrapper for CRV locked via StakeDAO that earns trading fees, CRV emissions, and vote incentives, with additional veSDT boost applied to increase rewards.

[**yvCurve-yYB-f Lending/Borrowing Market**](https://app.morpho.org/ethereum/market/0xb3325fd674f0a63a4cc4559d51a4cd2bff557d3b1695b414bf825fcda0b3d903/yvcurve-yyb-f-scrvusd) — a market with yvCurve-yYB-f as collateral, which is a Yearn vault share token composed of a Convex-boosted Curve stable pool of YB and yYB, earning trading fees and boosted CRV rewards.

[**CurveYield Lending scrvUSD Curve Oracle Stable Pool**](https://curveyield.com/cylscrvusd-sp) — a Curve stable pool composed of cylscrvUSD, scrvUSD, and crvUSD that uses an oracle-based pricing mechanism to maintain accurate relative pricing and consistent tradability of cylscrvUSD across DeFi pools on Ethereum mainnet.

All lending markets use a unified parameter set, ensuring consistent behavior across markets regardless of collateral type.

The liquidation LTV is 77%, with a liquidation penalty of 7.41%. All markets use the Standard Morpho interest rate model (0x870aC11D48B15DB9a138Cf899d20F13F79Ba00BC). Each market uses a custom oracle contract, listed on the Contracts page.
