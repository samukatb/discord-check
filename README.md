# DiscordCheck - Discord 2FA Login System for Minecraft Servers


## Overview

DiscordCheck is a powerful and user-friendly plugin designed to enhance the security of your Minecraft server through seamless integration with Discord as a Two-Factor Authentication (2FA). Safeguard player accounts against unauthorized access, providing administrators and players alike with peace of mind.

## Features

- **Discord Integration:** Link Minecraft accounts with Discord for unified authentication.
- **Two-Factor Authentication (2FA):** Implement an extra layer of security for player accounts.
- **Effortless Setup:** Easy installation and configuration for quick implementation.
- **Customizable Verification Codes:** Personalize the 2FA experience with customizable messages.
- **Automatic Account Protection:** Active defense against potential threats upon login.
- **Bukkit and Spigot Compatibility:** Works seamlessly with popular server platforms.

## Getting Started

### Prerequisites

- Minecraft server running Bukkit or Spigot.

### Installation

1. Download the DiscordCheck JAR file from the [releases page](https://github.com/samukatb/discord-check/releases).
2. Place the JAR file in the `plugins` folder of your Minecraft server.
3. Start the server to create configuration files
4. Stop the server and configure the plugin in the `config.yml` file.
5. Start the server.

### Configuration

Edit the `config.yml` and `messages.yml`` file to customize settings such as Discord bot token and messages options.

```yaml
discord:
  bot-token: 'your bot token'
```

### Acknowledgments

- Special thanks to [Discord JDA](https://github.com/discord-jda/JDA) for Discord API support.
