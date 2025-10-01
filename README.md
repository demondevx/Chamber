# 🏛️ Chamber Bot - User Guide

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
- Note: 6-minute cooldown between renames

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

**`/voice status <message>`** ✨ NEW
- Set a custom status message that appears on your voice channel
- Example: `/voice status Chill vibes only`

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

**`/voice invite @user`**
- Send a direct invite to someone to join your channel
- Example: `/voice invite @friend`

**`/voice age-restricted`**
- Toggle age-restricted mode for your channel
- Useful for adult content discussions

**`/voice bitrate <kbps>`**
- Set custom audio quality for your channel
- Higher bitrate = better audio quality

**`/voice permit-role @role`**
- Allow an entire role to join your channel
- Example: `/voice permit-role @Moderators`

**`/voice reject-role @role`**
- Prevent an entire role from joining your channel

## 🌍 Region Controls ✨ NEW

Optimize your voice quality by selecting the server location closest to you!

**`/region`**
- Opens a menu to choose your preferred voice server region
- **12 Available Regions**: Automatic, Brazil, Hong Kong, India, Japan, Rotterdam, Singapore, South Africa, US Central, US East, US South, US West
- Lower latency = better call quality
- Change anytime with no cooldown

You can also change your region from the **Channel Interface** menu!

## 💾 Profile System ✨ NEW

Save your favorite channel settings and apply them instantly!

**`/profile save <name>`**
- Save your current channel configuration as a preset
- Example: `/profile save My Gaming Setup`

**`/profile apply`**
- Choose from your saved profiles and apply settings in one click

**`/profile list`**
- View all your saved profiles

**`/profile delete <name>`**
- Remove profiles you no longer need

**`/profile set-default <name>`** (Premium Only)
- Set a profile to auto-apply to every new channel you create

**What Gets Saved:**
- **Free Users**: Channel name and limit (1 profile)
- **Premium Users**: Name, limit, region, ghost mode, lock status (20 profiles)

## 📊 Stats & Leaderboards ✨ NEW

Track your voice channel activity and see community rankings!

**`/stats`**
- View server-wide voice channel statistics
- See total channels created and overall activity

**`/stats me`**
- Check your personal voice channel usage
- See how many channels you've created and time spent

**`/leaderboard`**
- View community rankings
- **Top VC Creators**: Who creates the most channels
- **Longest Sessions**: Who spends the most time in voice
- **Time Frames**: Weekly, monthly, or all-time stats

## 🎫 Access Request System ✨ NEW

Let users politely request access to your locked channels!

**`/permitembed`**
- Posts an interactive panel for requesting channel access
- Users can browse available temporary channels
- Send access requests with one click

**How It Works:**
1. User runs `/permitembed` and selects "Channel List"
2. Picks your channel from the dropdown
3. Request appears in your voice channel's text area with Accept/Reject buttons
4. You click to approve or deny
5. Permissions update automatically

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
- **Unlimited Profiles**: Save up to 20 channel configurations with all settings
- **Auto-Apply Profiles**: Set defaults that apply automatically to new channels
- **Text Channel Creation**: Create temporary text channels for your voice channels
- **Game Detection**: Automatic channel renaming based on your current game
- **Ghost Mode**: Hide your channels from the public
- **Direct Invites**: Send personalized invites to users
- **Age-Restricted Toggle**: Control adult content settings
- **Custom Bitrate**: Set higher audio quality
- **Role Permissions**: Control access by entire roles
- **Premium Support**: Priority help when you need it

### How to Get Premium:
Contact the bot owner or server administrator. Premium is activated per-server, so all members benefit!

## Tips and Best Practices

### Channel Management
- **Be Respectful**: Don't abuse the lock/unlock feature to exclude people unfairly
- **Use Descriptive Names**: Name your channels clearly so people know what's happening
- **Save Profiles**: Create presets for quick setup
- **Pick Your Region**: Choose a voice server near you for better quality
- **Clean Up**: When you're done, leave your channel - it will automatically delete

### Privacy and Safety
- **Ghost Mode**: Use this for private conversations (Premium)
- **Lock + Permit**: Control exactly who can join
- **Access Requests**: Let people ask politely instead of forcing entry
- **Age-Restricted Content**: Use the toggle for adult discussions

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
- Wait 6 minutes between renames (cooldown to prevent spam)
- Try the command again

**"I can't save more profiles!"**
- Free users get 1 profile - upgrade to premium for 20 profiles
- Premium users have a 20 profile limit

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
- **`/setup`** - Configure the voice channel system
- **`/toggle`** - Enable/disable bot features
- **`/interface`** - Create the voice channel interface
- **`/troubleshoot`** - Fix common issues
- **`/premium status`** - Check server premium status

## Support and Community

- **Bot Developer**: Demondev_
- **Discord Support Server**: [Join our support server](https://discord.gg/VQFnjvvFhc)
- **Email**: [demondev_](mailto:demondevxx@gmail.com)
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

[![Vote My Bot](https://top.gg/api/widget/1401037197645189160.svg)](https://top.gg/bot/1401037197645189160)


*Last updated: September 30, 2025*
