---
description: >-
  You can use variables when making a join, joinDM or Leave message. Variables
  are replaced with the correct information in join messages. Take to mind where
  all the different variables are usable.
---

# Variables

### All Variables and Their Explanation

| Variable                  | Description                                                                                                                                                                | Where to use               |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| %member%                  | Member's display name if applicable. Otherwise defaults to Username#Discriminator                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_name%            | Member's username                                                                                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_discriminator%   | Member's discriminator                                                                                                                                                     | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_mention%         | Mention the member                                                                                                                                                         | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_id%              | Member's Discord ID                                                                                                                                                        | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_avatar%          | Member's Discord profile picture                                                                                                                                           | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_created%         | When the member made their account                                                                                                                                         | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_created\_ago%    | How long ago the member made their account                                                                                                                                 | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_joined%          | When the member joined the server                                                                                                                                          | `LEAVE`                    |
| %member\_joined\_ago%     | How long ago the member joined the server                                                                                                                                  | `LEAVE`                    |
| %member\_join\_count%     | How many times the member joined the server                                                                                                                                | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_leave\_count%    | How many times the member left the server                                                                                                                                  | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter%                 | Inviter's display name if applicable. Otherwise defaults to Username#Discriminator                                                                                         | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_name%           | Inviter's username                                                                                                                                                         | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_discriminator%  | Inviter's discriminator                                                                                                                                                    | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_mention%        | Inviter's mention                                                                                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_id%             | Inviter's Discord ID                                                                                                                                                       | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_avatar%         | Inviter's Discord profile picture                                                                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_invites%        | Inviter's number of total invites                                                                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_reg\_invites%   | Inviter's number of regular invites                                                                                                                                        | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_leave\_invites% | Inviter's number of leave invites                                                                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_fake\_invites%  | Inviter's number of fake invites                                                                                                                                           | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_bonus\_invites% | Inviter's number of bonus invites                                                                                                                                          | `JOIN`, `LEAVE`, `JOIN DM` |
| %guild\_name%             | Server's name                                                                                                                                                              | `JOIN`, `LEAVE`, `JOIN DM` |
| %guild\_avatar%           | Server's icon                                                                                                                                                              | `JOIN`, `LEAVE`, `JOIN DM` |
| %guild\_count%            | Number of members in the server                                                                                                                                            | `JOIN`, `LEAVE`, `JOIN DM` |
| %invite\_code%            | The invite code the user used                                                                                                                                              | `JOIN`                     |
| %invite\_uses%            | The number of uses the invite code has                                                                                                                                     | `JOIN`                     |
| %invite\_url%             | The invite url                                                                                                                                                             | `JOIN`                     |
| %invite\_label%           | <p>The invite label. Otherwise, defaults to the invite code.<br><br>What are Invite Labels? Click <a href="../invite-tracking.md#invite-label">here</a> for more info.</p> | `JOIN`, `LEAVE`, `JOIN DM` |
| %random\_color%           | Random color for embeds                                                                                                                                                    | `JOIN`, `LEAVE`            |

