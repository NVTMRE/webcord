# Discord Bot with Web UI

## Description
A Discord bot with a Web UI for easy management and configuration.

---

## Installation

### Prerequisites
- Node.js (v18+ recommended)
- A Discord bot token (get one from the [Discord Developer Portal](https://discord.com/developers/applications))

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com//discord-bot-with-web-ui.git
   cd discord-bot-with-web-ui
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   Create a `.env` file and add the following:
   ```env
   DISCORD_TOKEN=your-bot-token
   CLIENT_ID=your-client-id
   GUILD_ID=your-guild-id
   PORT=3000
   ```

4. Start the bot:
   ```bash
   npm start
   ```

---

## Usage
1. Invite the bot to your Discord server using the OAuth2 link from the Developer Portal.
2. Open the Web UI at `http://localhost:3000` for easy bot configuration and management.

---

## License
This project is licensed under the MIT License.
