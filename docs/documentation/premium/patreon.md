---
icon: lucide/banknote
description: Information on Color-Chan's Patreon integration for purchasing premium features
---

Color-Chan's [Patreon](https://www.patreon.com/c/BrammyS) page offers an alternative way to support the development of Color-Chan and gain access to premium features for your server. You will also gain access to Color-Chan's patreon only Discord channel. The main difference between [Patreon](https://www.patreon.com/c/BrammyS) and the [Discord Store](./discord-store.md) is that patreon premium subscriptions can be used on multiple servers depending on your chosen plan, while [Discord Store](./discord-store.md) subscriptions are tied to a single server.


## Tiers

Please visit Color-Chan's [Premium page](https://colorchan.com/premium) for the most up-to-date information on the available premium tiers and their features.


## Activating your subscription

The section below explains how to activate your Patreon premium benefits on your Discord server.

### Connecting your Discord account

First, you will need to connect your Discord account to your Patreon account. This can be done by going to your [Patreon settings](https://www.patreon.com/settings/apps) and linking your Discord account.
More information on how to do this can be found in Patreon's [official documentation](https://support.patreon.com/hc/en-us/articles/212052266-Getting-Discord-access).

### Claiming your premium benefits

To claim your premium benefits, use the `/patreon connect` command in the server where you want to activate premium. This command will check if your Patreon account has an active subscription and will activate the corresponding premium features for your server.

## Removing premium from a server

You can remove premium from a server by using the `/patreon disconnect` command. This will deactivate all premium features on the server. This will not cancel your Patreon subscription; it will only remove the premium features from that specific server. It will also lock any premium features that were in use on the server until premium is reactivated.

### Disconnecting from a lost server

Lost your server or can't access it anymore? You can disconnect your Patreon subscription from a server you no longer have access to by using the same command with the `id` parameter: `/patreon disconnect id:<server_id>`. Replace `<server_id>` with the ID of the server you want to disconnect from. You can find this ID with the `/patreon info` command, which will list all servers currently using your Patreon subscription.
