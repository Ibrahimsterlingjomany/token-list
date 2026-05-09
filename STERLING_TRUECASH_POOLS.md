# Sterling TrueCash Pools

## Canonical Pool

- Pair: `STM/SJBCUSD`
- Pool: `BbvR4zUAwZF8LmVFLXNpDy3CxuYcDwd5isoh7CZFAF5G`
- Program: `7v9sLrk92NNLLUfXLJw3o7MycZNvwsTK6kLWfWb8vcVA`
- Base vault: `3mRYBWgBKnQuUyvVDcYFqSeNoQTujTsFGra3GWLof9av`
- Quote vault: `5z4brtXmcDBhPKLk9YoiZE7fqaourBk26jBuAUHqZDN9`
- Fee vault STM: `HgaLTe9cp398Y2svc8qmK4R7Xi2da46iWeTyM4jH3LFP`
- Fee vault SJBC: `BjjVF8NhtRtCvmcdQEbFRY3ebkbLKyDa7KAmBTH2LBAp`

## TrueCash Reading

- STM = base asset
- SJBC = on-chain quote mint
- SJBCUSD = public USD quote label
- USDC = settlement rail
- 1492 = orchestration / control layer
- 8012 = canonical market truth

Sterling exposes the STM/SJBCUSD canonical pool as a public TrueCash USD market surface with cash-backed and real-peg flags enabled in the metadata.

## Public Metadata

- Pair metadata: `https://sterlingchain.net/token-assets/stm-sjbcusd.pair.metadata.json`
- Pool metadata: `https://sterlingchain.net/token-assets/stm-sjbcusd.pool.metadata.json`
- Token list: `https://api.sterlingchain.net/tokenlist.json`
- Pool registry: `https://api.sterlingchain.net/pool-registry.json`
- Proof: `https://api.sterlingchain.net/proof.json`
