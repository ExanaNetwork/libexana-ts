# Libexana TS

[![NPM Package](https://img.shields.io/npm/v/libexana-ts.svg?style=flat-square)](https://www.npmjs.org/package/libexana-ts)
[![Build Status](https://github.com/ExanaNetwork/libexana-ts/badges/main/pipeline.svg?key_text=build)](https://github.com/ExanaNetwork/libexana-ts/-/pipelines)
[![Coverage Status](https://github.com/ExanaNetwork/libexana-ts/badges/main/coverage.svg)](https://github.com/ExanaNetwork/libexana-ts/-/pipelines)
[![GitLab Release](https://github.com/ExanaNetwork/libexana-ts/-/badges/release.svg)](https://github.com/ExanaNetwork/libexana-ts/-/releases)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ExanaNetwork/libexana-ts/-/blob/main/LICENSE)

**A pure and powerful TypeScript Exana SDK library.**

## Principles

Exana is another powerful peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Exana network allows for highly resilient exana infrastructure, and the developer community needs reliable, open-source tools to implement Exana apps and services.

## Get Started

```sh
npm install libexana-ts
```

Or adding libexana-ts to your app's `package.json`:

```json
"dependencies": {
    "libexana-ts": "^1.0.0",
    ...
}
```

## Documentation

The complete docs are hosted here: [Libexana-ts documentation](https://github.com/ExanaNetwork/libexana-ts/).
There's also a [Libexana API reference](docs/api/index.md) available generated from the TSDocs of the project, where you'll find low-level details on each utility.

## Examples

- [Generate a random address](docs/examples.md#generate-a-random-address)
- [Generate a HD masterkey using Bip39](docs/examples.md#generate-an-address-using-BIP39-mnemonic-seed)
- [Import an address via WIF (Wallet Import Format)](docs/examples.md#import-an-address-via-wif)
- [Create a Transaction](docs/examples.md#create-a-transaction)
- [Sign a Exana message](docs/examples.md#sign-a-exana-message)
- [Verify a Exana message](docs/examples.md#verify-a-exana-message)

## Development & Tests

```sh
git clone https://github.com/ExanaNetwork/libexana-ts.git
cd libexana-ts
npm install
```

Run all the tests:

```sh
npm run test
```

You can also create a test coverage report (you can open `coverage/index.html` to visualize it) with `npm run coverage`.

## Security

We're using Libexana in production, as are many others, but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.