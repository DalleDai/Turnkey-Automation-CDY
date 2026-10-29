# Turnkey Automation CDY

Automate your interactions with Turnkey Wallet using this Python bot.

- 🔗 Register here: [Turnkey Wallet](https://wallet.tx.xyz/)
- 🧠 Signup with Google
- 🔐 Export Seed Phrase & Private Key
- 💾 Save your credentials safely

---

## 🚀 Features

- Auto Fetch Wallet Info
- Supports 3 Proxy Modes:
  - 🌐 Proxyscrape Free Proxy
  - 🔒 Private Proxy
  - 🟢 No Proxy
- Auto Transfer to Random Wallet
- Multi-Account Support
- Easy Configuration

---

## 🛠 Requirements

- Python 3.9+
- Pip (Python package manager)
- ETH Sepolia Testnet Balance  
  🔗 [Claim from Google Cloud Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia)

---

## 📥 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/DalleDai/Turnkey-Automation-CDY.git
    ```
   ```bash
   cd Turnkey-Automation-CDY
    ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## 📝 Configuration

* `accounts.txt` — Add one private key per line:

  ```text
  your_private_key_1
  your_private_key_2
  ```

* `proxy.txt` — Add proxies like this:

  ```text
  ip:port
  http://ip:port
  http://user:pass@ip:port
  ```

---

> ⚠️ Proxy type will be chosen inside the script when you run the bot.

---

## ▶️ Run the Bot

```bash
python bot.py
```
OR

```bash
python3 bot.py
```

Choose the desired proxy option (1, 2, or 3) when prompted.

---

## 📌 Troubleshooting

Make sure your installed library versions match `requirements.txt`.

* Check:

  ```bash
  pip show library_name
  ```
* Uninstall:

  ```bash
  pip uninstall library_name
  ```
* Reinstall with version:

  ```bash
  pip install library_name==x.x.x
  ```

---
## Happy Farming! 🚀🌾

*Brought to you by [CryptoDai3](https://t.me/cryptodai3) X [YetiDAO](https://t.me/YetiDAO)*

---

## ☕ Buy Me a Coffee

* **EVM:** `0xd07Ac11e9b2590d3788Cd9e2f833034C9555178e`

---

## 🔒 Safety & Support

### ⚠️ Important Disclaimer

* **Testnet Only** – This tool is designed for testnet environments only
* **No Liability** – Use at your own risk. Developers assume no responsibility
* **DYOR** – Always do your own research before using any automation tools

### 🛡️ Security Best Practices

* 🔐 Never use Main wallets
* 🚫 Never expose sensitive credentials
* 📜 Always review code before execution
* 💸 Use burner wallets with test tokens only

---

### 🙌 Support Our Work

Love this tool? Help us improve:

* ⭐ Star the repository
* 🔗 Share with your farming community
* 💎 Use our referral codes (where applicable)
* 💡 Contribute ideas and code

---

## 📝 License

This project is licensed under the MIT License.

---
