# dEzz CS2 config

My `binds.cfg` for Counter-Strike 2 (sensitivity, viewmodel, binds, F1–F12 buy binds, demo binds) plus my main graphics and audio settings.

## Installation

1. Download `binds.cfg` (**Code → Download ZIP**, or open the file → **Download raw file**).
2. Put it in:
   ```
   Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
   ```
3. In Steam: right-click CS2 → **Properties** → **Launch Options**, add:
   ```
   +exec binds
   ```
4. Launch the game — the console will print `dEzz's settings have been loaded.`

## Basics

| Setting | Value |
|---|---|
| Sensitivity | 0.625 |
| Zoom ratio | 1 |
| Crosshair | style 4, size 1, yellow (255 222 0), outline |
| Viewmodel | fov 68, x 2.5, y 0, z -1.5 |

## Graphics

Set in **Settings → Video** (stored in `cs2_video.txt`, not in a cfg).

| Setting | Value | Parameter |
|---|---|---|
| Resolution | 1440×1080 (4:3) | `defaultres` / `aspectratiomode 0` |
| Refresh rate | 240 Hz | `refreshrate_numerator 240` |
| Display mode | Fullscreen | `fullscreen 1` |
| Brightness (gamma) | 2.1 | `r_fullscreen_gamma 2.1` |
| Boost player contrast | Enabled | `r_player_visibility_mode 1` |
| V-Sync | Disabled | `mat_vsync 0` |
| NVIDIA Reflex | Enabled + Boost | `r_low_latency 2` |
| Max FPS | Unlimited | `fps_max 0` |
| Anti-aliasing | 4x MSAA | `msaa_samples 4` |
| Global shadow quality | High | `videocfg_shadow_quality 2` |
| Dynamic shadows | All | `videocfg_dynamic_shadows 1` |
| Model / texture detail | Low | `videocfg_texture_detail 0` |
| Texture filtering | Anisotropic 4x | `r_texturefilteringquality 3` |
| Shader detail | Low | `shaderquality 0` |
| Particle detail | Low | `videocfg_particle_detail 0` |
| Ambient occlusion | High | `videocfg_ao_detail 3` |
| HDR | Performance | `videocfg_hdr_detail -1` |
| FidelityFX (FSR) | Disabled | `videocfg_fsr_detail 0` |

## Audio

| Setting | Value | Parameter |
|---|---|---|
| Master volume | 100% | `volume 1` |
| EQ profile | Crisp | `snd_headphone_eq 1` |
| L/R isolation | 0.33 | `snd_spatialize_lerp 0.327` |
| Perspective correction | Enabled | `snd_steamaudio_enable_perspective_correction 1` |
| Play audio when game is in background | Disabled | `snd_mute_losefocus 1` |
| Voice chat | 81% | `snd_voipvolume 0.81` |
| Main music volume | 100% | `snd_musicvolume 1` |
| Main menu music | 4% | `snd_menumusic_volume 0.04` |
| Round start | 0% | `snd_roundstart_volume 0` |
| Round end | 0% | `snd_roundend_volume 0` |
| Round action | 0% | `snd_roundaction_volume 0` |
| Bomb / hostage | 0% | `snd_mapobjective_volume 0` |
| Ten second warning | 4% | `snd_tensecondwarning_volume 0.04` |
| MVP music | 9% | `snd_mvp_volume 0.088` |
| Death camera | 0% | `snd_deathcamera_volume 0` |

## Binds

| Key | Action |
|---|---|
| Shift | jump |
| Space | crouch |
| Ctrl | walk |
| R | use |
| Q | knife (while held) |
| C | voice chat |
| V | buy menu |
| PgUp / PgDn | toggle voice / toggle volume |
| `[` | cycle crosshair color |
| F1–F4 | AK/M4, MP7, P250, AWP |
| F5–F8 | flash, HE, molotov, smoke |
| F9–F12 | kevlar, kevlar+helmet, defuse kit, decoy |
| Ins / Home | demo fast-forward x10 / slow-mo x0.5 |
| Del / End | pause demo / demoui |
| `\` | X-ray in spectator |
| J / N | remove smokes / noclip (sv_cheats only) |
