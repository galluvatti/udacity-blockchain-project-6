# Supply Chain Project

## Truffle Version
>
    Truffle v4.1.14
>

## Node Version
>
    node v10.16.0
>

## web3 Version
>
    web3@1.2.1
>
## Contract Deployment Address
>
transaction https://rinkeby.etherscan.io/tx/0x60168f0d65f413f09c394a54e7a2c1986f39a51fa5f0509d8962854fae687f24
contract https://rinkeby.etherscan.io/address/0x2f7e3ba53d9d7c3106399a4b508a4282b550637d

## Project write-up - UML

### Activity Diagram
![Activity Diagram](uml/activity.png)

### Sequence Diagram
![Sequence Diagram](uml/sequence.pn)

### State Diagram
![State Diagram](uml/state.png)

### Class Diagram (Data Model)
![Class Diagram](uml/class.png)

## Libraries
truffle-hdwallet-provider 1.0.17 to deploy contract on Rinkeby network


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

### Installing

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
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

All 10 tests should pass.

In a separate terminal window, launch the DApp:

```
npm run dev
```
