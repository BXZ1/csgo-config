<p align="center"><img src="https://i.imgur.com/NsN13SA.png"></p>

# Installation Steps:

### 1. Launch Options
```
-high -novid -nojoy +mat_queue_mode 2 -tickrate 128 -language zak +exec autoexec
```
> To input launch options, head over to Steam, right click on CSGO and go to properties.

### 2. [Download](https://github.com/BXZ1/csgo-config/zipball/master) the config and extract the following files
* `csgo_zak.txt` > Steam\steamapps\common\Counter-Strike Global Offensive\csgo\resource
* `radial_custom.txt` > Steam\steamapps\common\Counter-Strike Global Offensive\csgo
* `autoexec.cfg` `binds.cfg` `misc.cfg` `practice.cfg` `pvp.cfg` `video.txt` > Steam\userdata\ **XXXXX** \730\local\cfg
>**XXXXX** = Your Steam Account ID <br>1. Visit [STEAMID I/O](https://steamid.io) and login or paste your steam profile URL <br>2. Look for steamID3 ( *that’s the name of your folder* )

### 3. Launch CS:GO and type `apply` in the console

# Binds:

| Key | Description |
| --- | --- |
| F1 | Play [SLAM](https://github.com/SilentSys/SLAM) selected sound (Also used for voting) |
| F2 | Toggle Net graph (Also used for voting) |
| F3 | Buy M4A4/M4A1-S or AK-47 |
| F4 | Buy Smoke, Flash, HE, Molotov/Incendiary |
| F5 | Open Radio Wheel 1 |
| F6 | Open Radio Wheel 2 |
| F7 | Toggle Mute Enemy Chat |
| F8 | Call timeout |
| F9 | Type ( ͡° ͜ʖ ͡°) in chat |
| F10 | Type ¯\\_(ツ)_/¯ in chat |
| F11 | Type ಠ_ಠ in chat |
| F12 | Screenshot Bind (Because i disabled steam overlay) |
| 1234 | Switch between Primary, Secondary, Knife, Throwables |
| WASD | Movement (Will clear decals while moving)<br />(An option is available in [binds.cfg Line 15](https://github.com/BXZ1/csgo-config/blob/master/binds.cfg#L11-L23) to switch between QWERTY and AZERTY Layouts) |
| B | Buy Menu |
| E | Use |
| F | Open the radial menu for selecting throwables<br /><img src="https://i.imgur.com/fj9bcc1.png"><br />(An option is available in [binds.cfg Line 21](https://github.com/BXZ1/csgo-config/blob/master/binds.cfg#L11-L23) to switch between inspect-weapon or the radial menu) |
| G | Drop Weapon |
| M | Team Selection Menu |
| N | Jump Throw |
| R | Reload Weapon |
| T | Grafitti Menu (Will also inspect the current weapon) |
| U | Team Chat |
| Y | Chat |
| V | Voice Key |
| H | Radio Chat "Cover Me" |
| J | Radio Chat "Sorry" |
| K | Radio Chat "Enemy Down" |
| L | Radio Chat "Bomb is Going to Blow" (Can be annoying to other players) |
| Z | Radio Menu 1 |
| X | Radio Menu 2 |
| C | Radio Menu 3 |
| SPACE | Jump+Duck |
| CTRL | Duck (An option is available in [binds.cfg Line 18](https://github.com/BXZ1/csgo-config/blob/master/binds.cfg#L11-L23) to switch between CTRL and ALT) |
| ALT | Drop C4 (An option is available in [binds.cfg Line 18](https://github.com/BXZ1/csgo-config/blob/master/binds.cfg#L11-L23) to switch between CTRL and ALT) |
| SHIFT | Walk |
| TAB | Stats and Scores |
| CAPSLOCK | Toggle noclip |
| HOME | Disconnect from server |
| END | Mute voice chat for one round |
| NUMPAD ENTER | Mute voice chat for one round |
| INSERT | Increase+ voice chat volume by 5% |
| NUMPAD + | Increase+ voice chat volume by 5% |
| DELETE | Decrease- voice chat volume by 5% |
| NUMPAD - | Decrease- voice chat volume by 5% |
| PAGEUP | Zoom+ Radar by 7% |
| PAGEDOWN | Unzoom- Radar by 7%|
| UPARROW | Buy Vest+Helmet |
| DOWNARROW | Buy Vest |
| LEFTARROW | Buy Defuser |
| RIGHTARROW | Buy Decoy |
| MOUSE3 | Player ping (Will also clear decals) |
| NUMPAD 0 | Restart your server |
| NUMPAD 1 | Allow all players in your server to hear/talk to eachother |
| NUMPAD 2 | Allow all players in your server to buy everywhere in the map |
| NUMPAD 3 | Simulate grenade trajectory in your server |
| NUMPAD ./DEL | Rethrow last grenade (In your server) |

# Aliases:

| Alias | Description |
| --- | --- |
| `Slam` | Execute [SLAM](https://github.com/SilentSys/SLAM) |
| `l` | List [SLAM](https://github.com/SilentSys/SLAM) sounds |
| `d` | Disconnect from server (`disconnect`) |
| `q` | Close/Exit CS:GO |
| `rs` | Reconnect to server (`retry`) |
| `c` | Clear console |
| `hud` | Toggle HUD (This alias enables `sv_cheats` in order to hide HUD) |
| `sv` | Toggle `sv_cheats` |
| `apply` | Apply the config |
| `auto` | `exec autoexec` |
| `pract` | `exec practice` (Start practice mode) |
| `pvp` | `exec pvp` (Start pvp mode) |
| `misc` | `exec misc` (Show misc commands in console) |
| `del` | Delete entity |
| `snow` | Give Snowball |
| `snowpile` | Spawn Snowball pile |
| `skull` | Spawn Skull |
| `coin` | Spawn Opration Coin |
| `hostage` | Spawn Hostage |
| `barrel` | Spawn Exploding Barrel |
| `drone` | Spawn Drone |
| `turret` | Spawn Turret |
| `jammer` | Spawn Radar Jammer |
| `tablet` | Give Tablet |
| `mine` | Give BumpMine |
| `exo` | Give Exojump Boots |
| `shot` | Give HealthShot |
| `tag` | Give TAG Grenade |
| `breach` | Give Breach Charge |
| `shield` | Give Shield |
| `suit` | Equip Heavy Assault Suit |
| `chick` | Spawn Chicken |
| `c4` | Give C4 |
| `pc4` | Spawn activated C4 (10s countdown) |
| `knives` | Spawn all CS:GO knives on the ground |
| `melee` | Spawn all Danger Zone melees on the ground |
| `bun` | Enable Auto bunny hopping in your server |
| `armor` | Equip Armor to all players in your server everytime they spawn |
| `helmet` | Equip Armor+Helmet to all players in your server everytime they spawn |
| `noarmor` | All players in your server spawn without Armor |
| `hs` | Toggle Headshot only kills in your server |
| `nosec` | Removes Secondary weapons for all players in your server |
| `nopri` | Removes Primary weapons for all players in your server |
| `usp` | Set **USP-S** as the Default Secondary for Ts and CTs in your server |
| `glock` | Set **Glock-18** as the Default Secondary for Ts and CTs in your server |
| `dual` | Set **Dual Berettas** as the Default Secondary for Ts and CTs in your server |
| `five` | Set **Five SeveN** as the Default Secondary for Ts and CTs in your server |
| `p250` | Set **P250** as the Default Secondary for Ts and CTs in your server |
| `tec9` | Set **TEC9** as the Default Secondary for Ts and CTs in your server |
| `cz` | Set **CZ75-Auto** as the Default Secondary for Ts and CTs in your server |
| `r8` | Set **R8 Revolver** as the Default Secondary for Ts and CTs in your server |
| `deagle` | Set **Desert Eagle** as the Default Secondary for Ts and CTs in your server |
| `nova` | Set **Nova** as the Default Primary for Ts and CTs in your server |
| `xm` | Set **XM1014** as the Default Primary for Ts and CTs in your server |
| `mag7` | Set **MAG-7** as the Default Primary for Ts and CTs in your server |
| `sawedoff` | Set **Sawed-Off** as the Default Primary for Ts and CTs in your server |
| `negev` | Set **Negev** as the Default Primary for Ts and CTs in your server |
| `m2` | Set **M249** as the Default Primary for Ts and CTs in your server |
| `mp5` | Set **MP5-SD** as the Default Primary for Ts and CTs in your server |
| `mp7` | Set **MP7** as the Default Primary for Ts and CTs in your server |
| `mp9` | Set **MP9** as the Default Primary for Ts and CTs in your server |
| `mac10` | Set **MAC-10** as the Default Primary for Ts and CTs in your server |
| `ump` | Set **UMP-45** as the Default Primary for Ts and CTs in your server |
| `p90` | Set **P90** as the Default Primary for Ts and CTs in your server |
| `bizon` | Set **PP-Bizon** as the Default Primary for Ts and CTs in your server |
| `famas` | Set **FAMAS** as the Default Primary for Ts and CTs in your server |
| `galil` | Set **Galil AR** as the Default Primary for Ts and CTs in your server |
| `m4` | Set **M4A4** as the Default Primary for Ts and CTs in your server |
| `m4s` | Set **M4A1-S** as the Default Primary for Ts and CTs in your server |
| `ak` | Set **AK-47** as the Default Primary for Ts and CTs in your server |
| `aug` | Set **AUG** as the Default Primary for Ts and CTs in your server |
| `sg` | Set **SG 553** as the Default Primary for Ts and CTs in your server |
| `scout` | Set **SSG 08** as the Default Primary for Ts and CTs in your server |
| `awp` | Set **AWP** as the Default Primary for Ts and CTs in your server |
| `g3` | Set **G3SG1** as the Default Primary for Ts and CTs in your server |
| `scar` | Set **SCAR-20** as the Default Primary for Ts and CTs in your server |

<br>
<p align="center">
  <a href="https://steamcommunity.com/id/BXZ1">My Steam Profile</a> |
  <a href="https://readtldr.gg/simpleradar">Simple Radar</a> |
  <a href="https://github.com/WilliamRagstad/Font-Manager/releases">CS:GO Font Manager</a> ( <a href="https://www.dafont.com/stanberry.font">My Font</a> ) |
  <a href="https://www.mruy.de/csgo-panorama-backgrounds">Panorama Backgrounds</a>
<br>
<br>
  <b>Check out my Counter Strike 1.6 <a href="https://gist.github.com/BXZ1/2c1bee8f4cda2b0bbef9dbcb4d5d503a">Config</a></b></p>
