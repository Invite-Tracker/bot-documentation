---
description: The explanation for the giveaway command for Invite Tracker.
---

# Giveaway

## Commands

<table><thead><tr><th width="342.3896176132662">Command</th><th>Description</th></tr></thead><tbody><tr><td><code>/giveaway create &#x3C;prize name> &#x3C;duration> &#x3C;winner amount> &#x3C;#channel></code></td><td>Creates a giveaway using the specified information</td></tr><tr><td><code>/giveaway delete &#x3C;message id></code></td><td>Deletes a specified giveaway</td></tr><tr><td><code>/giveaway end &#x3C;message id></code></td><td>Ends a specified giveaway</td></tr><tr><td><code>/giveaway list</code></td><td>Lists all of the server's currently active giveaways</td></tr><tr><td><code>/giveaway reroll &#x3C;message id></code></td><td>Chooses new winners for the specified giveaway</td></tr></tbody></table>

{% hint style="info" %}
<mark style="color:blue;">When ending a giveaway, Invite Tracker will choose winners.</mark>&#x20;

<mark style="color:blue;">When deleting a giveaway, Invite Tracker just permanently removes it without choosing any winners.</mark>
{% endhint %}

## Optional Arguments

### /giveaway create

<table><thead><tr><th width="313.095002016768">Argument</th><th>Description</th></tr></thead><tbody><tr><td><code>[messages_required: &#x3C;number>]</code></td><td>Requires members to have at least the specified amount of messages in order to be able to join the giveaway</td></tr><tr><td><code>[role_bonus_entries: &#x3C;@role> &#x3C;number>]</code></td><td>Assigns bonus entries to members with the specified roles</td></tr><tr><td><code>[roles_required: &#x3C;@role>]</code></td><td>Requires members to have all of the required roles in order to be able to join the giveaway</td></tr><tr><td><img src="../.gitbook/assets/image (95).png" alt="" data-size="line"> <code>[winner_roles: &#x3C;@role>]</code></td><td>Winner roles will be automatically assigned to the winners of the giveaway</td></tr></tbody></table>

{% hint style="info" %}
<mark style="color:blue;">You can configure multiple roles in arguments. Simply just add a new one after the first one.</mark>
{% endhint %}

### /giveaway reroll

| Argument                    | Description                                                              |
| --------------------------- | ------------------------------------------------------------------------ |
| `[winner_amount: <number>]` | Chooses the specified amount of new winners when re-rolling the giveaway |
