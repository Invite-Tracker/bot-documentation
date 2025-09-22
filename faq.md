---
description: Frequently asked questions regarding Invite Tracker.
---

# FAQ

## What is the default prefix for Invite Tracker?

Invite Tracker's prefix is `/`.

Due to Discord changing the prefixes, the forward slash will be the prefix used. This cannot be changed due to Discord's newer system.

## Why is Invite Tracker not responding to my commands?

Firstly, make sure the bot is not offline and that there are no current outages by checking Invite Tracker's support server's [outage channel](https://discord.gg/MfTenmfQuP).

If there are no obvious outages, please mention the bot to check if Invite Tracker has enough permissions to view the channel. (You can not add any text other than the actual mention for this to work)&#x20;

Lastly, if Invite Tracker is not responding to a mention, please make sure Invite Tracker has the right permissions. All of Invite Tracker's required permissions are listed [here](faq.md#what-are-the-required-permissions-for-invite-tracker).

## How do I set up invite roles?

This feature has sadly been disabled due to it being against Discord's Developer Terms of Service. Having any features that include rewarding invites just enables server advertisement in servers and direct messages. This is something Discord views as unsolicited advertisement, which is exactly what breaks the Discord Developer Policy.

{% hint style="info" %}
<mark style="color:$info;">Invite requirements for giveaways is also disabled due to being against Discord's Developer Terms  of Service for the same reason as invite roles.</mark>
{% endhint %}

## How do I setup Invite Tracker?

{% embed url="https://youtu.be/iUs6rr28tiY" %}
A tutorial video on how to SETUP the Invite Tracker bot!
{% endembed %}

## How do giveaways work?

{% embed url="https://youtu.be/JSxU-0oPmaE" %}
A tutorial video on how giveaways work and how to set them up.
{% endembed %}

## How do giveaway "extra entries" work?&#x20;

On free servers, there is an option to vote for the bot to gain **1 extra entry** for a giveaway.\
It is important to note that this extra vote is not reflected in the "Participants" count. However, the bot will check if you have voted when the giveaway ends, so make sure to keep voting [here!](https://top.gg/bot/720351927581278219/vote)&#x20;

## How do I manage my premium subscription?

Users can manage their dashboard subscriptions from the new My Account page. Click [here](invite-tracker/dashboard/my-account.md) to see how it works.

## What is the required permission to access the dashboard?

In order for your administrators or moderators to access Invite Trackers dashboard they will need the _Administrator_ permission enabled on their role.

## What are the required permissions for Invite Tracker?

All of Invite Tracker's required permissions are required for a reason, so please be careful about what permissions you remove. If you do start to remove permissions, you have a high likelihood of rendering some of Invite Tracker's features useless.&#x20;

Keep in mind that just giving the permissions to it's role sometimes may not work as a specific channel has overridden it's permissions. So, to fix that you either need to add the Invite Tracker role in the specific channel and regrant the permissions needed or add _Administrator_ to the Invite Tracker role.

If you want to give Invite Tracker all permissions without any more hassle, you may grant _Administrator_ to the Invite Tracker role. By default when adding the bot, _Administrator_ is already applied.

| Permission             | Usage                                                                                        |
| ---------------------- | -------------------------------------------------------------------------------------------- |
| `Administrator`        | Grants all permissions                                                                       |
| `Manage Server`        | Needed to view the server's active invites so it can track them                              |
| `Manage Roles`         | Needed to grant roles such as reward roles, auto roles, winner roles, and verification roles |
| `Manage Channels`      | Needed for the bot to be able see invites created in a channel for tracking invites          |
| `Kick Members`         | Needed to kick members for verification action                                               |
| `Ban Members`          | Needed to ban members for verification action or for mass bans                               |
| `View Channel`         | Needed to view messages so it can either respond to or track them                            |
| `Send Messages`        | Needed to respond to commands, edit messages, and send join/leave/test messages              |
|  `Pin Messages`        | Needed to pin leaderboards                                                                   |
| `Embed Links`          | Needed to send embeds such as leaderboards, embedded join/leave messages, and giveaways      |
| `Attach Files`         | Needed to send statistical graphs and exports of the leaderboard                             |
| `Read Message History` | Needed to view older messages so it may edit them such as pinned leaderboards and giveaways  |
| `Add Reactions`        | Needed to react to join/leave messages                                                       |
| `Use External Emojis`  | Needed to use server emojis in your join/leave messages                                      |

## Why are invites not counting?

### Verification system in place.&#x20;

If you have a verification system in place, users being invited need to verify for your invites to be counted. You can check your plugin by going to the Dashboard -> Verification -> Verification Level to see if it is enabled. If you are using the plugin, make sure the level is set to _Disabled_.

### User is blacklisted from invites being counted.&#x20;

It may be that this user is blacklisted, meaning their invites are not being counted. You can check this by going to the Dashboard -> Invite Tracking -> User Invites Blacklist.

### The bot is missing some permissions, check that it has:

* Permission to _**Manage Server**_.
* Permission to _**View Channel**_ and _**Manage Channel**_ in every channel a member can create a invite for.

Alternatively you can provide the bot with _**Administrator**_ permissions by adding it to the Invite Tracker role. This will override any conflicting channel permissions you may have.

### The user has not created this link.&#x20;

They may be using another user's link. You can check if you own a link by running `/findlink`. Vanity URL's also do not count as invites. One use invites will not count as they are deleted after being used, make sure you're creating an invite with more than one use.

### The link being used did not register.&#x20;

If you have checked all of the above, creating a new invite link should register and count.

### I've checked all of these, and it still doesn't work!

Please make sure you have double checked all of these possible reasons. If you have, we are always happy to assist you further with your inquiry in our [support discord](https://discord.gg/8RwBGuf).

## Why are some roles missing from the role selector?

If there are some roles missing in the role selector on your dashboard, it means Invite Tracker's role is not set high enough in the role hierarchy.

To change this, head to your Server Settings -> Roles and drag the Invite Tracker role up above the roles you want to be able to select.
