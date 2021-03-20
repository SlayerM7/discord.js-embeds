# What is thi? 

Easy to use shuffle embeds with discord.js

# Installation

`npm i discord.js-embeds`

then...


# Usage

__Basic bot example__

```js
import reactionPage from "discord.js-embeds"

// or

const reactionPage = require('discord.js-embeds')


// Create a array of all embeds to shuffle through

const pages = [
    embed1, 
    embed2, 
    embed3,
    ...
]


// Call the method, The first two arguments are required

reactionPage(message, pages, emojisList, timeOut)
```