# Morden testnet

[![Join the chat at https://gitter.im/eth-classic/morden](https://badges.gitter.im/eth-classic/morden.svg)](https://gitter.im/eth-classic/morden?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The Morden proof-of-work testnet for Ethereum Classic.

Consensus Monitoring Dashboard: http://34.68.71.127:3000/ (ask on ETC Discord for `WS_SECRET`)

Atlantis Hardfork: `4_729_274`

### Parity Ethereum

Required version: 2.4.7+ for Atlantis testing

```bash
parity --chain morden
```

### Geth Classic

Required version: 6.0.3+ for Atlantis testing

```bash
geth --testnet
```

### Multi Geth

_Unfortunately, Multi-Geth does not support Morden. Please use [Kotti](https://github.com/goerli/testnet#meta-data-kotti-classic) or [Kensington](https://github.com/eth-classic/kensington)._
