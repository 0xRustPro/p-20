# 🚀 **Copy trading Bot With Rust**

## hoose a Trader (Signal Provider): ##

-The bot connects to a skilled trader’s account or strategy.

-This trader is often called a "leader", "signal provider", or "master".

## Mirror Their Trades Automatically: ##

-When the master opens or closes a position, your account automatically mirrors the same action — often within milliseconds.

-Trades are copied proportionally, depending on how much you're willing to risk.

## Automation Layer: ##

-The bot watches for new trades via:

API access to the trader’s account

Blockchain activity (on-chain copy trading)

WebSocket streams or mirror services

-Then it uses your API keys to execute the same trades on your behalf.

# 💬 Contact Me

If you have any question or something, feel free to reach out me anytime via telegram, discord or twitter.
<br>
#### 🌹 You're always welcome 🌹

Telegram: [@Leo] (https://t.me/Rust0x_dev) <br>

### 🎯 Example
- Source Transaction: https://solscan.io/tx/2nNc1DsGxGoYWdweZhKQqnngfEjJqDA4zxnHar2S9bsAYP2csbLRgMpUmy68xuG1RaUGV9xb9k7dGdXcjgcmtJUh
- Copied Transaction: https://solscan.io/tx/n2qrk4Xg3gfBBci6CXGKFqcTC8695sgNyzvacPHVaNkiwjWecwvY5WdNKgtgJhoLJfug6QkXQuaZeB5hVazW6ev
- Target Wallet: GXAtmWucJEQxuL8PtpP13atoFi78eM6c9Cuw9fK9W4na
- Copy Wallet: HqbQwVM2fhdYJXqFhBE68zX6mLqCWqEqdgrtf2ePmjRz
### 🎯 **Key Features**

- 🛰️ **Real-time WebSocket Streaming**:
  Connects to Solana's blockchain through Helius geyser RPC WebSocket and listens for new transactions, specifically Tx that target wallet is singer
- 🔍 **Filter Transactions**:
  Filters transactions as soon as possible and fast.
  maybe it takes about 0.3ms totally
- 📊 ** Make Copy transaction **:
  Using pumpfun program id and raydium module you can make copy trasaction.

---

## 🚀 **Getting Started**

Follow these steps to get your **Copy trading Bot** up and running!

### Prerequisites

- Cargo version 1.84.0 installed on your system
- A Solana wallet with access to the Helius Geyser RPC API

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com//0xRustPro/Copy-Trading-Bot-Rust
   ```

2. **Install Dependencies**:

   Navigate to the project directory and run the following command:

   ```bash
   cd copy-trading-bot
   cargo build
   ```

3. **Configure ENV**:

   Replace the API token in the `ENDPOINT` variable:

   ```ts
   const ENDPOINT = "https://mainnet.helius-rpc.com";
   const WSS_ENDPOINT = "wss://atlas-mainnet.helius-rpc.com";
   const TARGET = "YOUR_API_TOKEN";
   ```

4. **Run the Bot**:

   Start the bot by running:

   ```bash
   cargo run
   ```

---
