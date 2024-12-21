---
icon: pen-to-square
---

# Update 1.5.0

### Connections

* You now can connect 2 Channel (Sync to Channel) - If you write an message in #chats then the Bot send it on the other Server in the Channel
*
* Commands
* &#x20;  `/connection add` - Add the Sync Channel to the Channel from the Guild
* &#x20;  `/connection remove` - Remove the Channel Connection
* &#x20;  `/connection list` - Returns a list from all Channels

### Autoreact

* You now can add Channels in the Autoreact list to autoreact messages in a Channel
* Commands
* &#x20;  `/autoreact add` - Add a Channel on the list and a Emoji to the Channel (Multi Channels and Emojis)
* &#x20;  `/autoreact remove` - Remove a Channel from the list
* &#x20;  `/autoreact list` - Returns a list from all Channels

### Autopublish

* You now can add Channels in the Autopublish list to autopublish messages in a `GuildAnnouncment` Channel
* Commands
* &#x20;  `/autobublish add` - Add a Channel on the list
* &#x20;  `/autobublish remove` - Remove a Channel from the list
* &#x20;  `/autobublish list` - Returns a list from all Channels



### API

* Added API DB and Logic
* Commands&#x20;
* &#x20; `/api create` - Create or show the API Key
* &#x20; `/api delete` - Delete you Key
* &#x20;  `/api guild` - Add a Guild to acces the Guild on the API
* API on api.disbot.xyz **(API&#x20;**<mark style="color:red;">**currently**</mark>**&#x20;not OPEN)**



### Added

* Placeholder `{current.date}`  to all Systems they have a Embed Timestamp&#x20;
* Added `/chatfilter import` (now you can import your [sourceb.in](https://sourceb.in) Link)

### Bug Fixes

* Placeholder `{member.avatar}` now working
* Commands they are not Working in the DM has beed removed
* API Requests now 60 Seconds delayed
* Bot Join has now a new Message&#x20;
* `event/createEvent/auditlogMessageUpdate.js` currently <mark style="color:red;">disabled</mark>
* \[Twitch API] new API Key

