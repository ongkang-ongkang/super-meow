# Supermeow - Auto Claim Bot

🔗 **Referral Link**: [Supermeow]()

## 📢 Telegram Group

Join our Telegram group to stay updated and get instructions on how to use this tool:

- [Garapan Airdrop - Channel](https://t.me/garapanairdrop_indonesia)
- [Sobat Ongkang Ongkang - Group](https://t.me/ongkang_ongkang)


## 🌟 Features

| Feature       | Status  | Description                       |
| ------------- | ------- | --------------------------------- |
| Auto Check-in | On/Off  | Check-in daily to get more points |
| Auto Do Task  | On/Off  | Complete tasks                    |
| Auto Claim    | Dafault | Claim points when available       |

## 🚀 Run File

```
git clone https://github.com/ongkang-ongkang/supermeow.git && cd supermeow && python -m pip install -r requirements.txt
```

| Run with Proxy                   | Run without Proxy   |
| -------------------------------- | ------------------- |
| `bot-proxy.py` `data-proxy.json` | `bot.py` `data.txt` |

## ⚠️ Note

- Get auth data in the `Network` tab in DevTools.
  - `Network` --> Filter `info` or `balances` --> `Payload` --> `auth_data`
  - Starts with `%7B%22query_id%22...`
- Auto features: Change `false` to `true` in the `config.json` file.
- Supported commands: `/run_bot` `/proxy` `/proxy_web` (Join group to use these commands).
