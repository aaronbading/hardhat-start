# hardhat-start

This is a hardhat project that helps in getting started with the Smart Contract Development Environment.

## Relevant Commands :

```bash

npx hardhat accounts   #show local dev enviroment accounts
npx hardhat compile    #Compile smart contracts
npx hardhat clean      #Clean up and start new.
npx hardhat test       # run the tests
npx hardhat node       # spin up local developement network
npx hardhat help       #manual

REPORT_GAS=true npx hardhat test
npx hardhat coverage
npx hardhat run scripts/deploy.ts
TS_NODE_FILES=true npx ts-node scripts/deploy.ts
npx eslint '**/*.{js,ts}'
npx eslint '**/*.{js,ts}' --fix
npx prettier '**/*.{json,sol,md}' --check
npx prettier '**/*.{json,sol,md}' --write
npx solhint 'contracts/**/*.sol'
npx solhint 'contracts/**/*.sol' --fix

```
