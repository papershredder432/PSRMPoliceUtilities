# PSRMPoliceUtilities
A RocketMod plugin so your police can do their job (For RP ofc)

Admins are immune to being jailed by default.

## [Support Discord](https://discord.gg/ydjYVJ2)

### Permissions
| Permission Name | Command Usage | Is Implemented? | Description |
| ------------- | ------------- | ------------- | ------------- |
| `ps.policeutilities.jailmanager` | `/createjail <JailName>` | Yes | Creates a jail |
| `ps.policeutilities.jailmanager` | `/deletejail <JailName>` | Yes | Deletes a jail |
| `ps.policeutilities.free` | `/free <Player>` | Yes | Frees a player from a jail |
| `ps.policeutilities.isjailed` | `/isjailed <Player>` | Yes | Checks if a player is in jail |
| `ps.policeutilities.jail` | `/jail <Player> <JailName> <LengthInSeconds> [Reason]` | Yes | Puts a specified player in jail for a chosen amount of seconds |
| `ps.policeutilities.jailimmune` | N/A | Yes | Makes a player immune to being jailed |

### To Do
- [x] Add DeleteJail command
- [x] Add JailImmune
- [x] Implement jailed players get out after specified time
- [ ] Implement optional Discord webhooks
- [x] add more to this list
- [ ] Teleport players to the universal release position when /freed or on timeout
