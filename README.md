# AutoDrip - Minecraft Chat Logger Mod

A Fabric mod for Minecraft 1.21.4 that logs chat messages with player nicknames and server names, sending them to Discord via webhook.

## Features

- ✅ Logs all chat messages from the server
- ✅ Captures player nicknames
- ✅ Records server name
- ✅ Sends messages to Discord webhook
- ✅ Asynchronous message sending (doesn't lag the game)
- ✅ Easy configuration via JSON file

## Installation

1. Download the mod JAR file from releases
2. Place it in your `mods` folder
3. Launch Minecraft with Fabric loader
4. First launch will create a config file at `config/autodrip/config.json`

## Configuration

Edit `config/autodrip/config.json`:

```json
{
  "webhookUrl": "https://discord.com/api/webhooks/YOUR_WEBHOOK_URL",
  "enabled": true
}
```

## Building

```bash
./gradlew build
```

The built JAR will be in `build/libs/`

## License

MIT License
