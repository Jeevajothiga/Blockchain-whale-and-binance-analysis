# 🐋 **Blockchain Whale & Binance Tracker**  

## 🚀 **Track & Analyze Whale & Binance Transactions on Ethereum**  

This repository provides **Python scripts to analyze Ethereum transactions**, including:  
- ✅ **Random Whale Analysis** – Track a high-value Ethereum wallet's activity.  
- ✅ **Binance Wallet Analysis** – Monitor Binance's ETH movements & interactions.  
- ✅ **Gas Fee & Timing Analysis** – Understand when whales make transactions & how much they pay.  
- ✅ **Stablecoin & DeFi Interaction** – Detect if whales or Binance are converting ETH to USDT, USDC, or using DeFi.  

---

## 🐋 **Random Whale Analysis – Key Findings:**
- ✅ **Whale Received More ETH Than Sent** → This suggests accumulation, meaning the whale might be bullish on ETH.
- ✅ **Major ETH Movements Detected** → Large transactions show the whale is making strategic buys/sells instead of small trades.
- ✅ **Gas Fee Spikes on Certain Days** → High gas fees on specific days suggest the whale prioritizes speed for important transactions.
- ✅ **Stablecoin Interactions** → Some ETH was converted to USDT/USDC, possibly indicating profit-taking or risk management.
- ✅ **Transaction Timing Matches Market Events** → Whale activity aligns with big market movements, suggesting institutional involvement.

---

## 🏦 **Binance Wallet Analysis – Key Findings:**
- ✅ **High ETH Inflow & Outflow** → Binance is constantly receiving & sending ETH, indicating strong trading activity.
- ✅ **Major ETH Sent to Stablecoin Contracts** → Binance is likely converting ETH into USDT, USDC, or BUSD, meaning liquidity shifts.
- ✅ **Gas Fees Show Peak Trading Hours** → Binance processes large ETH movements during U.S. & European trading hours, following market cycles.
- ✅ **Some Transactions Involve Whales** → Some Binance transactions are linked to large whale addresses, meaning whales may be depositing/selling ETH.
- ✅ **No Direct ETH → Stablecoin Swaps Found** → Binance may be handling stablecoin conversions internally, without using on-chain swaps.

---

## ⛽ **Gas Fee & Transaction Timing Analysis – Key Findings:**
- ✅ **Whales Spend More Gas During Market Volatility** → High gas usage correlates with major ETH price movements.
- ✅ **Binance’s Gas Fees Show Trading Volume Spikes** → Binance processes more transactions during key market hours.
- ✅ **Certain Wallets Pay Extreme Gas Fees** → Some transactions indicate urgent, high-priority trades, likely whales making big moves.
- ✅ **Low Gas Fees on Weekends** → Suggests whales & Binance reduce activity when trading volumes are lower.

---

## 📌 **Overall Summary:**
- 📊 **Whales Accumulate ETH Before Market Surges** – They buy more before price increases.
- 📊 **Binance’s Transactions Align with Market Trends** – Binance’s stablecoin activity & ETH movements reflect market conditions.
- 📊 **Gas Fees Indicate Trading Volume & Urgent Transactions** – High fees suggest whales & institutions are making big trades.
- 📊 **Stablecoin Interactions Show Liquidity Moves** – When Binance & whales convert ETH into USDT/USDC, it signals risk management or market exit strategies.

---  

## 📌 **Features**  
✔ **Fetches** transaction data from **Etherscan API** 📡  
✔ **Cleans & processes** data into a structured **Pandas DataFrame** 📊  
✔ **Finds** top interacting wallets (**senders & receivers**) 🔍  
✔ **Identifies** transaction trends by **day & time** ⏳  
✔ **Detects** high gas fee transactions & DeFi interactions ⛽  
✔ **Plots** gas fee trends & transaction activity 📈  

---  

## 📌 **Setup & Installation**  

### 🔹 **1️⃣ Clone the Repository**  
```bash  
git clone https://github.com/yourusername/Blockchain-Whale-Tracker.git  
cd Blockchain-Whale-Tracker  
```

### 🔹 **2️⃣ Install Dependencies**  
```bash  
pip install requests pandas matplotlib  
```

### 🔹 **3️⃣ Get an Etherscan API Key**  
1. Sign up on **[Etherscan](https://etherscan.io/apis)**  
2. Generate a **free API key**  
3. Replace `"your_api_key_here"` in the scripts with your actual API key  

---  

## 📌 **Scripts & Usage**  

### 🔹 **1️⃣ Analyze a Random Whale 🐋**  
```bash  
jupyter notebook whale_analysis.ipynb  
```
- **Tracks** ETH movement for a **large Ethereum wallet**  
- **Finds** top senders & receivers  
- **Detects** stablecoin transactions  

### 🔹 **2️⃣ Analyze Binance Wallet 🏦**  
```bash  
jupyter notebook binance_analysis.ipynb  
```
- **Tracks** ETH movement for **Binance's official hot wallet**  
- **Analyzes** gas fees & transaction timing  
- **Checks** if Binance is moving ETH into stablecoins  

---  

## 📌 **Example Outputs**  
```bash  
✅ Transactions Fetched Successfully!  
🔹 Total ETH Sent: 45,200 ETH  
🔹 Total ETH Received: 50,500 ETH  
🔹 Top 10 Wallets That Sent ETH to This Address:  
  - 0xa88902d6e9... (50 transactions)  
  - 0x3aadb31f8e... (20 transactions)  
```
📊 **Plots of transaction trends & gas fees** will also be generated!  

---  

## 📌 **Future Improvements**  
- 🚀 **NFT Tracking** – Analyze whale activity in **NFT markets** like OpenSea  
- 🚀 **Real-Time Tracking** – Monitor **live transactions**  
- 🚀 **DeFi Loan & Swap Detection** – Find whales using **Aave, Uniswap, Curve**  

---  

## 📌 **Contributing**  
Feel free to **fork, improve, and submit pull requests!** 🤝  

---  

## 📌 **License**  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---  

## 📌 **Author**  
👨‍💻 **Built by Jeeva Jothiga – Let's Connect! 🚀**  

