### Something Random On Discord
  
- This Package Is Officially By CTK WARRIOR#7923
- I Just Created V2 With More Functions And Fixed All Errors!
- Stable Version : Current Version
- Full : Something Random On Discord V2

# Usage
```js
const Discord = require("discord.js");
const Random = require("srod-v2");
const client = new Discord.Client();

client.on("ready", () => {
    console.log("Bot Is Ready With Srod-v2!");
});

client.on("message", async message => {
    if (message.content.toLowerCase() === "meme") {
        let Meme = await Random.GetMeme();
        return message.channel.send(Meme);
    }
});

client.login("Put Your Epic Bot Token Here!");
```
![](https://cdn.discordapp.com/attachments/763294769974607912/763295959761289246/unknown.png)

# Why Srod-v2?

- Fastest Speed & Easy To Use
- Small Size
- Quick Support

# Documentation

- All Functions Return Data As JSON Embeds (Discord Message Embeds)
- Color Information - Use CAPS For Name (Blue : BLUE , Orange : ORANGE) , Black If Your Provided Color Is Invalid , Embed Color Will Be Random If No Color Provided!

Link => [Click Me](https://github.com/LegendaryEmoji/srod-v2/wiki)

# More!

_Note: This Package Is Using Many Websites For Getting Stuff, Thanks To Websites Owners_

- This Package Is Made With 💖 By Ctk & Emoji

- Donations Will Help Us To Maintain This Package

- Thank You For Reading & Using This Package ;)

=== Links ===

Support Server => [Click Me](https://discord.gg/8XDYaRe)

Patreon (Legendary Emoji) (Creator Of This Package) => [Click Me](https://www.patreon.com/LegendaryEmoji)

Patreon (Ctk) (Creator Of The Old Version Of This Package) => [Click Me](https://www.patreon.com/dbdandmore)
