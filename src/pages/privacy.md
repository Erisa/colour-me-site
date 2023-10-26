---
layout: '../layouts/Layout.astro'
title: 'Colour Me! Privacy Policy'
---

# Colour Me! Privacy Policy

The use of this application ("Bot", "Colour Me!") in a server requires the collection of some specific data ("Data"). The Data collected includes IDs of the Discord roles added to the Bot using commands. Use of the Bot is considered an agreement to the terms of this Policy.

The Data stored is stored as Discord ID numbers in a Key/Value store. The following is an example of the data stored.

Example key: `438781053675634713`, this is a Discord server ID

Example value:
```json
["741380339296895008","491366256847618069","438781500209758218","491366346987274240","956705196354969670","491366427463254035","438781385793208330"]
```
The above is a list of role IDs which are enabled for use with the Bot.

## Access to Data

Access to Data is only permitted to Bot's developers, and only in the scope required for the development, testing, and implementation of features for Bot. Data is not sold, provided to, or shared with any third party, except where required by law or a Terms of Service agreement.

## Storage of Data

Data is stored in [Cloudflare Workers KV](https://developers.cloudflare.com/kv/learning/how-kv-works/). The Data is secured to prevent external access except through the use of the Bot, however no guarantee is provided and the Bot owners assume no liability for the unintentional or malicious breach of Data to the extent applicable by law. In the event of an unauthorised Data access, users will be notified through the Discord client application.

## User Rights

At any time, you may view the data stored for a server by using the `/colour-role list` command on the server. Users with the `Manage Roles` permission on the server may remove any role IDs using the `/colour-role remove` command.

Exact command names may vary based on your language settings.

## Underage Users

The use of the Bot is not permitted for minors under the age of 13, or under the age of legal consent for their country. This is in compliance with the [Discord Terms of Service](https://discord.com/terms). No information will be knowingly stored from an underage user. If it is found out that a user is underage we will take all necessary action to delete the stored data.

## Questions

If you have any questions or requests, please [contact Erisa](https://erisa.uk/contact).

For more information check the [Discord Terms Of Service](https://discord.com/terms).

---

[Return home](/)