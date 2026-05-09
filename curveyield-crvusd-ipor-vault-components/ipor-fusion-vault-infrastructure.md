# IPOR Fusion Vault Infrastructure

CurveYield crvUSD uses IPOR Fusion as the vault framework.

IPOR Fusion provides the vault contract, access manager, price manager, withdraw manager, fee manager, rewards claim manager, and context manager used by the vault. Strategy actions are executed through fuses, which define the approved protocol interactions the vault can perform.

For the Base vault, the active strategy route uses Curve and ERC4626-style fuses. The vault also uses price feed contracts so the IPOR price manager can value the assets held by the vault route.

The vault can hold idle crvUSD and strategy assets at the same time. Keeper automation can move excess idle crvUSD into the strategy route and can call harvest actions when available rewards are large enough to justify execution.

All strategy routes are controlled through vault configuration. A route must have the correct fuse, balance fuse, substrate, and price source configuration before the vault can safely use it.
