---
description: >-
  The message counting plugin can decide where messages can be counted, how
  often they can be counted, and even assign roles to users who send enough
  messages.
---

# 💬 Message Counting

## Message Count Delay

The _message count delay_ of your server is the number of seconds that need to pass between each counted message before Invite Tracker counts another message.

For example, if a user sends a message which Invite Tracker counts and the _message count delay_ in that server is 10 seconds, Invite Tracker will not count any other messages sent by that same user before 10 seconds have passed. This is to stop people from spamming messages to be at the top of the message count leaderboard.

![](<../../.gitbook/assets/Mcount Delay.png>)

{% hint style="info" %}
<mark style="color:blue;">Every server's default</mark> _<mark style="color:blue;">message count delay</mark>_ <mark style="color:blue;">is 0 seconds.</mark>
{% endhint %}

{% hint style="success" %}
<mark style="color:green;">A good</mark> _<mark style="color:green;">message count delay</mark>_ <mark style="color:green;">is 10 seconds.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:orange;">A server's</mark> _<mark style="color:orange;">message count delay</mark>_ <mark style="color:orange;">must be between 0 and 300 seconds.</mark>
{% endhint %}

## Messages Channel Blacklist

This is where you can blacklist a channel from having messages counted. Messages sent by users in a blacklisted channel will not be counted towards their total amount of messages sent.

![](<../../.gitbook/assets/Mchannel Blacklist.png>)

{% hint style="success" %}
<mark style="color:green;">A good idea would be to blacklist any bot-designated channels. This is because usually, you do not want people to gain messages for spamming lots of commands.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:orange;">Free servers can only have a maximum of 5 blacklisted channels.</mark>

<mark style="color:orange;">Premium servers can have an unlimited amount blacklisted channels.</mark>
{% endhint %}

## Role Messages Blacklist

This is where you can blacklist roles from having messages counted. Messages sent by users with a message-blacklisted role will not count towards their total amount of messages sent.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">Free servers can only have a maximum of 3 blacklisted roles.</mark>

<mark style="color:orange;">Premium servers can have an unlimited amount of blacklisted roles.</mark>
{% endhint %}

## User Messages Blacklist

This is where you can blacklist members from having their messages counted by using their user IDs. Messages sent by message-blacklisted users are not tracked by Invite Tracker and will not count towards their total amount of messages sent.

![](<../../.gitbook/assets/Umessage Blacklist.png>)

{% hint style="info" %}
<mark style="color:blue;">Information regarding how to get a user's ID can be found</mark> [<mark style="color:purple;">here</mark>](../../information.md#copying-a-user-id)<mark style="color:blue;">.</mark>
{% endhint %}

{% hint style="danger" %}
<mark style="color:red;">Be careful not to blacklist the wrong users.</mark>
{% endhint %}

## Highest Mode

This switch decides the effect of the [_<mark style="color:purple;">reward roles</mark>_](message-counting.md#reward-rolesto-assign-a-role-as-a-reward-role-simply-select-it-from-the-list-and-then-choose-the-num) feature for the message counting plugin.

_The Highest Mode_ decides whether users keep all of the reward roles they have managed to acquire or only the role that requires the most amount of messages. To keep the highest role, enable the Highest Mode setting. To keep all the roles added keep the Highest Mode setting disabled.

<div align="center"><img src="../../.gitbook/assets/Highest Mode.png" alt=""></div>

## Reward Roles

A _reward role_ is a role that is assigned to a user when they have sent a certain amount of messages.

![](<../../.gitbook/assets/Reward Roles.png>)

{% hint style="warning" %}
<mark style="color:orange;">Free servers can only have a maximum of 5</mark> _<mark style="color:orange;">reward roles</mark>_<mark style="color:orange;">.</mark>

<mark style="color:orange;">Premium servers can have an unlimited amount of</mark> _<mark style="color:orange;">reward roles</mark>_<mark style="color:orange;">.</mark>
{% endhint %}
