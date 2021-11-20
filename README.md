## Why choose our api?
our api is unique for the Unique Ai

## How to use it

Join our [Discord](https://discord.gg/7MEZZHD6Wh) and make a ticket and use za/genapi and you can get your api (**DON'T SHARE IT**)

and now go on https://api.notzerotwo.ml/admin/test?api=ApiKey and you can see if it work

# All different Endpoint

**Admin: test**

**data: colorinfo,covid,crypto,github,hypixel,npm,weather**

**Fun: 8ball,advice,catfact,chatbot,clown,dadjoke,fact,meme,TexttoImage,wouldyourather**

**Image: achievement,alert,beautiful, bobross,busted,changemymind,delete, drake,fear-man, gay,invert, jokeoverhead,lisapresentation, panik-kalm,pixelizem simp,spongebob-burn,spotify,this-guy,triggered,tuxedo-pooh,tweet,wanted,welcomecard**

**Security: cve,dangerous,domain**

**Text: compile,decode-binary,emojify,encode-binary,question,translate,zalgo**

## Example

Request a question

```javascript
const { Message } = require('discord.js');
const fetch = require('node-fetch')

const response = await fetch(`https://api.notzerotwo.ml/text/question?api=Apikey&question=${args[0]}`);
let json = await response.json();

Message.channel.send(`The short answer is: ${json.ShortResponse} or the Full Answer is: ${json.Response}`)
//or
//msg.channel.send(`The short answer is: ${json.ShortResponse} or the Full Answer is: ${json.Response}`)
```
