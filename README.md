# Male Wolfein Expanded

A RimWorld mod that adds rare male Wolfein to [Wolfein Race](https://steamcommunity.com/sharedfiles/filedetails/?id=3473140562).

By default the Wolfein are almost entirely female (`maleGenderProbability` near zero with `fixedGender Female`). This mod unlocks Male pawns at a 10% spawn chance by default, adjustable via Mod Settings.

## Features

- Adds Male adult Wolfein + Ghoul variant, with tail and ear offsets.
- Flat child bodies, so boys no longer use the breasted base child art (girls pre-puberty use it too — Child/Baby are unisex).
- Removes `fixedGender` on Wolfein pawns so `maleGenderProbability` applies.
- Male apparel mirrors for the base race plus compatible Wolfein apparel mods.
- With [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206): adjust the male spawn chance in Mod Settings (0–100%, restart required). Without it: fixed 10%.

## Requirements

- RimWorld
- [Wolfein Race](https://steamcommunity.com/sharedfiles/filedetails/?id=3473140562)
- [Ancot Library](https://steamcommunity.com/sharedfiles/filedetails/?id=2988801276) (Wolfein Race dependency)
- [Humanoid Alien Races](https://steamcommunity.com/sharedfiles/filedetails/?id=839005762) (Wolfein Race dependency)
- [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206) (optional but recommended — enables the spawn-chance slider; without it the chance is fixed at 10%)

## Installation

### Steam Workshop

Subscribe to the required mods and add them to your RimWorld mod list in the following order:

1. Harmony (if required by HAR/dependencies)
2. Core
3. Royalty, Ideology, Biotech, and Anomaly, if applicable
4. [Humanoid Alien Races](https://steamcommunity.com/sharedfiles/filedetails/?id=839005762)
5. [Ancot Library](https://steamcommunity.com/sharedfiles/filedetails/?id=2988801276)
6. [Wolfein Race](https://steamcommunity.com/sharedfiles/filedetails/?id=3473140562)
7. [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206) (optional)
8. Male Wolfein Expanded

This mod should load after [Wolfein Race](https://steamcommunity.com/sharedfiles/filedetails/?id=3473140562) and XML Extensions.

### Manual Installation

1. Download the latest release from the [**Releases**](https://github.com/Keullaeseu/Male-Wolfein-Expanded/releases/latest) section.
2. Extract the mod folder into your RimWorld `Mods` directory.
3. Enable the required mods in RimWorld.
4. Use the recommended load order listed above.

## Usage

1. Enable the mod alongside Wolfein Race.
2. Start or continue a colony — male Wolfein spawn at 10% by default.
3. Optional: open Mod Settings → Male Wolfein to change `Male Wolfein: {value}` (requires XML Extensions + game restart).

Do not change the slider and expect already-spawned pawns to reroll gender — it only affects newly generated pawns.

## Compatibility

Male apparel mirrors are included for:

- Wolfein Race base apparel (Red-Eyed Armor uses its native Male-shape Thin art)
- Wolfein Black Science Expand (mirrors loaded when active)
- Wolfein Race MegaCorp Edition (mirrors loaded when active)
- Wolfein extension: Little Red Riding Hood (mirrors converted from its native Thin art, loaded when active)

No patch needed for:

- Wolfein Allegiance, Imperial Weapons, Extra Backstories / Genes, Gene Patch, GFI Expand (no apparel)

It does not replace:

- [Wolfein Race](https://steamcommunity.com/sharedfiles/filedetails/?id=3473140562)

## Known Limitations

- Male apparel textures are Female-cut copies as placeholders (no errors, slightly feminine fit). Proper flattened male cuts may replace them later.
- Supplied `PreTeenager` body files are unused (base maps PreTeenager age to the Child body).
- Compatibility may be affected by future RimWorld or Wolfein Race updates.
- Any third-party Wolfein apparel mod without Male variants will log `Failed to find ..._Male` errors on male pawns until mirrors are added.

## Credits

- [Wolfein Race on Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3473140562)
- [Ancot Library](https://steamcommunity.com/sharedfiles/filedetails/?id=2988801276)
- [Humanoid Alien Races](https://steamcommunity.com/sharedfiles/filedetails/?id=839005762)
- [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206)
- [Male Wolfein Expanded](https://github.com/Keullaeseu)
