# Twitch-Spotify Bot

Control your Spotify player through your Twitch chat

[Get the bot here](https://spotify.beatz.dev) (read below for manual joins)

## Available commands:
| Command | Cooldown | Description |
|:-----------:|:-----------:|:------------:|
| !song / !playing | 5 seconds | Info about the currently playing song |
| !play <song name> | 2 seconds | Plays the provided song now (supports song names and URLs. Use `!play pl:<playlistname>` to play a playlist; example: `!play pl:house music`) |
| !queue <song name> | 2 seconds | Enqueues the provided song (song name or URL) |
| !volume <1-100> | 2 seconds | Changes the volume (number in percent) |
| !resume | 2 seconds | Resumes the playback |
| !pause | 2 seconds | Pauses the playback |
| !skip / !next | 2 seconds | Skips to the next song |
| !voteskip / !vs | /// | Initiates a vote skip or contributes to an ongoing voting |
| !voteskip <on/off> | 2 seconds | Enables/disables vote skips (default: off), broadcaster only |
| !voteskip <0 - 100%> | 2 seconds | Changes the required amount of vote skips in relation to the amount of stream viewers, broadcaster only |
| !previous | 2 seconds | Plays the previously played song |
| !save | 2 seconds | Saves the currently playing song to your fav. songs |
| !shuffle <on/off> | 2 seconds | Enables/disables shuffling |
| !repeat <on/off> | 2 seconds | Enables/disables repeating |
| !userlevel <song / management> <user / sub / vip / mod / broadcaster> | 2 seconds | Changes the minimum user level for using the !song command (`song`) or other commands that modify the Spotify player (`management`), broadcaster only |
| !spotjoin | /// | Makes the bot join a new channel after the user authorized the bot [here](https://spotify.beatz.dev), bot owner only |
| !updatedevice | 2 seconds | Changes the Spotify device that the bot interacts with, needs to be used after reinstalling Spotify or getting a new PC for example, broadcaster only |

Arguments in `<>`'s are necessary and need to be added to the command. Replace `<song name>` with the actual name of the song you want to use.<br>
When trying to play/enqueue a new song, try to provide the artist's name (in case there are multiple songs with the same name) to increase the chance of fetching the correct song.<br>
Make sure to grant VIP privileges to `beatz` (run `/vip beatz` in the Twitch chat) to ensure that the bot is always able to send messages.
  
Create a channel points reward named "Song Request" to allow your viewers to enqueue songs by spending channel points. Both song names and Spotify URLs are supported.

#### If you require a manual join of the bot or need help, contact me here (preferably through Twitch):
* Twitch (Whispers or write in my chat): [Beatz](https://twitch.tv/beatz)
* Twitter: [@Beatz141](https://twitter.com/beatz141)
* Discord: [Beatz#0001](https://discord.com/users/462263905842888714)
