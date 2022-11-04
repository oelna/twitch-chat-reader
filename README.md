# Twitch Chat Reader

A mostly self-contained client to Twitch chat, use as OBS overlay.

This uses `justinfan+number` as a way to read chat without auth. Also, it loads badge data from [twitchinsights.net](https://twitchinsights.net/badges), so that may break in the future. Use at your own peril.

[Demo](https://oelna.github.io/twitch-chat-reader/) (uses channel [twitch.tv/amaz](https://www.twitch.tv/amaz), on at 4pm CET)

## Instructions

- download `index.html` and `tmi.min.js`
- set channel and options (line ~100)
- set font to use in CSS (line ~10)
- set up in OBS as `Browser Source` ("local file")

This was working in 2022. If it's not, don't @ me.
