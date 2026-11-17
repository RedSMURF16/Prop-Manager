<h1 align="center">Prop Manager</h1>

<p align="center">
  <a href="https://www.youtube.com/watch?v=6wWm1Pe0n2Q"><img src="https://img.youtube.com/vi/6wWm1Pe0n2Q/maxresdefault.jpg" alt="Watch on YouTube" width="600"></a>
</p>

## 📝 Description
This plugin adds a fully dynamic prop placement system to Counter-Strike 1.6.
Props can be placed, managed and configured during gameplay with full runtime control over positioning, rotation and persistence.
Custom setups are saved per map and automatically loaded on every map start.
- Place and remove props during gameplay via an in-game menu
- Large library of props: barrels, crates, signs, fences, furniture, neon decor and more
- Ghost preview model with natural alignment to ground and walls while placing
- Adjustable placement offset (forward distance) with scroll-wheel control
- Configurable per prop: model, solidity, animation sequence, framerate and spawn chance
- Custom bounding box per prop for accurate collision matching the model's shape
- Per-map saving and automatic loading of placed props

## 📋 Requirements
- ReGameDLL
- AMX Mod X 1.10+

## 💬 Commands
- `say /pm` - Opens the Prop Manager menu.
- `say_team /pm` - Opens the Prop Manager menu.
- `say /prop` - Opens the Prop Manager menu.
- `say_team /prop` - Opens the Prop Manager menu.
- `pm_reload` - Reloads the configuration file.
- `prop_reload` - Reloads the configuration file.

## ⚙️ Configuration
```ini
# Per-prop settings (defined under each [Prop Name] section):
# PROP_MODEL                      = Path of prop's model
# PROP_FLAGS                      = a - Solid, b - Anim
# PROP_SEQUENCE                   = Animation sequence for the prop model
# PROP_FRAMERATE                  = Animation frame rate for the prop model
# PROP_SPAWN_CHANCE               = Prop's respawn probability (0.0 = never, 1.0 = always)
# PROP_MINS                       = Minimum bounding box of the prop (x y z)
# PROP_MAXS                       = Maximum bounding box of the prop (x y z)
```

## 🔄 Changelog
```text
* v1.0: Initial release.
```

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20video-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=6wWm1Pe0n2Q)
