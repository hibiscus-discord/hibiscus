# 🌺 ***Hibiscus*** 

### Command Handler for [Eris](https://abal.moe/eris 'Created by abalabahaha#9503')
### **Official Support Server: https://discord.gg/Kzm9C3NYvq**

[![npm](https://img.shields.io/npm/dt/@skullbite/hibiscus?style=for-the-badge)](https://www.npmjs.com/package/@skullbite/hibiscus)


### Basic Usage
```js
const hibiscus = require("@skullbite/hibiscus")

const bot = new hibiscus.Bot('token', {}, {prefix: "!"})

bot.addCommand(
    new hibiscus.Command({name: "greet"})
    .setExec(async function(ctx) {
        ctx.send(`Hi ${ctx.author.username}`)
    })
)

bot.connect()
```
