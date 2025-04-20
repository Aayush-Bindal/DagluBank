# DBank

DBank is a decentralized banking application that allows users to top up, withdraw, and manage their balance seamlessly.

## Features

- **Top Up**: Add funds to your account.
- **Withdraw**: Withdraw funds from your account.
- **Compound Interest**: Automatically compounds your balance.
- **Real-Time Balance Updates**: View your current balance instantly.

## Project Structure

- **Frontend**: Located in `src/dbank_assets/src/`. Contains the HTML, CSS, and JavaScript files for the user interface.
- **Backend**: Defined in the `src/declarations/dbank/` folder. Includes the service interface and logic.
- **Assets**: Static assets like images and stylesheets are in `src/dbank_assets/assets/`.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [DFX SDK](https://internetcomputer.org/docs/current/developer-docs/build/install-upgrade-remove/)
- A local replica of the Internet Computer running.

## Getting Started

###  Start the Local Replica

1. Make sure dfx is running

```
dfx start --clean
```

2. Deploy the project
```
dfx deploy
```

3. Start NPM
```
npm start
```



