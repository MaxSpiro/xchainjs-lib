# v0.1.12 (2022-12-27)

## Update

- Bump:
 - `xchain-avax@0.1.3`
 - `xchain-binance@5.6.6`
 - `xchain-bitcoin@0.20.7`
 - `xchain-bitcoincash@0.15.6`
 - `xchain-client@0.13.5`
 - `xchain-cosmos@0.20.6`
 - `xchain-ethereum@0.27.6`
 - `xchain-evm@0.1.3`
 - `xchain-litecoin@0.10.8`
 - `xchain-thorchain@0.27.7`
 - `xchain-util@0.12.0`
- Change `Asset*` and `*Chain` imports from `xchain-util` to its respective `xchain-*`

# v0.1.11 (2022-12-16)

## fix

- use abbreviated asset names in swap memo

# v0.1.10 (2022-12-13)

## Udpate

- Bump dependencies

# v0.1.9 (2022-11-27)

## Udpate

- Bump dependencies

# v0.1.8 (2022-11-12)

## ADD

- Add `estimateAddSaver()` & `estimateWithdrawSaver()` & `getsaverPosition()`

## Update

- Use latest xchain-midgard@0.3.0

# v0.1.7 (2022-11-10)

## Fix

- added missing AVAX case in getDustValues()
- fixed BTC/BCH/LTC case statement

# v0.1.6 (2022-10-27)

## ADD

- Add Liquidity position growth calculations using the LUVI formula in `checkLiquidityPosition()`

## Fix

# v0.1.5 (2022-10-27)

## Fix

- Bug - Limit asset amount was not using 8 decimal places
- Bug - Swap to Synths was failing Pool Conversion
-

## Update

- Removed getInboundAddresses() from thorchainCache since it was redundant
- Renamed AffiliateFeePercent to AffiliateFeeBasisPoints in EstimateSwapParams
- Updated output decimals to us NativeDecimals from Pool data
- Created calcOutboundFee() to use thornode outbound_fee

# v0.1.4 (2022-10-17)

## Fix

- Bug - Limit asset amount was not using 8 decimal places
- Bug - outbound fee is now calculated correctly
- Bug - affiliate fee calculation fixed
- Bug - getPoolForAsset() changed to take both chain & ticker for lookup
- Bump dep on package `xchain-midgard`

## Add

- check input asset decimals match nativeDecimals in LiquidityPool.pool, or throw Error

# v0.1.3 (2022-10-17)

## Update

- default to mainnet and standard APIs with no arg constructor

# v0.1.2 (2022-10-11)

## Update

- Lp estimate add and witdraw

# v0.1.1 (2022-10-04)

## Update

- Bumped `xchain-utils` & `xchain-client`

# v0.1.0 (2022-10-03)

## Add

- Add and Remove Lp functions

# v0.1.0 (2022-10-03)

## Update

- Updated outboundfee calcs it now uses `/thorchain/inbound_addresses`, `outbound_fee`

# v0.1.0-beta2 (2022-09-29)

## Add

- Add estimate add & withdraw Liquidity
- Add Check Liquidity position

# v0.1.0-beta1 (2022-09-29)

## Update

- bumped deps on xchain-utils & xchain-client

# v0.1.0-beta (2022-09-15)

## Fix

- fixed math calcs to account for decimals

# v0.1.0-alpha1 (2022-09-07)

## Fix

- Updated EstimateSwapParam type
- Edited function `estimateSwap()` to include default parameters

# v0.1.0-alpha (2022-08-26)

## Module Created
