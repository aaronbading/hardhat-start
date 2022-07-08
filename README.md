# hardhat-start

This is a hardhat project that helps in getting started with the Smart Contract Development Environment.

## Relevant Commands :

```bash

$npx hardhat accounts   #show local dev enviroment accounts
$npx hardhat compile    #Compile smart contracts
$npx hardhat clean      #Clean up and start new.
$npx hardhat test       # run the tests
$npx hardhat node       # spin up local developement network
$npx hardhat help       #manual

$REPORT_GAS=true npx hardhat test
$npx hardhat coverage
$npx hardhat run scripts/deploy.ts
$TS_NODE_FILES=true npx ts-node scripts/deploy.ts
$npx eslint '**/*.{js,ts}'
$npx eslint '**/*.{js,ts}' --fix
$npx prettier '**/*.{json,sol,md}' --check
$npx prettier '**/*.{json,sol,md}' --write
$npx solhint 'contracts/**/*.sol'
$npx solhint 'contracts/**/*.sol' --fix

```

## Deployment

```bash
$npx hardhat run scripts/deploy.js --network <network-name>

```

With our current configuration, running it without the --network parameter would cause the code to run against an embedded instance of Hardhat Network. In this scenario, the deployment actually gets lost when Hardhat finishes running, but it's still useful to test that our deployment code works:

```bash
$npx hardhat run scripts/deploy.js
Deploying contracts with the account: 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266
Account balance: 10000000000000000000000
Token address: 0x5FbDB2315678afecb367f032d93F642f64180aa3
```

### Deploy to goerli

Fill out .env.example with necessary keys ..

```bash
$npx hardhat run scripts/deploy.js --network goerli
Deploying contracts with the account: 0xE8857156276388683047eA7485369e7e9c039182
Account balance: 50000000000000000
Token address: 0xF1Ff3E3e0395b4b8bb75747022C7b97E22037544
```
