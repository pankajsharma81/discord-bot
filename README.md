# Discord Bot

A simple Discord bot that uses Google Gemini AI to generate responses to user messages.

## Features
- Listens to messages in your Discord server
- Uses Google Gemini AI (via @google/genai) to generate intelligent responses

## Prerequisites
- Node.js (v16 or higher recommended)
- A Discord bot token ([How to create a Discord bot](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot))
- Google Gemini API key ([Get an API key](https://ai.google.dev/))

## Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/discord-bot.git
   cd discord-bot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment variables**
   Create a `.env` file in the project root with the following content:
   ```env
   DISCORD_TOKEN=your_discord_bot_token
   GEMINI_API_KEY=your_google_gemini_api_key
   ```

4. **Run the bot**
   ```bash
   node index.js
   ```

## Usage
- Invite the bot to your Discord server.
- Send any message in a channel the bot has access to. The bot will reply with an AI-generated response.

## Dependencies
- [discord.js](https://discord.js.org/)
- [@google/genai](https://www.npmjs.com/package/@google/genai)
- [dotenv](https://www.npmjs.com/package/dotenv)

## License
ISC
