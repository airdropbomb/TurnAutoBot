# TurnKey Auto Bot

Automated bot for executing transactions on Ethereum Sepolia testnet with multiple wallets. This bot helps automate daily transaction batches for airdrop farming and testnet interaction.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Ethereum Sepolia testnet ETH for gas fees
- Private keys for your wallets

## Installation

1. Clone the repository:
```bash
git clone https://github.com/airdropbomb/TurnAutoBot.git && cd TurnAutoBot
```

2. Install dependencies:
```bash
npm install
```

3. Create a `pk.txt` file in the root directory:
```bash
nano pk.txt
```

4. Configure your environment variables in `pk.txt`:
```env
PRIVATE_KEY_1
PRIVATE_KEY_2
PRIVATE_KEY_3
# Add more private keys as needed (PRIVATE_KEY_4, PRIVATE_KEY_5, etc.)
```

## Usage

1. Start the bot:
```bash
npm start
```
