# dapp-truffle-nextjs
A minimal smart contract development boilerplate that uses [Truffle Suite](https://www.trufflesuite.com/) and [NextJS](https://nextjs.org/).

Source: https://www.trufflesuite.com/boxes/truffle-next

| This repo follows the source above but updates Node Packages to their latest versions. It also makes a few minor adjustments to run with these updates.

## Installation

1. Install Truffle Suite globally.
```
npm install -g truffle
```
2. Clone this repository.
```
git clone git@github.com:lliamscholtz/dapp-truffle-nextjs.git
```
3. Install all npm modules (dependencies).
```
// Change directory to the project folder
cd dapp-truffle-nextjs

// Change directory to the front-end folder
cd client

yarn install
// or
npm install
```
4. Run the development console.
```
truffle develop
```
5. Compile and migrate the smart contracts.
```
compile
migrate
```
6. Run the next.js server for the front-end. Smart contract changes must be manually recompiled and migrated.
```
// Change directory to the front-end folder
cd client

// Serves the front-end on http://localhost:3000
npm run dev
```