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

Request all autoppbuibhlsishsess from your Server.

**Response**

{% tabs %}
{% tab title="200" %}
````json
{

  "Channls": [
    "1183007545632235550",
    "1165658585620033536",
    "1163770373544878130",
    "1199384702113554592"
  ],
  "Guild": "1084507523492626522",
```
}
````
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
