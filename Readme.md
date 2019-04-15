# Project 5: Build CryptoStar Dapp on Ethereum

This is **Project 5: Build CryptoStar Dapp on Ethereum**, this project is extension of StarNotary Version 2 that we built during the course.
Users can create a star and also look up the star through UI

# Documentation
-------------

## Prerequisites

This project runs on top of node.js, please make sure to install **[Nodejs]** on machine with default configuration before running it.This project is developed on latest version of **[Node.js]** which is right now **v10.14.1** and Latest version of **[Truffle]** look Built with section for more information 

## Installation

Go to project folder in command prompt/terminal and run below command:


```sh
npm install
```

```sh
cd app
npm install
```

This will install all the required libraries, check out **package.json** and look value for _dependencies_ for all libraries used in this project. More over check Built With section for more information.

## Deployment

Go to project folder in command prompt/terminal and run below command:


```sh
truffle compile
truffle migrate --reset
truffle test
```
On second terminal 

```sh
npm run dev
```

Server is configured to run by default on port: 8080
Local url : http://localhost:8080


## Built With and Token Information

ERC-721 Token Name : ScientistZ Token
ERC-721 Token Symbol : SCI
Token Address on Rinkeby : https://rinkeby.etherscan.io/token/0xA067EC8c3284DdbF36Dc50E6aB9aa85f6ae7F50F

- [Truffle](https://truffleframework.com/) - v5.0.12 (core: 5.0.12) - As a development framework
- [truffle-hdwallet-provider](https://github.com/trufflesuite/truffle-hdwallet-provider) - 1.0.2 - Provider to communicate
- [openzeppelin-solidity](https://github.com/OpenZeppelin/zeppelin-solidity) - 2.1.2 - For using ERC 721 contracts
- [nodejs] - 10.14.1 - Server which is used to run app
    
## Versioning

This is the first version of this project denoted as _Project 5 V 1.0_

## Author(s)

[Muhammad Zaheer Nazir]

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/bitcoinjs/bitcoinjs-lib/blob/master/LICENSE) file for details

[Muhammad Zaheer Nazir]: <https://www.linkedin.com/in/muhammad-zaheer-nazir/>



