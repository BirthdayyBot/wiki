# Commands
###### This page lists all usage and information about BirthdayyBot's commands.

{% hint style="info" %}
How to Read these Docs

* Arguments in **`< >`** are _mandatory_.
* Arguments in **`[ ]`** are _optional_.

{% endhint %}

Prefix: `/`
Example Command Usage: `/birthday list`

## General

`/bugreport <bug>` - File a bug report to the server developer.
`/feedback` - Want to review Birthdayy? Feel free to leave some feedback!
`/guide` - A simple guide to guide you on how to set-up the bot
`/help [commands]` - Need help with commands? (subcommands are not supported, at the moment)
`/invite` - Invite the bot!
`/status` - Show the status of the bot
`/suggestion <suggestion>` - Have a suggestion for the bot, let us know!
`/support` - To join the support server!
`/vote` - Vote us!

## Birthdayy General
`/birthday register <date> [user]` - Register users' birthday with the bot, using the following format: `DD/MM/YYYY` or `DD/MM/XXXX`
`/birthday update <user> <date>` - Update users' birthday with the bot, using the following format: `DD/MM/YYYY` or `DD/MM/XXXX`
`/birthday remove <user>` - Remove users' birthday from the bot.
`/birthday list` - List all the users' birthday in embed format.
`/birthday show [user]` - Show the user's birthday.

## Birthdayy Configuration (**for server administrator only**)
`/config status` - To show the overall configuration of the bot.
`/config logs <channel>` - To set the logs channel for the bot.
`/config overview <channel>` - To set the overview of the birthdayy bot.
`/config announcement <channel>` - To set an announcement channel for the bot
`/config ping-role <role>` - Configure the ping/ mentioned role.
`/config birthday-role <role>` - Configure the birthday role.
`/config timezone <zone>` - Configure the timezone region for the bot.
