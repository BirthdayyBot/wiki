---
description: Get a quick overview over all commands Birthdayy has.
---

# Overview

**This page lists all usage and information about Birthdayy's commands.** \
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

`/birthday register <date> [user]`\
Register users' birthday with the bot, using the following format: `DD/MM/YYYY` or `DD/MM/XXXX.`

`/birthday update <user> <date>`\
Update users' birthday with the bot, using the following format: `DD/MM/YYYY` or `DD/MM/XXXX.`

`/birthday remove <user>`\
Remove users' birthday from the bot.

`/birthday list`\
List all the users' birthday in embed format.

`/birthday show [user]`\
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

`/config overview <channel>`\
To set the overview of the Birthdayy bot.

`/config announcement <channel>`\
To set an announcement channel for the bot

`/config ping-role <role>`\
Configure the ping/ mentioned role.

`/config birthday-role <role>`\
Configure the birthday role.

`/config timezone <zone>`\
Configure the timezone region for the bot.

{% content-ref url="config.md" %}
[config.md](config.md)
{% endcontent-ref %}
