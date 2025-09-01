---
description: View all the different invite and message types.
---

# Types

## Invite Types

Invite Tracker allows each user to have a specific amount of **regular**, **left**, **bonus** and **fake** invites. Each invite type has a different meaning.

| Invite Type | Description                                                                                                                                                                                  |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Regular`   | This invite is added to the inviter when someone joins with their invite, no matter what.                                                                                                    |
| `Left`      | This invite is added to the inviter of the person who joined with their invite when they leave the server.                                                                                   |
| `Bonus`     | This type of invite can be added via commands by administrators.                                                                                                                             |
| `Fake`      | This type of invite is added to the inviter when someone joins with their invite, but the new member's account age is less than the server's [fake delay](../invite-tracking.md#fake-delay). |

## Message Types

### Main Message Types

| Type     | Description                                                                    |
| -------- | ------------------------------------------------------------------------------ |
| `Join`   | This message is sent in the server whenever a user joins it.                   |
| `JoinDM` | This message is sent as a direct message to a user who just joined the server. |
| `Leave`  | This message is sent in the server whenever a user leaves it.                  |

### Sub-Message Types

| Type      | Description                                                                                     |
| --------- | ----------------------------------------------------------------------------------------------- |
| `Normal`  | The message sent when the user joined the server via "normal" means.                            |
| `Vanity`  | The message sent when the user joined the server via a vanity link.                             |
| `Bot`     | The message sent when a bot joined/left the server.                                             |
| `No-Perm` | The message sent when Invite Tracker does not have enough permissions to see how a user joined. |
| `Unknown` | The message sent when Invite Tracker does not know how a user joined the server.                |

{% hint style="warning" %}
<mark style="color:$warning;">The</mark> `unknown` <mark style="color:$warning;">message is very rare. There are only a few reasons why you would get this message:</mark>

<mark style="color:$warning;">**1:**</mark> <mark style="color:$warning;"></mark><mark style="color:$warning;">Invite Tracker can not see the channel to which the invite was directed.</mark>\ <mark style="color:$warning;">(Permission problem which can be fixed easily by giving admin to Invite Tracker)</mark>

<mark style="color:$warning;">**2:**</mark> <mark style="color:$warning;"></mark><mark style="color:$warning;">Multiple people joined at the same time.</mark> \ <mark style="color:$warning;">(Impossible to fix)</mark>\
\
<mark style="color:$warning;">**3.**</mark> <mark style="color:$warning;"></mark><mark style="color:$warning;">The invites made are not being registered with discord. One use invite links will not track.</mark>\


<mark style="color:$warning;">**4:**</mark> <mark style="color:$warning;"></mark><mark style="color:$warning;">The bot just restarted and you server's invites were not in the bot's custom cache at that time, though they should be now. Remember that this should only be happening once after a bot restart.</mark> \ <mark style="color:$warning;">(Impossible to fix)</mark>
{% endhint %}
