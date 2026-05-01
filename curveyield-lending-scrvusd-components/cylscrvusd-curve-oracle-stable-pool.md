# cylscrvUSD - Curve Oracle Stable Pool

A Curve stable pool composed of cylscrvUSD, scrvUSD, and crvUSD.

The pool uses an oracle to price cylscrvUSD at the vault’s deposit and withdrawal conversion rate, ensuring that cylscrvUSD trades at its correct value.

This design allows cylscrvUSD to trade efficiently in liquidity pools, similar to wstETH, rather than behaving like standard vault tokens that either do not trade well in liquidity pools or rely on arbitrage losses to maintain proper pricing.

Pool: [CurveYield cylscrvUSD Stable Pool](https://curveyield.com/cylscrvusd-sp)\
Contract: [0x2507b71876233dba4876ea7741f35736f5ac937d](https://etherscan.io/address/0x2507b71876233dba4876ea7741f35736f5ac937d)\
Oracle: [0x572e7c136cEE1BCbC6B17aD2F0405dbeAC10E9ac](https://etherscan.io/address/0x572e7c136cEE1BCbC6B17aD2F0405dbeAC10E9ac)
