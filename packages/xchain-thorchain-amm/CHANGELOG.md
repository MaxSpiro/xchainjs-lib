# v0.3.11 (2022-12-27)

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
 - Update README.md dependency specification

# v0.3.10 (2022-12-08)

## udpate

- changed eth & evm deposit() to use depositWithExpiry() with a 15 min expiry time

# v0.3.9 (2022-11-24)

## udpate

- Bump `xchain-client`

# v0.3.8 (2022-11-08)

## Update

- added `addSaver()` & `withdrawSaver()` to thorchain-amm

# v0.3.7 (2022-11-10)

## Update

- added missing 'await' statements in thorchain-amm

# v0.3.6 (2022-11-08)

## Update

- changed chain-id in wallet to `thorchain-stagenet-v2`
- removed clienturl params in wallet

# v0.3.5 (2022-10-27)

## Update

- Bump Dep for `thorchain-query`
- Bump Dep for `xchain-litecoin`

# v0.3.4 (2022-10-27)

## Update

- Bump Dep for `thorchain-query`
- update to `getInboundDetails()`

# v0.3.3 (2022-10-17)

## Update

- Bump Dep version number for `xchain-midgard`, `thorchain-query`
- Change ExecuteSwap() parameters to use constructed memo from `estimateSwap()`
- Remove `constructMemo()` from wallet.ts
- validate affiliate address is either a valid thorchain adress OR a valid thorname
- Clean types file

# v0.3.3 (2022-10-17)

## Update

- default to mainnet and stadard APIs with no arg constructor

# v0.3.1 (2022-10-11)

## Add

- Add lp add & withdraw
- Bumped `xchain-litecoin`

# v0.3.0 (2022-10-10)

## Update

- Bumped `xchain-thorchain`

# v0.2.1 (2022-10-04)

## Update

- Bumped `xchain-utils` & `xchain-client`

# v0.2.0 (2022-10-04)

## Update

- Updated wallet.ts and evm files to use updated `thorchain-query` `getInboundDetails()`

# v0.0.1.0-beta5 (2022-09-29)

## Update

- bumped deps on xchain-utils & xchain-client

# v0.0.1.0-beta4 (2022-09-15)

- moved examples into different directory
- import new version of xchain-thorchain-query

# v0.0.1.0-beta3 (2022-09-06)

- import new version of xchain-thorchain-query

# v0.0.1.0-beta2 (2022-09-05)

- moved estimate logic into xchain-thorchain-query

# v0.0.1.0-beta (2022-08-15)

- resolved several issues
- added avax client
- added ThorchainCache to manage caching thorchain state

# v0.0.1.0-alpha3 (2022-08-08)

## Remove

- Remove `Polkadot` from chain defaults and chain references/switch cases.

# v0.0.1.0-alpha2 (2022-07-25)

## ADD

- Add `Doswap()` function to thorchain-amm

## Update

- Changed values in `calcSwapNetworkFee` to suite the latest network fees

# v0.0.1.0-alpha (2022-07-20)

## Module Created
