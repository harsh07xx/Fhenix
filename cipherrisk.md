# CipherRisk

CipherRisk is the private risk module.

The current frontend describes it as computing:

- health factor
- LTV
- liquidation risk

It only presents a live result when an initialized encrypted CipherRisk position is available from the configured contract. It does not create a heuristic score from wallet balances or transaction counts.
