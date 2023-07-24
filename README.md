PvPToggle
=========

Gives ability to toggle player's PvP status
- Originally made by White.
- Updated to **TShock** `4.5.11` by [QuiCM](https://github.com/QuiCM).
- Updated to **TShock** `5.2` by yours truly.

## How to Install
1. Put the .dll into the `\ServerPlugins\` folder.
2. Restart the server.
3. Give the desired permissions to your disired groups.

## How to Use
### Config Options
- `ForcePvPOnBloodMoon` - Determines whether the plugin should force pvp for everyone when a bloodmoon is active.
### Commands and Usage
- `pvp` - toggles pvp for the sender the same way UI would.
- `tpvp {player name}` - toggles pvp normally for the targeted player, requires the `pvp.switch` perm. 
- `team {team color}` - switches the sender's team to the parametered color.
- `tteam {player name} {team color}` - switches the targeted player's team to the parametered color. requires the `pvp.team` perm.
- `forcepvp/fpvp {player name/*/*off}` - toggles forcedPvp for the targeted player, `*` and `*off` can be used as parameter to respectively activate/deactivate forcedPvp for everyone, requires the `pvp.force` perm.
- `bloodmoonpvp/bmpvp` - toggles wheather forcedPvp should be automatically activated for everyone on bloodmoons, requires the `pvp.moon` perm.

## How to Build
1. Download the source code.
2. Open the `.sln` file.
3. Check to make sure the references are all correct and up to date.
4. Build.

 ## Notes
 - The credits for the PvPToggle plugin goes to White and [all those who contributed on the project so far](https://github.com/Maxthegreat99/PvPToggle/commits/master).
 - If you find any bugs create an issue or report it to my [discord](https://discord.gg/e465y7Xeba).
# Orginal Plugin Repository
https://github.com/QuiCM/PvPToggle/tree/master
