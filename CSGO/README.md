# [config.cfg](https://github.com/JoShMiQueL/JoShMiQueL_Game_Configs/blob/main/CSGO/config.cfg)
# [autoexec.cfg](https://github.com/JoShMiQueL/JoShMiQueL_Game_Configs/blob/main/CSGO/autoexec.cfg)
# [practice.cfg](https://github.com/JoShMiQueL/JoShMiQueL_Game_Configs/blob/main/CSGO/practice.cfg)
Config from game [Counter-Strike: Global Offensive](http://counter-strike.net).

#### Installation "autoexec.cfg"
Place `autoexec.cfg` in your `...\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg` folder.

In steam, go to game properties and add `+exec autoexec.cfg` to launch options.

**OR**

Ingame, open the console and type `exec autoexec`. Now the autoexec should take effect without any further action from you in future.

#### Installation "practice.cfg"
Place `practice.cfg` in your `...\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg` folder.

The included binds are disabled by default, and you will need to uncomment them if you wish to use them. Don't forget to setup the crosshair to your liking if you wish to use the fullscreen crosshair bind!

#### Installation "video.txt"
Place `video.txt` in your `...\Steam\userdata\[UserId3]\730\local\cfg` folder.

#### Features
- Jump-throw & run-jump-throw binds for consistent grenades.
- Aliases and binds to quickly set up a match to practice.

#### Default Binds
- `F5` Say GL&HF!
- `F6` Say GH!
- `F7` Say GG!
- `V` Jump-throw.
- `N` Noclip (requires sv_cheats 1).

#### Commands
- `practice` Enables cheats, sets roundtime to 60, kicks bots, sets cash to 50000, enables infinite ammo, and enables grenade trajectories and impact and penetration data.

### Launch Options
- `-novid -no-browser -nojoy -freq 60 +snd_use_hrtf 0 +exec autoexec.cfg`

- `NOTE: change -freq XXX to match YOUR monitors refresh rate: (Have 144hz monitor? use -freq 144)`
#### Credits
- [JoShMiQueL](https://github.com/JoShMiQueL)
