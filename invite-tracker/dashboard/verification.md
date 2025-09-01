---
description: >-
  The verification plugin affects new members of your server by requiring them
  to go through a security check before they can have access to the server.
---

# 🔒 Verification

## Verification Level

The _verification level_ of your server is the type of verification in your server. It gradually gets more secure for each level.

There are 4 verification levels:

* **Disabled**: The verification plugin of your server is turned off and will not function.
* **Button**: Requires new members to click a button created by Invite Tracker to get their verification role.
* **Captcha**: Requires new members to solve a captcha sent by Invite Tracker to get their verification role.
* **Website**: Requires new members to solve a captcha on our website. This offers the best protection against bots and raids.

<div align="center" data-full-width="false"><img src="../../.gitbook/assets/Verification Level.png" alt=""></div>

{% hint style="info" %}
<mark style="color:$info;">Selecting the</mark> <mark style="color:$info;"></mark><mark style="color:$info;">**Button**</mark> <mark style="color:$info;"></mark><mark style="color:$info;">option will cause a new, blue bar to appear. Clicking this will cause Invite Tracker to attempt to send a verification button to your server's</mark> [_<mark style="color:$info;">verification channel</mark>_](verification.md#verification-channel)<mark style="color:$info;">.</mark> <mark style="color:$info;">If Invite Tracker fails, please grant it the required permissions for that channel.</mark>
{% endhint %}

{% hint style="success" %}
<mark style="color:$success;">We recommend using the</mark> <mark style="color:$success;"></mark><mark style="color:$success;">**Website**</mark> <mark style="color:$success;"></mark><mark style="color:$success;">option for this feature as it is the most secure way of protecting your server against bot accounts and raids.</mark>
{% endhint %}

## Verification Timeout

The _verification timeout_ of your server is the number of seconds that need to pass before an unverified user is automatically kicked/banned from the server.

![](<../../.gitbook/assets/Verification Timeout.png>)

{% hint style="success" %}
<mark style="color:$success;">Users need time to verify, so remember to set the</mark> <mark style="color:$success;"></mark>_<mark style="color:$success;">verification timeout</mark>_ <mark style="color:$success;"></mark><mark style="color:$success;">accordingly. The default</mark> <mark style="color:$success;"></mark>_<mark style="color:$success;">verification timeout</mark>_ <mark style="color:$success;"></mark><mark style="color:$success;">of 180 seconds should be sufficient for most cases.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:$warning;">A server's</mark> <mark style="color:$warning;"></mark>_<mark style="color:$warning;">verification timeout</mark>_ <mark style="color:$warning;"></mark><mark style="color:$warning;">must be between 15 and 1800 seconds.</mark>
{% endhint %}

## Verification Action

This feature decides the effect of the [_verification timeout_](verification.md#verification-timeout) feature.

There are two _verification actions_:

* **Kick**: If a user does not verify within the _verification timeout_, they will be kicked from the server.
* **Ban**: If a user does not verify within the _verification timeout_, they will be banned from the server.

![](<../../.gitbook/assets/Verification Action.png>)

{% hint style="info" %}
<mark style="color:$info;">Every server's default</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">verification action</mark>_ <mark style="color:$info;"></mark><mark style="color:$info;">is set to kick.</mark>
{% endhint %}

{% hint style="danger" %}
<mark style="color:$danger;">Be careful when using the</mark> <mark style="color:$danger;"></mark><mark style="color:$danger;">**Ban**</mark> <mark style="color:$danger;"></mark><mark style="color:$danger;">option for this feature. It is generally not recommended to use it.</mark>
{% endhint %}

## Verification Role

The _verification role_ of your server is the role that is granted to the user after they complete the verification. [_Auto roles_](administration.md#auto-roles) are added to a user alongside _verification roles_.

![](<../../.gitbook/assets/Verification Role.png>)

{% hint style="warning" %}
<mark style="color:$warning;">When configuring the Verification Role in your server, make sure the Invite Tracker bot role is above the role you want to give.</mark>
{% endhint %}

## Verification Channel

The _verification channel_ of your server is the channel where the verification message will be sent if the new member has their DMs closed.

![](<../../.gitbook/assets/Verification Channel (1).png>)

{% hint style="warning" %}
<mark style="color:$warning;">Remember to give Invite Tracker enough permissions so it can post verification messages.</mark>
{% endhint %}

## <img src="../../.gitbook/assets/premium.png" alt="" data-size="line"> Verification Custom Embed

_Verification Custom Embed_ allows you to customize the embed for the button [verification level](verification.md#verification-level) option.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Once enabled, you can customize what the embed looks like. The new embed is sent out when you click on the _Send Verification Panel_ button.

## Verification Logs

_Verification_ _logs_ are messages sent by Invite Tracker to a specific channel that notify you whether new members managed to verify, failed the verification, or did not verify within the _verification timeout_.

![](<../../.gitbook/assets/Verification Logs.png>)

## Verification Logs Channel

The _verification logs channel_ of your server is where your server's _verification logs_ are sent.

{% hint style="warning" %}
<mark style="color:$warning;">You need to enable the</mark> [_verification logs_](verification.md#verification-logs) <mark style="color:$warning;">switch for this feature to work.</mark>
{% endhint %}

