<p align="center"><a href="https://github.com/eth-clients/goerli">Goerli (2019)</a> | <a href="https://github.com/eth-clients/sepolia">Sepolia (2021)</a> | <strong>Holešky (2023)</strong></p>
<p align="center"><img src="./assets/holesovice.png" /></p>

# Holešky (Holešovice Testnet)

Meet `--holesky`, the first long-standing, merged-from-genesis, public Ethereum testnet. Holešky will replace <a href="https://github.com/eth-clients/goerli">Goerli</a> as a staking, infrastructure and protocol-developer testnet in 2023. For testing decentralized applications, smart contracts, and other EVM functionality, please use <a href="https://github.com/eth-clients/sepolia">Sepolia</a>!

### Metadata

This is _work in progress_. The final config will be shared prior to launch date.

* Status: _Planned_ ([#3](https://github.com/eth-clients/holesky/issues/3))
* Flag: `--holesky`
* Flavor: Permissionless (Proof-of-Stake), _to replace Goerli_
* Launch Date: **Sept/15, 2023, 14:00 UTC**
  * Epoch time: 1694786400
  * LTS: Dec/2027, EOL: Dec/2028
* Execution Version: Cancun _(TBD)_
* Consensus Version: Deneb _(TBD)_
* Merge: At Genesis (`0`)
* Shapella Epoch: `10`
  * Epoch time: `1694790240` (64 minutes after genesis)
* Network ID: `17000`
* Chain ID: `17000`
* Genesis Execution Block payload:
```yaml
baseFeePerGas: 1000000000,
difficulty: 1,
extraData: "0x686f77206d7563682069732074686520666973683f",
gasLimit: 25000000,
gasUsed: 0,
hash: "0xff9006519a8ce843ac9c28549d24211420b546e12ce2d170c77a8cca7964f23d",
logsBloom: "0x00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000",
miner: "0x0000000000000000000000000000000000000000",
mixHash: "0x0000000000000000000000000000000000000000000000000000000000000000",
nonce: "0x0000000000001234",
number: 0,
parentHash: "0x0000000000000000000000000000000000000000000000000000000000000000",
receiptsRoot: "0x56e81f171bcc55a6ff8345e692c0f86e5b48e01b996cadc001622fb5e363b421",
sha3Uncles: "0x1dcc4de8dec75d7aab85b567b6ccd41ad312451b948a7413f0a142fd40d49347",
size: 535,
stateRoot: "0x69d8c9d72f6fa4ad42d4702b433707212f90db395eb54dc20bc85de253788783",
timestamp: 1694786100,
totalDifficulty: 1,
transactions: [],
transactionsRoot: "0x56e81f171bcc55a6ff8345e692c0f86e5b48e01b996cadc001622fb5e363b421",
uncles: []
```
* EVM Version: London
  * Homestead: 0 (block number)
  * Byzantium: 0 (block number)
  * Constantinople: 0 (block number)
  * Petersfork: 0 (block number)
  * Istanbul: 0 (block number)
  * Berlin: 0 (block number)
  * MuirGlacier: 0 (block number)
  * London: 0 (block number)
  * Shanghai: 1694790240 (unix time)
  * Cancun: _(TBD)_
* Bootnodes Execution layer:
  * `enode://ac906289e4b7f12df423d654c5a962b6ebe5b3a74cc9e06292a85221f9a64a6f1cfdd6b714ed6dacef51578f92b34c60ee91e9ede9c7f8fadc4d347326d95e2b@146.190.13.128:30303`
  * `enode://a3435a0155a3e837c02f5e7f5662a2f1fbc25b48e4dc232016e1c51b544cb5b4510ef633ea3278c0e970fa8ad8141e2d4d0f9f95456c537ff05fdf9b31c15072@178.128.136.233:30303`
* Bootnodes Consensus layer:
  * `enr:-KG4QMH842KsJOZAHxI98VJcf8oPr1U8Ylyp2Tb-sNAPniWSCaxIS4F9gc3lGOnROEok7g5qrOm8WgJTl2WXx8MhMmIMhGV0aDKQqX6DZjABcAAKAAAAAAAAAIJpZIJ2NIJpcISygIjpiXNlY3AyNTZrMaECvQMvoDF46BfJgvAbbv1hwpNu9VQBXRIpHS_B8zmkZmmDdGNwgiMog3VkcIIjKA`
  * `enr:-Ly4QDU8tZeygxz1gEeAD4EKe4H_8gg-IanpTY6h8A1YGPv5BPNvCMD77zjHUk_iF1pfG_8DC6jYWbIOD1k5kF-LaG4Bh2F0dG5ldHOIAAAAAAAAAACEZXRoMpCpfoNmMAFwAAoAAAAAAAAAgmlkgnY0gmlwhJK-DYCJc2VjcDI1NmsxoQN4bUae9DwIcq_56DNztksQYXeddTDKRonI5qI3YhN4SohzeW5jbmV0cwCDdGNwgiMog3VkcIIjKA`
* Deposit contract address: `0x4242424242424242424242424242424242424242`

### Resources
* Ethstats: [https://ethstats.holesky.ethpandaops.io](https://ethstats.holesky.ethpandaops.io)
* Homepage: [https://holesky.ethpandaops.io](https://holesky.ethpandaops.io)
* Latest Proposal: [Ethereum Magicians - Predictable Ethereum Testnet Lifecycle](https://ethereum-magicians.org/t/proposal-predictable-ethereum-testnet-lifecycle/11575)
* Some Context: [Ethereum Magicians - Paths out of the Goerli supply mess](https://ethereum-magicians.org/t/testnet-workgroup-paths-out-of-the-goerli-supply-mess/11453)
