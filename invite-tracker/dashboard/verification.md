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

<div align="center" data-full-width="false">

<img src="../../.gitbook/assets/Verification Level.png" alt="">

</div>

{% hint style="info" %}
<mark style="color:blue;">Selecting the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Button**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">option will cause a new, blue bar to appear. Clicking this will cause Invite Tracker to attempt to send a verification button to your server's</mark> [_<mark style="color:purple;">verification channel</mark>_](verification.md#verification-channel)<mark style="color:blue;">.</mark> <mark style="color:blue;"></mark><mark style="color:blue;">If Invite Tracker fails, please grant it the required permissions for that channel.</mark>
{% endhint %}

{% hint style="success" %}
<mark style="color:green;">We recommend using the</mark> <mark style="color:green;"></mark><mark style="color:green;">**Website**</mark> <mark style="color:green;"></mark><mark style="color:green;">option for this feature as it is the most secure way of protecting your server against bot accounts and raids.</mark>
{% endhint %}

## Verification Timeout

The _verification timeout_ of your server is the number of seconds that need to pass before an unverified user is automatically kicked/banned from the server.

![](<../../.gitbook/assets/Verification Timeout.png>)

{% hint style="success" %}
<mark style="color:green;">Users need time to verify, so remember to set the</mark> <mark style="color:green;"></mark>_<mark style="color:green;">verification timeout</mark>_ <mark style="color:green;"></mark><mark style="color:green;">accordingly. The default</mark> <mark style="color:green;"></mark>_<mark style="color:green;">verification timeout</mark>_ <mark style="color:green;"></mark><mark style="color:green;">of 180 seconds should be sufficient for most cases.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:orange;">A server's</mark> <mark style="color:orange;"></mark>_<mark style="color:orange;">verification timeout</mark>_ <mark style="color:orange;"></mark><mark style="color:orange;">must be between 15 and 900 seconds.</mark>
{% endhint %}

## Verification Action

This feature decides the effect of the [_<mark style="color:purple;">verification timeout</mark>_](verification.md#verification-timeout) feature.

There are two _verification actions_:

* **Kick**: If a user does not verify within the _verification timeout_, they will be kicked from the server.
* **Ban**: If a user does not verify within the _verification timeout_, they will be banned from the server.

![](<../../.gitbook/assets/Verification Action.png>)

{% hint style="info" %}
<mark style="color:blue;">Every server's default</mark> <mark style="color:blue;"></mark>_<mark style="color:blue;">verification action</mark>_ <mark style="color:blue;"></mark><mark style="color:blue;">is set to kick.</mark>
{% endhint %}

{% hint style="danger" %}
<mark style="color:red;">Be careful when using the</mark> <mark style="color:red;"></mark><mark style="color:red;">**Ban**</mark> <mark style="color:red;"></mark><mark style="color:red;">option for this feature. It is generally not recommended to use it.</mark>
{% endhint %}

## Verification Role

The _verification role_ of your server is the role that is granted to the user after they complete the verification. [_<mark style="color:purple;">Auto roles</mark>_](administration.md#auto-roles) are added to a user alongside _verification roles_.

![](<../../.gitbook/assets/Verification Role.png>)

## Verification Channel

The _verification channel_ of your server is the channel where the verification message will be sent if the new member has their DMs closed.

![](<../../.gitbook/assets/Verification Channel (1).png>)

{% hint style="warning" %}
<mark style="color:orange;">Remember to give Invite Tracker enough permissions so it can post verification messages.</mark>
{% endhint %}

## Verification Logs

_Verification_ _logs_ are messages sent by Invite Tracker to a specific channel that notify you whether new members managed to verify, fail the verification, or did not verify within the _verification timeout_.

![](<../../.gitbook/assets/Verification Logs.png>)

## Verification Logs Channel

The _verification logs channel_ of your server is where your server's _verification logs_ are sent.

{% hint style="warning" %}
<mark style="color:orange;">You need to enable the</mark> [_<mark style="color:purple;">verification logs</mark>_](verification.md#verification-logs) <mark style="color:orange;">switch for this feature to work.</mark>
{% endhint %}

