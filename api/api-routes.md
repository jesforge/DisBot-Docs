---
icon: arrow-progress
---

# API Routes

## Get Autoroles

<mark style="color:orange;">`GET`</mark> `/autoroles`

Request all autoroles from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "GuildID": "",
  "Roles": [],
  "__v": 2
}
```
{% endtab %}

{% tab title="401" %}
```json
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="404" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Autoreacts

<mark style="color:orange;">`GET`</mark> `/autoreacts`

Request all autoreacts from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "Channel": "",
  "Guild": "",
  "Emoji": "",
}
```
{% endtab %}

{% tab title="401" %}
```
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="Untitled" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Autopulish

<mark style="color:orange;">`GET`</mark> `/autopublishs`

Request all autopublishes from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "Channls": [],
  "Guild": "",
}
```
{% endtab %}

{% tab title="401" %}
```
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="404" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Ticketmenus or Ticketbuttons

<mark style="color:orange;">`GET`</mark> `/ticketmenus`

<mark style="color:orange;">`GET`</mark> `/ticketbuttons`

Request all ticketmenus/ticketbutton from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
GuildID: String,
Category: String,
Handlers: String,
MenuID: String,
Transscript: String,
MessageID: String,
TicktEmbedJSON: String,
ChannelName: String,
Thread: Boolean,
MessageTempleateID: String,
TicketMessageOpen: String,
TicketBlackListRole: String,
Image: String,
Thubmnail: String,
FooterImage: String,
AuthorImage: String,
Timestamp: String,
Modal: Boolean,
ModalName: String,
ModalOptions1: {
  Name: String,
  Placeholder: String,
  Type: String,
},
ModalOptions2: {
  Name: String,
  Placeholder: String,
  Type: String,
},
ModalOptions3: {
  Name: String,
  Placeholder: String,
  Type: String,
},
ModalOptions4: {
  Name: String,
  Placeholder: String,
  Type: String,
},
ModalOptions5: {
  Name: String,
  Placeholder: String,
  Type: String,
},
}
```
{% endtab %}

{% tab title="401" %}
```
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="404" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Messages

<mark style="color:orange;">`GET`</mark> `/messages`

Request all messages from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
GuildID: "",
Content: "",
EmbedJSON: "",
UUID: "",
Name: ""
}
```
{% endtab %}

{% tab title="401" %}
```
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="404" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Permissions

<mark style="color:orange;">`GET`</mark> `/permissions`

Request all permissions from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
GuildID: "",
Permissions: {
  Autopublish: "",
  Autoreact: "",
  Autoroles: "",
  Discord: "",
  Chatfilter: "",
  Moderation: "",
  Embed: "",
  Giveaway: "",
  Ticket: "",
  LeaveWelcome: "",
  Level: "",
  Tempvoice: "",
  Socialmedia: "",
  Info: "",
  Other: "",
  Backup: "",
  Emoji: "",
  Birthday: "",
  Connections: "",
  SyncChannel: "",
  Reminder: "",
  AutoDelete: "",
  Economy: "",
  }
}
```
{% endtab %}

{% tab title="401" %}
```
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="404" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Tickets

<mark style="color:orange;">`GET`</mark> `/tickets`

Request all tickets from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
ChannelId: String,
ThreadID: String,
Claimed: Boolean,
UserhasClaim: String,
Looked: Boolean,
TicketOwner: String,
ChannelCreated: String,
MembersID: Array,
Handlers: String,
SetupChannel: String,
SetupMessageId: String,
Transscript: String,
}
```
{% endtab %}

{% tab title="401" %}
```
{
  "error": "Auth token is missing"
}
{
  "error": "Invalid Auth Token"
}
{
  "error": "Guild ID is missing"
}
```
{% endtab %}

{% tab title="404" %}
```
{
  "error": "No <route> Found"
}
```
{% endtab %}
{% endtabs %}

## Get Version

<mark style="color:orange;">`GET`</mark> `/version`

Get the current version from Disbot ([https://api.disbot.xyz/version](https://api.disbot.xyz/version))&#x20;

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
version: ""
}
```
{% endtab %}
{% endtabs %}
