# CurveYield crvUSD Base Vault (cy-crvUSD)

CurveYield crvUSD on Base is an IPOR Fusion vault that accepts crvUSD and issues cy-crvUSD vault shares.

The Base vault is the first deployed example of the CurveYield crvUSD IPOR vault design. It routes vault capital through a Curve pool and into a StakeDAO vault, giving the vault exposure to Curve ecosystem yield while keeping deposits, withdrawals, accounting, and permissions inside the IPOR Fusion vault system.

The vault is configured with IPOR fuses for Curve pool interaction and ERC4626-style vault interaction. Price feeds are used so the vault can account for the assets held in the route.

Keeper automation is used to move idle crvUSD into the strategy route when idle balances exceed the configured threshold, and to run harvest actions when rewards are large enough to justify execution.

Vault: [0x574D968Dea29F6D488E03392A28A3E230D0f76d9](https://basescan.org/address/0x574D968Dea29F6D488E03392A28A3E230D0f76d9)\
IPOR App: [CurveYield crvUSD on Base](https://app.ipor.io/fusion/base/0x574D968Dea29F6D488E03392A28A3E230D0f76d9)\
Underlying: [crvUSD](https://basescan.org/address/0x417Ac0e078398C154EdFadD9Ef675d30Be60Af93)\
StakeDAO Vault: [0x6f6533b7e0730d150E617001e331ff2FAA41fDe4](https://basescan.org/address/0x6f6533b7e0730d150E617001e331ff2FAA41fDe4)\
Keeper: [0x50bA5cC6F493B8113640bE496899Adc11da879f5](https://basescan.org/address/0x50bA5cC6F493B8113640bE496899Adc11da879f5)
