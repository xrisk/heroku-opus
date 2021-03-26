# heroku-opus

Installs the opus codec for usage with heroku apps. 

## How to use

https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app#adding-a-buildpack

Please leave a star if you found this useful.

Also see the warning below.

## Example use case

* YouTube downloader - use youtube-dl with https://github.com/xrisk/ffmpeg-lame-yasm. See for example: https://github.com/xrisk/webdl
* Discord music bot - use discord.py (https://github.com/Rapptz/discord.py/blob/master/examples/basic_voice.py) with this buildpack

## Warning

Do not use `discord.opus.load_opus` (for discord.py and similar). This library will be picked up by discord.py automatically!

