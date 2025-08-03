# Chamber Bot - User Guide

[![Discord.js](https://img.shields.io/badge/Discord.js-14.14.1-blue.svg?style=flat-square&logo=discord)](https://discord.js.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.0.0+-green.svg?style=flat-square&logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-orange.svg?style=flat-square&logo=mongodb)](https://mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

Welcome to Chamber! This guide will help you understand how to use Chamber's voice channel features in your Discord server.

## What is Chamber?

Chamber is a powerful Discord bot that creates a dynamic voice channel experience. When you join a special "Join to Create" channel, Chamber automatically creates a temporary voice channel just for you and your friends. You have full control over this channel - you can rename it, lock it, invite people, and much more!

## Getting Started

### How to Create Your Own Voice Channel

1. **Find the Join to Create Channel**: Look for a voice channel in your server that says something like "➕ Join to Create" or "🎤 Create Channel"
2. **Join the Channel**: Simply click on it to join
3. **Your Channel is Created**: Chamber will automatically create a new voice channel with your name
4. **Start Talking**: You're now the owner of your own voice channel!

## Voice Channel Commands

Once you're in your voice channel, you can use these commands to manage it:

### Basic Commands (Available to Everyone)

**`/voice name <name>`**
- Rename your voice channel to any name you want
- Example: `/voice name Gaming Room`

**`/voice limit <number>`**
- Set how many people can join your channel (0-99)
- Example: `/voice limit 5` (only 5 people can join)

**`/voice lock`**
- Lock your channel so no one else can join
- Only you can unlock it later

**`/voice unlock`**
- Unlock your channel so others can join again

**`/voice permit @user`**
- Allow a specific person to join your channel even if it's locked
- Example: `/voice permit @friend`

**`/voice reject @user`**
- Kick someone out of your channel and prevent them from rejoining
- Example: `/voice reject @troublemaker`

**`/voice claim`**
- If you're in a channel where the owner left, you can claim ownership
- This gives you control of the channel

### Premium Commands (Require Premium Subscription)

**`/voice text`**
- Create a temporary text channel that's linked to your voice channel
- Perfect for sharing links or having text discussions while voice chatting

**`/voice game`**
- Automatically rename your channel to show what game you're currently playing
- Example: If you're playing Minecraft, your channel becomes "Playing Minecraft"

**`/voice ghost`**
- Hide your voice channel from the channel list
- Only people you invite can find and join it

**`/voice unghost`**
- Make your hidden channel visible again

**`/voice invite @user <message>`**
- Send a direct invite to someone with a custom message
- Example: `/voice invite @friend Join our gaming session!`

**`/voice nsfw`**
- Toggle NSFW mode for your channel
- Useful for adult content discussions

**`/voice bitrate <kbps>`**
- Set custom audio quality for your channel
- Higher bitrate = better audio quality

**`/voice permit-role @role`**
- Allow an entire role to join your channel
- Example: `/voice permit-role @Moderators`

**`/voice reject-role @role`**
- Prevent an entire role from joining your channel

## General Commands

**`/help`**
- Shows all available commands and features
- Use the dropdown menu to explore different categories

**`/ping`**
- Check if the bot is responding quickly
- Shows bot latency

**`/uptime`**
- See how long the bot has been running

**`/invite`**
- Get a link to invite Chamber to another server

## Premium Features

Chamber offers a premium subscription that unlocks advanced features:

### What You Get with Premium:
- **Text Channel Creation**: Create temporary text channels for your voice channels
- **Game Detection**: Automatic channel renaming based on your current game
- **Ghost Mode**: Hide your channels from the public
- **Direct Invites**: Send personalized invites to users
- **NSFW Toggle**: Control adult content settings
- **Custom Bitrate**: Set higher audio quality
- **Role Permissions**: Control access by entire roles
- **Premium Support**: Priority help when you need it

### How to Get Premium:
1. Contact the bot owner or server administrator
2. They can grant you premium access
3. Use `/subscription activate` to activate it on your server
4. Use `/subscription status` to check your premium status

## Tips and Best Practices

### Channel Management
- **Be Respectful**: Don't abuse the lock/unlock feature to exclude people unfairly
- **Use Descriptive Names**: Name your channels clearly so people know what's happening
- **Clean Up**: When you're done, leave your channel - it will automatically delete

### Privacy and Safety
- **Ghost Mode**: Use this for private conversations
- **Permit/Reject**: Control who can join your channels
- **NSFW Content**: Use the NSFW toggle for adult discussions

### Getting Help
- **Use `/help`**: Always start here if you're confused
- **Ask Moderators**: Server moderators can help with bot issues
- **Check Permissions**: Make sure you have the right permissions to use commands

## Troubleshooting

### Common Issues:

**"I can't use voice commands!"**
- Make sure you're in a voice channel that you own
- Check if you have the right permissions
- Try leaving and rejoining the channel

**"My channel disappeared!"**
- Channels automatically delete when everyone leaves
- If you want to keep it, make sure someone stays in it

**"I can't rename my channel!"**
- Make sure you're the owner of the channel
- Check if the server has premium features enabled
- Try the command again

**"The bot isn't responding!"**
- Use `/ping` to check if the bot is online
- Ask a moderator to check the bot status

## Server Setup (For Administrators)

If you're a server administrator, you can set up Chamber with different channel creation systems:

### Setup Types:
- **Default**: Simple channels with user names
- **Clone**: Exact copies of the join channel
- **Sequence**: Numbered channels (Gaming 1, Gaming 2, etc.)
- **Predefined**: Custom templates with variables

### Admin Commands:
- `/setup` - Configure the voice channel system
- `/toggle` - Enable/disable bot features
- `/interface` - Create the voice channel interface
- `/troubleshoot` - Fix common issues

## Support and Community

- **Bot Developer**: Demondev_
- **Discord Support Server**: [Join our support server](https://discord.gg/VQFnjvvFhc)
- **Server Moderators**: Help with server-specific issues
- **Documentation**: This guide covers all user features
- **Updates**: Chamber is regularly updated with new features

## Technical Information

- **Built with**: [Discord.js](https://discord.js.org/) v14.14.1
- **Runtime**: [Node.js](https://nodejs.org/) 18.0.0+
- **Database**: [MongoDB](https://mongodb.com/) 6.0+
- **License**: [MIT License](LICENSE)

---

**Remember**: Chamber is designed to make your Discord voice experience more dynamic and fun. Use these features responsibly and respect your fellow server members!

*Last updated: 4 August 2025* 
