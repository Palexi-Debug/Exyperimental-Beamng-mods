# Universal Weapons (Tunable)

Based on "Universal Weapons" by stefan750 (BeamNG mod).

Changes:
- New weapon "Tunable Cannon" (fixed + turret variant). Strength is set in the Tuning menu (Weapon > Tunable Cannon):
  explosion radius/force, muzzle velocity, projectile mass, fire rate, recoil.
- Vehicle-side hit registration for all weapons (`universalweapons.lua`), so shots hit other vehicles even when the
  projectile node does not collide physically. Only locally owned vehicles take hits (BeamMP).
- Vivace presets: `tunecannon`, `tunecannon_turret`.

Install: zip the contents of this folder (lua, vehicles, settings at the zip root) and put the zip into
`Documents/BeamNG.drive/mods`. Disable the original Universal Weapons mod.
