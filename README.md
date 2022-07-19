![CI](https://github.com/pooltogether/v4-pool-data/actions/workflows/main.yml/badge.svg)

# Pool data

A [Contract List](https://github.com/losslessproject/contract-list-schema) of the latest Lossless deployments on mainnets and testnets.

# Installation

```bash
yarn add @losslessproject/pool-data
```

# Use

```js
import { mainnet, testnet } from '@losslessproject/pool-data'
```

`mainnet` consists of all of the deployments on mainnets (ex. Ethereum, Polygon, etc.)
`testnet` consists of all of the deployments on testnets (ex. Harmony, Rinkeby, etc.)
