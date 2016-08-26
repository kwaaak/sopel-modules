# sopel-modules
## Modules for Sopel IRC Bot

Requirements:

* [Sopel 6.x](https://github.com/sopel-irc/sopel/)
* [Python 3.3+](https://www.python.org/)

Contents:

* channel.py - channelmodule (BlizzCon/QuakeCon counters, reddit queries, random youporn comments and more nonsense)
* streams.py - twitch.tv and hitbox.tv integration (API query, channel announcement when stream goes online)
* ud.py - adds .urban command to query [urbandictionary.com](http://urbandictionary.com)
* youtube.py - adds youtube APIv3.0 support to Sopel (requires API key)
* update.py - adds .update admin command to update modules via git
* new_weather.py - fixes broken .weather command requires forecast.io and google url shortener API key
* talk.py - adds .talk command 

most of my modules are based on / developed by https://github.com/dasu/
