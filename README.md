📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)


> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> > > Help me with your referral [Link](https://t.me/fomo/app?startapp=ref_ACBRX)

## 🚀 Getting Started

To get started with the bot, follow these steps:

> Remember to download Nodejs version: **22.11.0** and NPM version: **10.9.0**


0. **Dowload NodeJS to run the bot**

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `run.bat` for windows or `run.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents axios meo-forkcy-colors https-proxy-agent socks-proxy-agent 
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json

  //for each pair fill the order and the coin you want, i have the `coins.js` file for manage all the coins, or you just set by default and dont touch anything
{
  "limit": 100,
  "countdown": 300,
  "delayEachAccount": [5, 8],
  "pair1": {
    "symbol": "BTC",
    "Long-Short": "Long"
  },
  "pair2": {
    "symbol": "BTC",
    "Long-Short": "Short"
  },
  "pair3": {
    "symbol": "BTC",
    "Long-Short": "Long"
  },
  "referralCode": "ACBRX"
}


```

### 2. `datas.txt` 🗂️ - Get it from here >>> [Link](https://t.me/KeoAirDropFreeNe/257/6879)

```txt
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - Cannot update yet.

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)


```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it
> To run the bot, use the following command: `cd "ether-drops"; node meomundep`

🎇Enjoy!
