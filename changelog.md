---
title: Changelog
has_children: false
nav_order: 2
---

# Changelog


## [**v5.0.0**](https://github.com/BotSauce/BotSauce/releases/tag/v5.0.0)

- Rewrote from scratch using Discord.js's Commando framework

Changed
{: .label .label-blue }
- Now using Twitch EventSub
- Changed the usage of some commands (check \help)

Added
{: .label .label-purple }
- \kick, \monty


Fixed
{: .label .label-green }
- Minor fixes.

* * *

## [**v4.2.0**](https://github.com/BotSauce/BotSauce/releases/tag/v4.2.0)

Added
{: .label .label-purple }
- Added \send and \edit commands, which allow mods and admins to send messages as the bot and edit them

* * *

## [**v4.1.0**](https://github.com/BotSauce/BotSauce/releases/tag/v4.1.0)

Added
{: .label .label-purple }
- The bot now logs the number of attachments in a deleted message.

Fixed
{: .label .label-green }
- Minor changes/fixes.

* * *

## [**v4.0.0**](https://github.com/BotSauce/BotSauce/releases/tag/v4.0.0)

Fixed
{: .label .label-green }
- All the Twitch API stuff, and it finally works now
- \ban
- The \help command is now cleaner
- Minor changes

Added
{: .label .label-purple }
- More welcome messages
- \social (removed \twitch, \youtube and \twitter)

* * *

## [**v3.9.1**](https://github.com/BotSauce/BotSauce/releases/tag/v3.9.1)

Fixed
{: .label .label-green }
- Fixed a bug where if the user didn't have a nickname before or it got reset the nickname would show up as null in the logs

* * *

## [**v3.9.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.9.0-releasefix)

Added
{: .label .label-purple }
- Added some logging features, more specifically:
  - Join voice chat
  - Leave voice chat
  - Member leave
  - Nickname change

* * *

## [**v3.8.1**](https://github.com/BotSauce/BotSauce/releases/tag/v3.8.1)

Fixed
{: .label .label-green }
- Fixed a bug where messages got logged even though the content was never edited

* * *

## [**v3.8.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.8.0)

Added
{: .label .label-purple }
- Added some logging features, more specifically:
  - Message deleted
  - Message edited

* * *

## [**v3.7.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.7.0)

Added
{: .label .label-purple }
- Added code to make the bot automatically publish every message sent in the News (a.k.a. Announcement) channels

* * *

## [**v3.6.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.6.0)

Added
{: .label .label-purple }
- Added code for the Twitch API, more specifically:
  - Added code to subscribe to the Twitch Webhooks
  - Added code to process the Twitch Webhooks and ping the @streams role
  - Added code to refresh the New Twitch API Tokens
  - Added \refreshtokens

* * *

## [**v3.4.0 - v3.5.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.5)

Added
{: .label .label-purple }
- Added code to handle complaints and ban appeals
- Added \ban command

* * *

## [**v3.3.1**](https://github.com/BotSauce/BotSauce/releases/tag/v3.3.1)

Added
{: .label .label-purple }
- Added code to check for specific key in POST request (a simple form of authentication)
- Added basic auto-moderator that deletes a mssage if it contains a swear word

* * *

## [**v3.3.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.3.0)

Changed
{: .label .label-blue }
- Added the musicCommands function
- Moved the arrays to dedicated files (e.g. vsauce3vids was moved to vsauce3vids.js)

Added
{: .label .label-purple }
- Added basic auto-moderator that deletes a message if it contains a swear word
- Added \stop

* * *

## [**v3.2.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.2.0)

Added
{: .label .label-purple }
- Added \jakerobot

* * *

## [**v3.1.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.1.0)

Added
{: .label .label-purple }
- Added code to handle notifications, more specifically:
  - Added code to receive POST requests
  - Added code to send a message to the appropriate channel, depening on the content of the POST request
- Added code to greet new members
- Added \succ

* * *

## [**v3.0.0**](https://github.com/BotSauce/BotSauce/releases/tag/v3.0.0)

Changed
{: .label .label-blue }
- Some commands now work differently depending on if the user is in voice chat or not
- The voice chat clips are stored in /audioclips, which means that the bot doesn't have to rely on external sources

* * *

## [**v2.3.0**](https://github.com/BotSauce/BotSauce/releases/tag/v2.3.0)

Added
{: .label .label-purple }
- Added \fingers, a command that plays the clip "Hey, Vsauce. Michael here. Where are your fingers?" in voice chat, and if you aren't in vc it sends a link.

* * *

## [**v2.2.0**](https://github.com/BotSauce/BotSauce/releases/tag/v2.2.0)

Added
{: .label .label-purple }
- Added \setstatus, a command to change the status on the fly
- Added \orisit, a command that plays Moon Men in vc
- Added code to make role-specific commands

Changed
{: .label .label-blue }
- Changed the accent colour to be the same as the profile picture
- Renamed \botinfo to \info
- Renamed \random to \randomvideo
- Minor changes to existing code

* * *

## **v2.1.0**

Added
{: .label .label-purple }
- Added code to set a custom status

Changed
{: .label .label-blue }
- Minor changes

* * *

## **v2.0.0**

Major rewrite of the bot.

Added
{: .label .label-purple }
- Added a function (embedCommand) to make an embed, to help make the code more readable
- Added comments
- Added a \botinfo command that sends the version of the bot and a link to the changelog

Fixed
{: .label .label-green }
- Fixed misquote (That's a very good question. But more importantly, how much does it weigh? -> Mmm, very good question. But more importantly... how much does it weigh?)

Changed
{: .label .label-blue }
- Cleaned up code
- Minor changes

* * *

## **v1.0.0**
First release

Added
{: .label .label-purple }
- \twitch
- \youtube
- \twitter
- \random
- \caulk
- \weigh
