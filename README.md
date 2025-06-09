# 💠 Discord Whitelist Bot

A professional Discord bot for handling Whitelist registration using `Buttons`, `Modals`, `Embeds`, and Admin approval system. Perfect for Web3/NFT communities or any gated-access systems.

---

## 📌 Features

- ✅ Whitelist Registration via Modal
- 🔒 Admin Approval System
- 🧾 Log Channel with Full User Info
- 🔁 Duplicate Check & Data Validation
- ⏳ Auto-Close Inactive Sessions
- ✨ Fully Customizable Embed & Button UI

---

## ⚙️ Requirements

- Node.js (v18.x or later)
- Discord Bot Token
- A `.env` file for environment variables

---

## 🚀 Installation

1. **Clone this repository**

```bash
git clone https://github.com/yourusername/discord-whitelist-bot.git
cd discord-whitelist-bot

npm install
bot_config.js Chang
DISCORD_TOKEN=your_discord_bot_token
CLIENT_ID=your_bot_application_client_id
GUILD_ID=your_test_server_id (optional for testing)
LOG_CHANNEL_ID=channel_id_for_logging

node bot-whitelist.js

🔁 Keep the bot running 24/7

npm install -g pm2
pm2 start index.js --name whitelist-bot
pm2 save
pm2 startup

To monitor:
pm2 logs

whitelist-bot/
├── node_modules
├── bot-whitelist.js
├── bot_config.js
├── .env
├── package.json
└── package-lock.json

