[![npm](https://img.shields.io/npm/v/stacks-pix-sdk?color=blueviolet)](https://www.npmjs.com/package/stacks-pix-sdk) ![Stacks Mainnet](https://img.shields.io/badge/Stacks-Mainnet-blueviolet) ![license](https://img.shields.io/badge/license-MIT-blue)

# stacks-pix-sdk

TypeScript SDK for interacting with the StacksPix pixel board contract on Stacks.

## Installation

```bash
npm install stacks-pix-sdk
```

## Usage

```ts
import { StacksPixClient } from "stacks-pix-sdk";

const client = new StacksPixClient({
  contractAddress: "SP...",
  contractName: "stackspix"
});
```

## Development

```bash
npm install
npm run build
```

## License

MIT
