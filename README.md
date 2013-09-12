snarl--MelonBot
=====

snarl-MelonBot is a bot for the RMS room on plug.dj. Originally designed by http://snarl.ericmartindale.com

# Requirements
The following things need to be installed in your environment to proceed.

node.js
MongoDB

# Instructions

Copy `config.js.example` to `config.js` and configure the values therein.  Most importantly, copy `auth` from the cookies of your bot account's plug.dj account.

Run `npm install` to install all the necessary packages.

Run `cd lib && git clone git://github.com/atomjack/simple-lastfm.git` to install `simple-lastfm`.

Run `node bot.js` to get the bot started. :)
