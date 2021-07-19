![The Complete Guide to Full Stack Ethereum Development
](https://miro.medium.com/max/1400/0*lGH4EEnrm9auNQAB.jpg)

This codebase goes along with the tutorial [The Complete Guide to Full Stack Ethereum Development](https://kanew.medium.com/the-complete-guide-to-full-stack-ethereum-development-490e5b87b688)

## Getting started

Here's how to deploy this project

1. Clone the repo

```sh
git clone https://github.com/kanew071/Ethereum-Full-Stack.git
```

2. Install the dependencies

```sh
npm install

# or

yarn
```

3. Start the local test node

```sh
npx hardhat node
```

4. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Update __src/App.js__ with the values of your contract addresses (`greeterAddress` and `tokenAddress`)

6. Run the app

```sh
npm start
```
