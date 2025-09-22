---
description: >-
  These plugins let you create highly customizable join, join DM and leave
  messages.
---

# 👋 Join, Join DM, and Leave Messages

## Useful Information

{% embed url="https://youtu.be/iUs6rr28tiY" %}
A tutorial video on how to SETUP the Invite Tracker bot!
{% endembed %}

### Main Message Types

Join, join DM, and leave messages are very similar. The only differences are the triggers and the different variables you can use to configure them.&#x20;

For our examples, we will be configuring a join message.

{% hint style="info" %}
<mark style="color:$info;">You can find an explanation of all the differences between the main message types</mark> [<mark style="color:$info;">here</mark>](types.md#main-message-types).
{% endhint %}

### Variables

Usually, you want the message to display information that changes its value depending on who just joined or who invited the person that just joined, for example. The way to add this type of varying information is by using variables.

{% hint style="info" %}
<mark style="color:$info;">You can find the complete list of variables</mark> [<mark style="color:$info;">here</mark>](variables.md)<mark style="color:blue;">.</mark>
{% endhint %}

## Configuration

### Enabled

First, you want to enable the plugin. Click the toggle to do so.

<figure><img src="../../../.gitbook/assets/JoinMessageEnable.png" alt=""><figcaption></figcaption></figure>

### Channel

Next, select the channel you want your message to be sent in.

<figure><img src="../../../.gitbook/assets/JoinMessageChannel.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
<mark style="color:$warning;">Configuring a channel does not apply to join DM messages.</mark>
{% endhint %}

### Emoji

You can also set Invite Tracker to react with an emoji reaction to every join/leave message by adding the  emoji directly or using the emoji code.

<figure><img src="../../../.gitbook/assets/JoinMessageEmoji.png" alt=""><figcaption></figcaption></figure>

To use a custom emoji, please send the following message in any Discord server: `\:emoji name:`, it will replace the message with something that looks like this: `<:invitetracker:744565894289555456>`. If you take that message and put it into the dashboard, Invite Tracker will display the emoji when sending a message.

### Configuring a Sub-Message Type

After you have chosen a channel, continue down to the **Messages** section of the page. You should see three boxes: one blue button, one small black box, and one large black text box. The first one is set to **Normal** by default, but you may change this if you are looking to edit another message type.

There is automatically a join/leave message set by default that can be used as shown below.

<figure><img src="../../../.gitbook/assets/JoinMessageConfig.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
&#x20;<mark style="color:$info;">A list explaining all the different sub-message types and their use can be found</mark> [<mark style="color:$info;">here</mark>](types.md#sub-message-types)<mark style="color:$info;">.</mark>
{% endhint %}

## The Message

### Creating the Message

When you have chosen the message type you want to configure, then you may pay attention to the large, black text box. This is where you write the message you want Invite Tracker to display when someone joins the server. The message may be anything you like.

{% hint style="info" %}
<mark style="color:$info;">If you'd like to customize your own message be sure to refer to the variables that can be found</mark> [<mark style="color:$info;">here</mark>](types.md#main-message-types)<mark style="color:blue;">.</mark>
{% endhint %}

### Testing the Message

After you have created your message, simply click the blue box named **Test message**. This will make Invite Tracker send a copy of the current message to either the configured join/leave channel or as a direct message to you, depending on what message type you have chosen.

<figure><img src="../../../.gitbook/assets/JoinMessagetestButton.png" alt=""><figcaption></figcaption></figure>

The message will appear as you configured it. This message is an example of the default message set, you can go as crazy as you want with your join message. Your mind is your only limit.

<figure><img src="../../../.gitbook/assets/JoinMessageTestDC.png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
<mark style="color:$danger;">If you test message does not appear, you need to ensure the bot has the</mark> [<mark style="color:$danger;">correct permissions</mark>](../../../faq.md#what-are-the-required-permissions-for-invite-tracker)<mark style="color:$danger;">.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:$warning;">Remember to turn on join messages after finishing configuring your message by clicking the upper-most switch.</mark>
{% endhint %}

## <img src="../../../.gitbook/assets/premium.png" alt="" data-size="line"> Embed

Embeds are a cool way to make _join_ and _leave messages_. Embeds bring a lot more customization to the table. You can configure anything from a 5-part story about a potato falling in love with a green rock, or you could configure the message to display all the variables, their function, and where to use them. Trust me, I have done it.

To enable and start configuring an embed, please click the switch right above the textbox at the right side of your screen labeled **Embed**.

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

After it has been enabled, you are prompted with a lot of text boxes. It might look like a lot, maybe even too much, but do not worry as everything will be explained.

<figure><img src="../../../.gitbook/assets/JoinMessageEmbed.png" alt=""><figcaption></figcaption></figure>

An overview of where everything is placed in the embed can be found below.

![](<../../../.gitbook/assets/image (52).png>)

Now that you have a general idea of how the embed looks and what goes where we can get to the explanation of every textbox.

#### Author

* **Author Icon URL** is where you can put either a picture link or an avatar variable. It will display the image as a small profile picture in the top left corner of the embed.
* **Author Name** is just a regular textbox where you can add whatever you want. Take to mind that bold, italic, strikethrough or code fields do not work here.
* **Author Name URL** is where you can put either a picture link or an avatar variable. It will create a hyperlink on the author name content.

#### Title

* **Title** is just a regular textbox where you can add whatever you want.
* **Title URL** is where you can put either a picture link or an avatar variable. It will create a hyperlink on the title content.

#### **Content**

* **Description** is just a regular textbox where you can add whatever you want.
* **Add Field** adds more title and description textboxes.

#### **Pictures**

* **Image URL** is where you can put either a picture link or an avatar variable. It will display the image as a large picture at the bottom of the embed.
* **Thumbnail URL** is where you can put either a picture link or an avatar variable. It will display the image as a medium-sized picture at the top right of the embed.

#### Footer

* **Footer Text** is just a regular textbox where you can add whatever you want. Take to mind that bold, italic, strikethrough or code fields do not work here.
* **Footer Icon URL** is where you can put either a picture link or an avatar variable. It will display the image as a small profile picture in the top left corner of the embed.

#### Extra

* **JSON Editor** allows you to copy/paste/edit the JSON of the embed.
* **Show current date and time** will show at what time the message was sent.
* **Random Color** will be a random embed color when the message is displayed.
* **Color Picker** will change the color of the embed line. Click the color bar to adjust.

Now, if we take everything we now know about embeds, we can make a simple embed message that looks like this:

<figure><img src="../../../.gitbook/assets/JoinMessageEmbedTest.png" alt=""><figcaption></figcaption></figure>

Now if we click the **Test message** button, we get this message:

<figure><img src="../../../.gitbook/assets/JoinMessageEmbedDC.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:$info;">There is really no right or wrong way to use all the embed boxes, just play around with it until you find something you like.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:$warning;">Pay attention to the small numbers under a few of the text boxes and buttons. They are the limits on how much can be fitted into that specific area.</mark>
{% endhint %}

{% hint style="warning" %}
<mark style="color:$warning;">You cannot use embeds for join DM messages.</mark>
{% endhint %}
