---
description: >-
  Custom Bot's let you run an instance of Invite Tracker on your own
  application.
---

# 🤖 Custom Bot

{% hint style="warning" %}
This feature requires the **Custom Bot** tier of Invite Tracker Premium. You can purchase it [here](https://invite-tracker.com/premium) and read about all the perks.
{% endhint %}

If you have the applicable subscription already, let's get started with making an application for Invite Tracker on. You may [skip](custom-bot.md#embed-color) this part if you already know what you're doing.

## Creating an Application

Let's start by heading over to the [Discord Developer Portal](https://discord.com/developers/applications). Make sure you're logged into the desired account and click the button "New Application" at the top right of the page, beside your avatar.

<figure><img src="../../.gitbook/assets/devappi1.png" alt=""><figcaption></figcaption></figure>

Choose a name for your new application and agree to the terms and conditions. After, click "Create".\


<figure><img src="../../.gitbook/assets/devappi2.png" alt=""><figcaption></figcaption></figure>

Head to the Bot tab on the left. From there, disable the "Public Bot" option and enable the "Server Members Intent" option.

<figure><img src="../../.gitbook/assets/app_perms.gif" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
The custom bot will not work without the "Server Members Intent".
{% endhint %}

To invite the custom bot to your server, head to the OAuth2 tab on the left. Select "bot" in OAuth2 URL Generator and "Administrator" in Bot Permissions. You will then be able to use the Generated URL to invite your custom bot to the server.

<figure><img src="../../.gitbook/assets/app_invite.gif" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
For this tutorial, administrator allows the custom bot to function as efficiently as possible. You may still choose to use the default Invite Tracker permissions. Click [here](../../faq.md#what-are-the-required-permissions-for-invite-tracker) to see them.
{% endhint %}

After inviting your custom bot, we need to activate it. Head to the Bot tab on the left and copy your token. On the server with the Custom bot tier, you will see a new plugin called **Custom Bot**, then paste the copied token into **Bot Token** and save changes.

<figure><img src="../../.gitbook/assets/app_token.gif" alt=""><figcaption></figcaption></figure>

## Embed Color

Customize the embed color sent by the custom bot with the color picker.

<figure><img src="../../.gitbook/assets/CB_embedcolor.png" alt=""><figcaption></figcaption></figure>

## Status & Activity

You will be able to customize the custom bot's status and activity status as well.

There are 4 statuses you can choose from:

* Online
* Invisible
* Idle
* Do Not Disturb

<figure><img src="../../.gitbook/assets/CB_status.png" alt=""><figcaption></figcaption></figure>

There are a variety of activity types you may choose from along with being able to customize the text that displays after the type.

<figure><img src="../../.gitbook/assets/CB_activity.png" alt=""><figcaption></figcaption></figure>
