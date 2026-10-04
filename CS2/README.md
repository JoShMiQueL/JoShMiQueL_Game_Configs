# CS2 Configuration

## Setup

| | |
|---|---|
| CPU | i7-14700K |
| GPU | RTX 4060 Ti |
| RAM | 32 GB |
| Monitor | 1920x1080 @ 280 Hz |
| Mouse | Zowie EC3-C |
| DPI | 400 |
| Resolution | **1280x960**, 4:3 stretched |

## Install

Copy [`autoexec.cfg`](autoexec.cfg) to:

```
...\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\autoexec.cfg
```

Steam → CS2 → Properties → General → Launch Options:

```
+exec autoexec.cfg -console -high -refresh 280 -allow_third_party_software
```

## Sensitivity

`1.2` at 400 DPI → **480 eDPI**. eDPI is DPI × sensitivity, how setups get compared across players.

From VALORANT 0.45, which is the same setup:

```
CS2 sens = VALORANT sens × (0.07 ÷ 0.022) = 0.45 × 3.1818 = 1.43
```

Pro settings, 38 players from prosettings.net:

| Player | DPI | Sens | eDPI |
|---|---|---|---|
| ZywOo | 400 | 1.9 | 760 |
| donk | 800 | 1.25 | 1000 |
| sh1ro | 800 | 1.04 | 832 |
| b1t | 800 | 0.825 | 660 |
| device | 800 | 0.95 | 760 |
| m0NESY | 400 | 2.3 | 920 |
| **This config** | **400** | **1.2** | **480** |

Median across pros: **800 eDPI**. Most common DPI: 400 (19 players) and 800 (17). |

## Crosshair

```
CSmT2d8xVhWpvPsbqUSGtVVWuPtjteuOEMcojKDPDjhRfJ
```

The crosshair is set by the autoexec, so there is nothing to paste. The commands below were generated from the share code with [`csxhair`](https://github.com/SyberiaK/csxhair).

| Convar | Value |
|---|---|
| `cl_crosshairstyle` | 4 |
| `cl_crosshair_length` | 2 |
| `cl_crosshair_thickness` | 1 |
| `cl_crosshair_gap` | 1 |
| `cl_crosshaircolor_r/g/b` | 255 / 0 / 0 |
| `cl_crosshaircolor_a` | 255 |
| `cl_crosshairdot` / `_t` / `_recoil` | false |
| `cl_crosshair_drawoutline` | 0 |
| `cl_crosshairoutline_r/g/b/a` | 0 / 0 / 0 / 255 |
| `cl_crosshair_dynamic_splitdist` | 4 |
| `cl_crosshair_dynamic_spread_limit` | 227 |
| `cl_crosshair_dynamic_splitalpha_innermod` | 1.0 |
| `cl_crosshair_dynamic_splitalpha_outermod` | 0.3 |
| `cl_crosshair_dynamic_maxdist_splitratio` | 0.0 |
| `cl_ironsight_dot_scale` | 1.0 |
| `cl_ironsight_usecrosshaircolor` | false |

## Settings

| | |
|---|---|
| **Audio** | HRTF on, 0.5 lerp, volume 0.4 |
| **Muted** | deathcam, menu music, round start/end, bomb plant |
| **MVP music** | 0.25 |
| **Radar** | 0.4 scale, uncentred, rotated |
| **Boost Player Contrast** | on |
| **Viewmodel** | FOV 68, offset 2.5 / 0 / −2, right handed |
| **Telemetry** | frametime and ping shown |

**Muted sounds** carry no information: death cam, menu music, round start/end stingers, bomb-plant beeps. MVP music stays at 0.25, the 10-second warning sits low at 0.15.

**HRTF** (`snd_steamaudio_enable_perspective_correction`) makes footsteps play from the direction they come from instead of flat stereo.

## Credits

- [csxhair](https://github.com/SyberiaK/csxhair) by SyberiaK — crosshair share code decoding, MIT

---

[JoShMiQueL](https://github.com/JoShMiQueL)