# ModMail

Welcome to ModMail. ModMail is an open-source ModMail bot that helps Discord Guild Moderators help their community easily and privately!

Information: This bot is written in eris. You'll need to install [node.js](https://nodejs.org/en/) to run it. This bot not hosted anywhere, you will have to host it yourself. For starter users you can use things like [replit.com](https://replit.com/).

# Getting started
To setup the bot, head over to [Discord's developer portal](https://discord.com/developers/applications), click new application, then bot, and add a bot account. Copy the token and put it into the token slot of the .env file. To run, ensure you have all the components installed;

`npm install eris`
`npm install moment`
`npm install axios`

### Configure the bot in config.js

```
    token: 'YOUR BOT TOKEN HERE',
    databaseToken: 'YOUR MONGODB TOKEN HERE', // We use MongoDB to store data! 

    mainGuild: '', // Main ModMail Guild ID (server)
    logChannel: '', // Channel ID of where you want ModMail Logs
    mailChannel: '', // **Category** ID of where you want ModMail channels to be!
    modRoles: [''],

    status: 'DM me for support!', // This will be the bot's playing status
    color: '0xfcfcfc', // Color of logging embeds!
    prefix: '!', // Bot prefix for commands
    msgPrefix: 'Ice Team' // The prefix that shows on messages (ex. Staff pink,: Hi!)
```

[You Can Get Mongo Db Url From The Ice](https://discord.gg/3D4PkVyrUt)
Made By AsdBee [Original Repository](https://github.com/asdbee/ModMail)
