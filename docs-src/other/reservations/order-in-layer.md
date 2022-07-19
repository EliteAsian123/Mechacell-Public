# SpriteRenderer "Order in Layer"

Commonly used layers are in bold.

## Mission Mode

| Sprite Order | Purpose |
|--------------|--------|
| `-100` and lower | Background |
| `-50` | Leaf Rings / Detached Backgrounds |
| `-15` | **Background Particles** |
| `-10` to `-4` | **Decoration Entity** |
| `-3` | Item Collectable |
| `-2` | **Background Entity** |
| `-1` | Heart, Blueprint, and Data Collectable |
| `0` to `4` | **Normal Entity** |
| `5` | Player Cell |
| `6` | Player Cosmetic Lights |
| `7` | Player Dirt |
| `8` | **Virus-Like Entity** |
| `9` | Unconstructed Weapons |
| `10` | Weapon Base |
| `11` | Weapon Cosmetic Lights |
| `12` to `14` | Weapon Overlay / Particle |
| `15` | Player Shield |
| `16` to `17` | **Foreground Entity** |
| `18` to `19` | **Foreground Particles** |
| `20` | Projectiles |
| `21` | Projectile Particles |
| `99` | Ghosts |
| `100` | **Ambient Particles** |
| `1000` | Water Droplets |
| `10000` | World Border |
| `32766` | Damage Blocked Icon |
| `32767` | Damage Text |