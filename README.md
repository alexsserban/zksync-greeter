# zksync-greeter

- Testing zkSync on testnet with a Greeter smart contract deployed via Hardhat and a Vue.js dApp.
- [Loom Video Demo](https://www.loom.com/share/61bd0bfa2e3d457d976008b7494ffa17)
- [zkSync Greeter contract](https://goerli.explorer.zksync.io/address/0xB182DE281AC10551A467DcB4304468F64f2a72a5)

```
cp .env.example .env
yarn
hh compile
hh deploy-zksync // update GREETER_CONTRACT_ADDRESS in ./frontend/src/App.vue
cd frontend
yarn
yarn serve
```
