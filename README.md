# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
```
.
├── contracts // 合约
│   └── Lock.sol
├── deploy
│   ├── 01-deploy-box.js
│   └── 02-deploy-box2.js
├── hardhat.config.js
├── helper-functions.js
├── helper-hardhat-config.js
├── package.json
├── scripts
│   ├── deploy-example.js
│   ├── deploy.js
│   ├── prepare-upgrade.js
│   ├── transfer-ownership.js
│   ├── upgrade-box-manual.js
│   └── upgrade.js
├── test
│   └── Lock.js
└── yarn.lock

```