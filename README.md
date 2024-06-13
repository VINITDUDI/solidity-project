# VinitCoin Smart Contract

Welcome to VinitCoin! This project hosts the code for a digital token called VinitCoin on Ethereum.

- **Details**: Name: VinitCoin, Symbol: VINIT, Decimals: 18
- **Features**: Create tokens, send/receive tokens, burn tokens to reduce supply.

### Usage

- **Setup**: Choose token details and initial supply.
- **Functions**: Mint new tokens, burn existing tokens.

### Example

```solidity
// Deploy VinitCoin with initial supply
VinitCoin vinitCoin = new VinitCoin("VinitCoin", "VINIT", 1000000);

// Mint 1000 tokens to an address
vinitCoin.mint(address recipient, 1000);

// Burn 500 tokens from an address
vinitCoin.burn(address account, 500);
```

### License

MIT License. See [LICENSE](./LICENSE) for details.

### Developer

Created by Vinit.

---

This version provides a quick overview of what VinitCoin is, how to use it, and includes essential details such as functions and licensing information.
