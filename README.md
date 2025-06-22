# Clan Team Sync

**Version:** 1.0.0  
**Author:** AnotherPanda  
**Description:** Automatically synchronizes Rust teams with Clans plugin.

---

## Features

- Syncs in-game teams with Clans plugin members.
- Automatically creates/disbands teams when clans are formed/disbanded.
- Assigns team leader based on the clan owner (if online).
- Automatically removes players from the clan if they leave the team.
- Invites players to the clan when they join a team.
- Validates and restores team composition when players reconnect.

---

## Configuration

_No configuration required._

---

## Usage

- Clan creation or updates automatically create/update in-game teams.
- Leaving a team can trigger clan removal.
- Rejoining the server will restore proper team-clan sync.

---

## Dependencies

- Requires the [Clans](https://umod.org/plugins/clans) plugin.

---

## Notes

- Based on and improved from the original [Clan Team](https://umod.org/plugins/clan-team) plugin by deivismac.
