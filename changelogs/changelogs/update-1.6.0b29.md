---
icon: pen-to-square
---

# Update 1.6.0b29

**Changelog**:

* API documentation added to the documentation. (https://docs.disbot.xyz/api/overview - https://docs.disbot.xyz/api/api-routes)
* Fixed display of the emoji \[object object].
* Command `/connections` is now called `/channellink`
* Old language handler removed
* Fixed having to specify `guildid` in the API (changed to `GuildId`)
* Fixed Docker images not building correctly
* Fixed `/bot info` and `/bot help` "Interaction Error" because querying data and emojis took too long.
* Embed Editor v2 (Fixed: Fields could not be removed correctly)
* The backup system is now in beta.
* In the logging system, the commands have been renamed (`/logging settings`, `/logging transcript`, `/logging delete`).
* Old messages converted to the new DisBot design (**some are still missing**)
* The new `/manage tags` system (Tag System)
* New logging types:
  * AutoMod: String,
  * Emoji: String,
  * Guild: String,
  * Integration: String,
  * Invite: String,
  * Member: String,
  * Moderation: String
  * Reaction: String
  * SoundBoard: String,
  * Sticker: String,
  * Topic: String
  * Voice: String,
  * Webhook: String,
  * `// TODO`
  * Poll: String
  * Stage: String
  * Event: String
* New handler error message in the new message design
* New beta system for testing features only
* Fixed the DisBot Prewive embeds not being displayed and a server error being displayed.

**Please report message errors such as emojis, grammatical errors, etc.**&#x20;

If you have a Customer please restart the Bot!

* It may be that the bot shows b29, but for all changes to be there, you must restart!!!
