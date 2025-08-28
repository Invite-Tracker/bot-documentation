---
description: >-
  The explanation for all the administration commands available for Invite
  Tracker.
---

# Administration

## Invite Administration

| Command                | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| `/deleteinvite <code>` | Deletes the specified invite code                                  |
| `/syncinvites [@user]` | Synchronizes the server's invites with everyone or a specific user |

{% hint style="danger" %}
/syncinvites adds the uses of active invites in your server to the invite count of the bot. You should only run this once (such as when adding the bot to your server), otherwise you will double the invites if run again.
{% endhint %}

## Server Settings

| Command                                                                | Description                                                                                                                                                                                                                     |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🌟`/massban <@user\|invite_code>`                                      | Allows you to ban everyone invited by a specific user or you can choose to mass ban everyone invited by a specific invite code.                                                                                                 |
| 🌟`/exportleaderboard <leaderboard_type>`                              | Allows you to export the invites or messages leaderboard type. This gives you raw data that can be downloaded from a .csv file format.                                                                                          |
| 🌟`/exportinvitedlist <@user\|invite_code\|invite_label\|filter_role>` | <p>Allows you to export a list of the specified type to a downloadable .csv file format.<br><br>What are Invite Labels? Click <a href="../invite-tracker/dashboard/invite-tracking.md#invite-label">here</a> for more info.</p> |

