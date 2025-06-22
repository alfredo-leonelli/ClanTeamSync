# Clan Team Sync

**Version:** 1.0.0  
**Author:** AnotherPanda  
**Dependency:** [Clans](https://umod.org/plugins/clans)

## Description

**Clan Team Sync** automatically synchronizes in-game teams with clan members created and managed through the Clans plugin. Whenever a clan is created, updated, or modified, the plugin ensures the in-game team accurately reflects the current clan members. It also handles automatic clan invitations and membership when players join teams.

## Features

- **Automatic synchronization** of in-game teams with clan members.
- **Assigns team leader** based on the clan owner (if online).
- **Creates and manages teams** when clans are created or updated.
- **Disbands the team** when a clan is disbanded.
- **Automatically removes players** from the clan if they leave the team.
- **Automatically invites and joins players** to a clan when they accept a team invite from a clan leader.
- **Validates and resyncs** team composition when a player reconnects.
- **Cleans up team membership** for players without a valid clan.

## Based on Original Plugin

This plugin is based on the [**Clan Team** plugin (by deivismac)](https://umod.org/plugins/clan-team), which provided initial logic to sync clan members into teams. However, that version had several limitations and bugs. **Clan Team Sync** includes:

- ✅ Fixes for null reference exceptions and invalid hook names
- ✅ Improved stability and clean team disband logic
- ✅ Full support for dynamic clan member updates (`OnClanMemberJoined/Gone`)
- ✅ Automatic clan invitations when joining teams
- ✅ Safer logic for reconnecting players and team validation

It can be considered a **bug-fixed, expanded and production-ready rewrite** of the original plugin.
