# Project Supply Chain

<hr>

### Prerequisites

Truffle v5.7.2 (core: 5.7.2)

Ganache v7.6.0

Solidity v0.5.16 (solc-js)

Node v14.15.2

Web3.js v1.8.1

<hr>

## Getting Started

### Installing

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/IgorSmilkov/udacity-supply-chain.git
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Test smart contracts:

```
truffle test
```

In a separate terminal window, launch the DApp:

```
npm run dev
```

<hr>

Contracts have been deployed on the Goerli test network. Here are the transaction and contract ids:

Transaction ID: 0x9c760d8fc26c55ebb9b0622ebaae479e2fdcdf2c89c62d6c5014d97b78936eb1

Contract Id: 0x4213fcb00690043ebda1b0cbda838ae1d26cbb2a

The diagrams can be found in the _diagrams_ directory
