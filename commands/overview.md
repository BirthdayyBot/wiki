---
description: Get a quick overview over all commands Birthdayy has.
---

# Overview

**This page lists all usage and information about Birthdayy's commands.**\
**For more information**, **visit the corresponding help page**

{% hint style="info" %}
How to Read these Docs

* Arguments in **`< >`** are _mandatory_.
* Arguments in **`[ ]`** are _optional_.
{% endhint %}

> Prefix: /

## General

All general commands of Birthdayy.

`/guide`\
A simple guide to guide you on how to set up the bot.

`/help [commands]`\
Need help with commands? (subcommands are not supported, at the moment)

`/status`\
Show the status of the bot commands.

`/vote`\
Vote for Birthdayy!

`/invite`\
Invite the bot!

`/support`\
Join the support server!

`/feedback`\
Want to review Birthdayy? Feel free to leave some feedback!

`/suggestion <suggestion>`\
Have a suggestion for the bot, let us know!

`/bugreport <bug>`\
File a bug report to the server developer.

{% content-ref url="general.md" %}
[general.md](general.md)
{% endcontent-ref %}

## Birthday

All subcommands of the `/birthday` command.

``[`/birthday register <day> <month> [year] [user]`](../guides/birthday-commands/register-your-birthday.md)\
Register users' birthday with the bot.

``[`/birthday update <user> <day> <month> [year]`](../guides/birthday-commands/update-birthdays.md) `` \
Update users' birthday with the bot.

``[`/birthday remove <user>`](../guides/birthday-commands/remove-birthdays.md)\
Remove users' birthday from the bot.

`/birthday list`\
List all the users' birthday in embed format.

``[`/birthday show [user]`](../guides/birthday-commands/showing-someones-birthday.md)\
Show the user's birthday.

{% content-ref url="birthday.md" %}
[birthday.md](birthday.md)
{% endcontent-ref %}

## Birthdayy Configuration (**for server manager only**)

All subcommands of the `/config` command.

`/config status`\
To show the overall configuration of the bot.

`/config logs <channel>`\
To set the logs channel for the bot.

``[`/config overview <channel>`](../guides/set-up-an-overview-channel.md)\
To set the overview of the Birthdayy bot.

``[`/config announcement <channel>`](../guides/config-commands-guides/set-up-announcement-channel.md)\
To set an announcement channel for the bot

``[`/config ping-role <role>`](../guides/config-commands-guides/set-up-a-ping-role.md)\
Configure the ping/ mentioned role.

``[`/config birthday-role <role>`](../guides/config-commands-guides/set-up-a-birthday-role.md)\
Configure the birthday role.

``[`/config timezone <zone>`](../guides/config-commands-guides/change-up-the-server-timezone.md)\
Configure the timezone region for the bot.

`/config announcement-message <message>`\
``Change the default Birthday announcement message. (Birthdayy Premium requred).\
Available Variables: _**{MENTION}**_, _**{USERNAME}**_, _**{DISCRIMINATOR}**_, _**{LINE\_BREAK}**_, _**{SERVERNAME}**_
