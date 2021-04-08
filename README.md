# AhojSynth
Ahoj.Synth is a synthetic asset protocol running on Avalanche

It is not forked from UMA Protocol, however we took the spirit and some part of the ideas and code from them. Ahoj.Synth is part of Ahoj.Finance and it allows the issuance and trading of financial instruments using synthetic assets named Ahoj Synthetic Assets (ASA).

**What are synthetics?**
A synthetic is a financial instrument that simulates other instruments. In other words, performance of any financial instrument can be simulated using a combination of other financial instruments.
 
**Ahoj.Synth**
Is a protocol for creating economic or financial rules to mint *ASA* (Ahoj Synthetic Assets).

*ASA* can represent one or several financial instruments. *ASA* is a smart contract implementing Total Return Swap financial concept.

This repository is a collection of smart contracts that implement the Ahoj.Swap protocol on Avalanche.

Ahoj is a Czech word from English ahoy. The word Ahoj is used to say *Hello* (informal greeting said when meeting someone) or inclusive to say *Bye* (informal farewell).

## Table of Contents

- [Install](#install)
- [Testing](#testing)
- [Contribute](#contribute)
- [License](#license)


## Install

```bash
# Install project dependencies
npm install

# Install ethereum local blockchain(s) and associated dependencies
npx setup-local-chains
```

## Testing

``` bash
# You can use the following command to start a local blockchain instance
npx start-chain [ganacheUnitTest|gethUnitTest]

# Run all unit tests
npm test

# Run unit tests in isolation
npx truffle --network ganacheUnitTest test test/unit/ahoj.js
```

## Contribute

To report bugs within this package, create an issue in this repository.
For security issues, please contact hello@bayro.io.
When submitting code ensure that it is free of lint errors and has 100% test coverage.

``` bash
# Lint code
npm run lint

# View code coverage
npm run coverage
```

