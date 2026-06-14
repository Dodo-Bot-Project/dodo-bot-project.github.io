---
title: Canary
description: A page about Canary and how to use them.
---

## What is Canary?
Canary is the unstable branch for developing upcoming versions of Dodo-Bot before they're eventually released as a stable version.

Builds released from this branch are incomplete and may have bugs as a result, so it is not recommended to use them for normal usage.

While regular releases have a random codename as they progress from being pre-release to Stable, Canary will always be Canary. It will always use the codename Canary regardless of how many versions have been released and it will always be constantly moving compared to a non-Canary release.

## Using Canary
The installation steps are pretty much the same as in the [Installation](/getting-started/install) page but you may need to slightly change the way the source code is obtained.

### Git
This is the recommended method for installing the Canary version of Dodo-Bot as it allows updating to the latest changes using `git pull`.

Simply run this in the terminal:
```
git clone -b canary https://github.com/ddodogames/Dodo-Bot "Dodo-Bot Canary"
```

For the rest of the install steps, Follow the [Setting up the bot](/getting-started/install#setting-up-the-bot) section from the [Installation](/getting-started/install) page.

### Manually (not recommended)
[Open the Canary branch](https://github.com/ddodogames/Dodo-Bot/tree/canary) on GitHub and press "Download ZIP" through the "Code" button, extract it somewhere and you're good to go.


### Without installing
Simply invite the [official Canary bot](https://discord.com/api/oauth2/authorize?client_id=970481494797738016&scope=bot+applications.commands&permissions=36032) into your server and start using the bot using the prefix `d?`.

The only downside of this is if you're paranoid since in this case, you will most likely install the bot using the source code instead.


