<p align="center">
    <a href="https://github.com/Vecnavium/PureChat"><img src="https://github.com/Vecnavium/PureChat/blob/stable/863.png"></img></a><br>
    <b>Provides custom chat formats based on PurePerms groups for your server.</b>
</p>

<p align="center">
    <img alt="GitHubrelease" src="https://img.shields.io/github/v/release/Vecnavium/PureChat?label=release&sort=semver">
      <img alt="Stars" src= "https://img.shields.io/github/stars/Vecnavium/PureChat?style=for-the-badge">
    <a href="https://discord.gg/6M9tGyWPjr"><img src="https://img.shields.io/discord/837701868649709568?label=discord&color=7289DA&logo=discord" alt="Discord" /></a>
</p>


# Commands

Command | Description | Permission
--- | --- | ---
`/setsuffix <player> <suffix>` | Set a players suffix. | pchat.command.setsuffix
`/setprefix <player> <prefix>` | Set a players prefix | pchat.command.setprefix
`/setnametag <group> <world> <format>` | Set the default nametag of a group | pchat.command.setnametag
`/setformat <group> <world> <format>` | Set default chat format | pchat.command.setformat


# FAQ

**Why can't players have coloured chat?**

You need to set 'pchat.coloredMessages' permission for the players if you want to allow them to use colored messages

**What are the colour codes to use, and where should I put them?**

See the available colour codes listed in the Config. Do not use colour codes in PurePerms groups directly, use PureChat config instead.

# Permissions

 - pchat
 - pchat.coloredMessages
 - pchat.command
 - pchat.command.setsuffix
 - pchat.command.setprefix
 - pchat.command.setnametag
 - pchat.command.setformat
