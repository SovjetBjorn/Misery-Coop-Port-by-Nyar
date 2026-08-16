# Changelog

## v0.5 — 2026-08-16

**Install requirement changed: this build needs AGWP 2, not AGWP 1.**
Install AGWP 2 first, then this mod on top. Existing saves keep working.

- Shotgun crash fixed: MR-133, Benelli M3 and MP-153 no longer crash the game
  when you equip them. (Models rebuilt by Vlad.)
- Suit crash fixed: the SSP-99 and SSP-99M Ecologist suits and the Ghillie suit
  no longer crash the game when you put them on.
- Fixed CTD when equipping a helmet. Affected every helmet in the game.
- Fixed CTD during fights — a dead player's handler kept receiving events.
- Fixed the dedicated server crash that dropped the whole lobby at once.
- Fixed the server crash in the mercenary camp fight on Zaton. Reloading the save
  and walking back into that fight crashed the server every time.
- Fixed a server crash caused by a single malformed line in a config file. A bad
  line now writes a warning naming the file instead of dropping everyone.
- Fixed a client crash when picking up an artefact.
- Fixed a crash from zombies using a missing animation file.
- Shipped the screen-effect files for helmets and for taking a heavy hit. They
  were referenced but missing, so the game crashed the moment one was needed.
- New first-person hands models.
- Army squads now spawn in the world simulation. They never had, so those
  spawn slots were sitting empty.
- AUG, DVL-10 and G36 temporarily pulled from traders and NPC loadouts while
  their fixes are finished. Ones you already own still work — they just won't
  drop or appear in stock for now.

## v0.4.1 — 2026-08-12

- Fixed loot reservation CTD.
- Blocked MP-153 from spawning.
- Fixed spawn rate of exoskeletons.

## v0.4 — 2026-08-10

- Flashlight issue fixed (allegedly).
- MP18 fixed.
- Medical issues fixed (allegedly).
