# SolanaRush

![solanarush](https://github.com/user-attachments/assets/7b32cbdb-c057-4834-a673-71a5267af87a)

SolanaRush is a frontrunner bot for the Solana blockchain, written in Node.js. The bot scans for profitable opportunities on the Solana network and executes transactions to gain a competitive advantage. It is designed for users who want to explore automated trading strategies in the Solana ecosystem.

## Features

- Real-time monitoring of Solana blockchain transactions
- Automated detection of profitable frontrunning opportunities
- Simple configuration and customization
- Easy-to-use, prebuilt versions available for download

## Disclaimer

**Use SolanaRush at your own risk. Frontrunning might be considered unethical or illegal in certain jurisdictions. Make sure you understand the relevant laws and regulations in your area before using this bot. The developers of SolanaRush are not responsible for any damages, financial losses, or legal consequences arising from its use.**

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- Solana CLI tools (optional, but recommended)

### Installation

1. **Clone the repository or download as a ZIP:**
   - Clone the repo using Git:
     ```bash
     git clone https://github.com/solanarushdotcom/solana-pumpfun-frontrun-bot
     cd solana-pumpfun-frontrun-bot
     ```
   - Alternatively, download the repository as a ZIP from GitHub and extract it:
     - Just click on the download as zip button.

2. **Install dependencies:**
   ```bash
   npm install
   ```


### Running the Bot
To start the bot, use the following command:
```bash
node main.js
```


### Configure the environment:
Modify the `.env` file in the project root and add the following variables:
```bash
SOLANA_RPC_URL=https://api.mainnet-beta.solana.com
PRIVATE_KEY=<your-wallet-private-key>
TARGET_PROGRAM=<target-program-id>
```

The bot will connect to the Solana network, monitor for frontrunning opportunities, and execute transactions based on the predefined strategies.

## Download Prebuilt Version
If you prefer not to build the project yourself, you can download a prebuilt version from our [website](https://solanarush.app). The prebuilt version includes everything you need to get started quickly.

## Configuration
You can customize the bot's settings by editing the `config.json` file. Below are the available parameters:

- `profitThreshold`: The minimum profit (in SOL) needed to trigger a transaction.
- `gasLimit`: The maximum amount of gas to use for a transaction.

Example `config.json`:
```json
{
  "profitThreshold": 0.1,
  "gasLimit": 100000,
}
```

## Troubleshooting
- Make sure your environment variables are correctly set in the `.env` file.
- Ensure that the Solana RPC URL is reachable and the network is not experiencing downtime.
- If encountering issues with dependencies, try reinstalling them with `npm install`.

## License
SolanaRush is released under the MIT License.

## Contact
For any questions, feel free to reach out via our [website](https://solanarush.app).
