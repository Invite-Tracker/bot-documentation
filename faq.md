---
description: Frequently asked questions regarding Invite Tracker.
---

# FAQ

## What is the default prefix for Invite Tracker?

Invite Tracker's prefix is `/`.

Due to Discord changing the prefixes, the forward slash will be the prefix used. This cannot be changed due to Discords' newer system.

## Why is Invite Tracker not responding to my commands?

Firstly, make sure the bot is not offline and that there are no current outages by checking Invite Tracker's support server's [<mark style="color:purple;">outage channel</mark>](https://discord.gg/MfTenmfQuP).

If there are no obvious outages, please mention the bot to check if Invite Tracker has enough permissions to view the channel. (You can not add any text other than the actual mention for this to work)&#x20;

Lastly, if Invite Tracker is not responding to a mention, please make sure Invite Tracker has the right permissions. You can do this by running the `/permscheck` command and then assign all of the missing permissions to it. All of Invite Tracker's required permissions are listed [<mark style="color:purple;">here</mark>](faq.md#what-are-the-required-permissions-for-invite-tracker).

## How do I set up invite roles?

This feature has sadly been disabled due to it being against Discord's Developer Terms of Service. Having any features that include rewarding invites just enables server advertisement in servers and direct messages. This is something Discord views as unsolicited advertisement, which is exactly what breaks the Discord Developer Policy.

{% hint style="info" %}
<mark style="color:blue;">Invite requirements for giveaways is also disabled due to being against Discord's Developer Terms of Service for the same reason as invite roles.</mark>
{% endhint %}

## What is the required permission to access the dashboard?

In order for your administrators or moderators to access Invite Trackers dashboard they will need the _Manage Server_ permission enabled on their role.

## What are the required permissions for Invite Tracker?

All of Invite Tracker's required permissions are required for a reason, so please be careful about what permissions you remove. If you do start to remove permissions, you have a high likelihood of rendering some of Invite Tracker's features useless.

| Permission             | Usage                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------- |
| `Add Reactions`        | Needed to add reactions to messages such as giveaways                                       |
| `Attach Files`         | Needed to send statistical graphs                                                           |
| `Embed Links`          | Needed to send embeds such as leaderboards and embedded join/leave messages                 |
| `Manage Messages`      | Needed to pin leaderboards and to remove reactions for giveaways                            |
| `Manage Roles`         | Needed to grant roles such as reward roles and auto roles                                   |
| `Manage Server`        | Needed to view the server's active invites so it can track them                             |
| `Read Messages`        | Needed to view messages so it can either respond to or track them                           |
| `Read Message History` | Needed to view older messages so it may edit them such as pinned leaderboards and giveaways |
| `Send Messages`        | Needed to respond to commands and send join, join dm and leave messages                     |
| `Use External Emojis`  | Needed to use private emojis for the help pages, for example                                |
