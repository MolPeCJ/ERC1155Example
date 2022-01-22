### Description

This repository contains a project based on interaction with the erc1155 token using smart contracts.  
All functions of smart contracts from the 'contracts' folder are commented to improve understanding of their work.  
Also, smart contracts are fully tested, the tests are located in the tests folder. 

***

### Instalation

bash  
```yarn install```

### Usage

For further work, you will need to install in this project all all the necessary dependencies,  
which are listed in the 'package.json' file (for example, coverage (```yarn install coverage```))

### Compilation

```yarn hardhat compile```

### Run tests and coverage 

```yarn hardhat coverage```

### Deploying contract

```npx hardhat run scripts/ *select the file you want to run*``` 
--network `<your network>`

### Verify a contract

```npx hardhat run scripts/ *select the file you want to run*``` 
--network `<your network>`