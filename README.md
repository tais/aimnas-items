# AIMNAS-Items

The **AIMNAS** weapon/item roster (all its guns, ammo, gear, attachments, graphics, and
enemy/dealer loadouts) on the **original Jagged Alliance 2 1.13 campaign maps** — instead
of AIMNAS's oversized "Bigmaps" world. You play the original-sized maps, but everything you
loot, buy, and fight against comes from AIMNAS. The original maps have their item placements
rewritten to AIMNAS's item IDs so loot and enemy gear are correct.

## Install

Install in this order:

1. A clean **Jagged Alliance 2 (Gold)**.
2. **JA2 1.13** on top of it (a recent build; 1.13 is now developed at
   <https://github.com/1dot13/source>).
3. **This mod** on top: download the repo contents and unpack them into your JA2 game folder
   (the one with `ja2.exe`). You'll get `Data-AIM-Items/`, `vfs_config.JA2113AIMItems.ini`,
   and `Ja2.ini` (overwrites the existing one).

Then launch and **start a NEW game** — existing 1.13/AIMNAS saves use different item IDs and
won't work. You don't need AIMNAS itself installed.

## Notes

* Combat keeps the original 1.13 feel (NCTH off). To use AIMNAS's designed accuracy system,
  set `NCTH = TRUE` in `Data-AIM-Items/Ja2_Options.INI` and copy AIMNAS's `CTHConstants.ini`
  into that folder.
* Your saves go in a separate profile, so this won't disturb your other 1.13 games.

## Credits

Built entirely on other people's work — full credit to them:

- **AIMNAS** (<https://github.com/aimnas>) — the weapon/item roster, graphics, sounds, and
  loadout data this mod carves out and re-points onto the original maps.
- **JA2 1.13** (<https://github.com/1dot13>) — the engine and base this runs on.
- **Jagged Alliance 2** (Sir-Tech) — the original game and its maps.

Unofficial fan project — requires a working JA2 1.13 install, and is not affiliated with
or endorsed by the AIMNAS project or Sir-Tech.
