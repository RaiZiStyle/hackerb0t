# C-TwitchBot
It's a bot for twitch, written in C for Linux (POSIX)
It's used to mannage my [Twitch channel](https://twitch.tv/raizi_style)


# Install : 

# Run

```Bash
make run
```


# Commands: 

- !ping   
    - Writes "Pong" to the chat. Mainly for debugging purposes (i.e. testing if the bot is up and responding)

- !saymyname   
    - Writes the user's name to the chat. Again, mainly for debugging (tests if all the parameter stuff gets passed through correctly)

- !title   
    - Fetches the current channel's stream title from the Twitch API and displays it in chat.

- !die   
    - Writes a suicide note to chat and kills itself.

- !suggest [suggestion]   
    -Takes a string as an argument (can contain spaces) and appends that string to a file called "suggestions.txt", followed by a newline.

- !uptime   
    - Fetches the start time of the current channel's stream from the Twitch API and displays how long the stream has been running for in a nice format.

- !botsnack   
    - Writes "Mmmmmh, delicious Kreygasm" to chat (where Kreygasm is a Twitch emote)

- !lurk [channel name]   
    - Joins another Twitch streamer's chat and lurks there. Note that the channel name has to be supplied without the leading # (e.g. hackerc0w).

- !unlurk [channel name]   
    - Leaves a channel that was previously joined by !lurk

- !sendto [channel] [message]   
    - Displays message in channel's Twitch chat. Note that this only works if the bot is currently lurking in this channel
