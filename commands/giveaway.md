---
description: The explanation for the giveaway command for Invite Tracker.
---

# Giveaway

{% embed url="https://youtu.be/JSxU-0oPmaE" %}
A tutorial video on how giveaways work and how to set them up.
{% endembed %}

## Commands

<table><thead><tr><th width="342.3896176132662">Command</th><th>Description</th></tr></thead><tbody><tr><td><code>/giveaway create &#x3C;prize name> &#x3C;duration> &#x3C;winner amount> &#x3C;#channel></code></td><td>Creates a giveaway using the specified information. See the tip below on how to format the duration.</td></tr><tr><td><code>/giveaway delete &#x3C;message id></code></td><td>Deletes a specified giveaway</td></tr><tr><td><code>/giveaway end &#x3C;message id></code></td><td>Ends a specified giveaway</td></tr><tr><td><code>/giveaway list</code></td><td>Lists all of the server's currently active giveaways and their message id's</td></tr><tr><td><code>/giveaway reroll &#x3C;message id></code></td><td>Chooses new winners for the specified giveaway</td></tr><tr><td><code>/giveaway scheduled</code> </td><td>Lists all of the server's scheduled giveaways</td></tr><tr><td><code>/giveaway templates</code> </td><td>Lists all of the server's giveaway templates</td></tr></tbody></table>

{% hint style="info" %}
<mark style="color:$info;">The format for giveaways is a number than the time variable. For example 5d = 5 days, 3d4h30m = 3 days, 4 hours, and 30 mins. The following variables are s = seconds, m = minutes, h = hours, and d = days.</mark>
{% endhint %}

{% hint style="info" %}
<mark style="color:$info;">When ending a giveaway, Invite Tracker will choose winners.</mark>&#x20;

<mark style="color:$info;">When deleting a giveaway, Invite Tracker just permanently removes it without choosing any winners.</mark>
{% endhint %}

## Optional Arguments

### /giveaway create

<table><thead><tr><th width="313.095002016768">Argument</th><th>Description</th></tr></thead><tbody><tr><td><code>[messages_required: &#x3C;number>]</code></td><td>Requires members to have at least the specified amount of messages in order to be able to join the giveaway</td></tr><tr><td><code>[role_bonus_entries: &#x3C;@role> &#x3C;number>]</code></td><td>Assigns bonus entries to members with the specified roles</td></tr><tr><td><code>[roles_required: &#x3C;@role>]</code></td><td>The roles required to enter the giveaway.</td></tr><tr><td><code>[roles_required_config: &#x3C;all|one of>]</code></td><td>Whether to require all roles or one of the roles selected in roles_required.</td></tr><tr><td><img src="../.gitbook/assets/image (97).png" alt="" data-size="line"> <code>[winner_roles: &#x3C;@role>]</code></td><td>Winner roles will be automatically assigned to the winners of the giveaway</td></tr></tbody></table>

{% hint style="info" %}
<mark style="color:$info;">You can configure multiple roles in arguments. Simply just add a new one after the first one.</mark>
{% endhint %}

### /giveaway reroll

| Argument                    | Description                                                              |
| --------------------------- | ------------------------------------------------------------------------ |
| `[winner_amount: <number>]` | Chooses the specified amount of new winners when re-rolling the giveaway |
