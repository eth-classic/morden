**Update 10/2021** -- Morden bootnodes for archiving purposes are available:

```
enode://a97fd677e1b67f2554ee36a882d100c3bbcaec241d000442dee95ab23eca8c39a6c918d5317ee5aebc433aa7329387ba936071359c768413f7cc1add531f0226@176.9.51.216:42648
enode://6559a9ebe13f04e1c5d572f278ec89072a56a064f4da189d628e4c010cfaf37deeaff81589119bd046e25fdb18a03b0ab9d63229c926f1abeb4b4717d4de73dd@88.99.70.182:42648
```

Clients known to support the last known config of Morden: Open Ethereum [v3.2.6](https://github.com/openethereum/openethereum/releases/tag/v3.2.6), Parity Ethereum [v2.7.2](https://github.com/openethereum/parity-ethereum/releases/tag/v2.7.2), and Classic Geth [v6.1.12](https://github.com/etclabscore/go-ethereum/releases/tag/v6.1.2); all conveniently with `--chain morden`. Note, that the custom, non-zero starting nonce of the Morden network does not allow you to sync the chain with Geth, Multi-Geth, or Core-Geth.

---

**Update 10/2019** -- Morden has been replaced by **Mordor**: https://github.com/eth-classic/mordor

---

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

Required version: 6.0.6+ for Atlantis testing

```bash
geth --testnet
```

### Multi Geth

_Unfortunately, Multi-Geth does not support Morden. Please use [Kotti](https://github.com/goerli/testnet#meta-data-kotti-classic) or [Kensington](https://github.com/eth-classic/kensington)._
