# simplified-musicbot
A simple Music JS for Discord Music Bots
# Simple, no need to be complicated.

# How to use? Simple!
# Install using NPM Package
```npm install simplified-musicbot```

# And start operating your bot by Login in to Discord
```js
const simple-music-bot = require('simplified-musicbot')
const bot = new simple-music-bot.Bot({token: "TOKEN", prefix: "!", RespondBot: false}) // RespondBot is to decide if the bot will respond to Bots or no
```
# Availabe Functions
> play(song name, download rate, cookie) Cookie Needed, Your bot could get status Code 429 Error.
> skip() Skip the current to play the next song
> queue() Shows a list of songs in line
> nowplaying() Shows the current Playing Song
> remove(number) Removes a song from the queue
> join() Order the bot to join the Voice Channel
> leave() Order the bot to leave the Voice Channel
> volume(number) Change the current volume of song
> loop() Repeats the current Song to play again after it ends
> stop() Pause the current song from playing
> resume() Resume the current paused song
# How to use the Functions? Simple!
```js
// The code before
bot.play("TokyoVania", 200) // You can add cookie if you don't want to get status Code 429, if that happens you need to wait 3-5 days for it to be able to use again.
```
## How to get Youtube Cookie
- navigate to YouTube in a web browser
- open up dev tools (opt+cmd+j on mac)
- go to the network tab
- click on a request on the left
- scroll down to "Request Headers"
- find the "cookie" header and copy its entire contents
[Join our Server](https://discord.gg/wSpn8Bs7uh)

