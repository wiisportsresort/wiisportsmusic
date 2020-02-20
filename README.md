# wiisportsmusic

## A Discord Music Bot

### Installation and Usage

1. Install dependencies: `npm i`   
2. Add credentials for the YouTube Data API and for your Discord Application. Either:
  - Set the environment variables `discordBotToken` and `youtubeApiKey` to their respective values.
  - Add the keys `discordBotToken` and `youtubeApiKey` to `config.json`.
3. Customize:   
  - Change the text in `text.js` to whatever you want.
  - Change `commandPrefix` in `server.js` to whatever you want.
  - Add new commands in `commands.js` by adding new keys to `module.exports`.
  - Enable the express.js landing page in `server.js`.
  
4. Start the bot: `npm start`