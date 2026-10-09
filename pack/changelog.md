# Skybound SMP Season 2, v2.40

Fixes:
- Fixed ships and other physics structures not showing up until a block was placed next to them, and their blocks not breaking or vanishing when right clicked.


# Skybound SMP Season 2, v2.39

Fixes:
- Fixed the game crashing on startup after updating to 2.38.
- Removed a wall of info text some players got in chat when joining.

Changed:
- Camera screen shake effects are turned off for now, they caused the startup crash.


# Skybound SMP Season 2, v2.38

Added:
- Incendium: the Nether has new biomes and structures.
- Simply Light: simple decorative lamps.
- Decorative Levitite: crafted from levitite, same look, no lift.

Changed:
- Removed Biomes O' Plenty. The Nether has been regenerated, anything left there is gone.
- Updated Create Aeronautics: Gadgets & Gizmos to 1.2.7: Creative RCS Thruster, belt wheel and zipline fixes, thruster light.
- Lighter Flywheel lighting and Sound Physics settings for everyone.
- Train Steps from Create Train Parts can no longer be crafted or placed.
- Ender Linker from Sophisticated Core is disabled, it could lock players out of the server.

Fixes:
- CBC Neo Warfare: unbored rotary and medium cannon parts can be cast again.


# Skybound SMP Season 2, v2.37

Added:
- Ships no longer unload while you are near them or right after you die on board.

Changed:
- Updated 28 mods (Xaero maps, Sophisticated Backpacks, Contraption Lights, AdvancedPeripherals, Create: High Skies and others).
- Create: High Skies: reversing the pump on a gas port now pulls hydrogen back out so you can reuse it.

Fixes:
- CBC Neo Warfare: rotary cannon moulds now cast the right parts, rotary and medium cannons can be cast and bored, and its blocks drop items again.
- Fixed recipe and loot errors in CBC Military Supplement.
- Fixed a client crash when rendering some Copycats+ blocks next to Create copycat panels or steps.
- Removed the dependency override warning screen on game launch.
- Fixed a Better Lib error on game start.


# Skybound SMP Season 2, v2.36

Changed:
- The Mechanical Chicken is now the Mechanical Livestock, and can also produce raw beef, raw porkchop and raw rabbit.
- Banned items are now hidden in JEI.

Fixes:
- Server performance improvements for Create machines and swivel bearings, and nested filter items can no longer overload the server.
- The Changelog button now shows the notes of the version you have installed.
- Missing kerosene and naphtha fluid textures.


# Skybound SMP Season 2, v2.35

Added:
- Create: High Skies (back in the pack)
- Kaleidoscope Cookery, Kaleidoscope Tavern and Kaleidoscope Contraption
- CEE: Voltworks
- CBC Military Supplement
- MALAHIT Monitors
- Create Shining Stage

Balance:
- Kaleidoscope Cookery food buffs nerfed: shorter durations, level I only. Satiated Shield reduction lowered.
- Kaleidoscope Tavern drink buffs nerfed the same way. Harmful effects are unchanged.
- Create Food effects rebalanced for its 3.0 update.

Updated:
- About 90 mods updated to their latest versions, including Create Deep Seas 3.3.0, Sable 2.0.6, TFMG Community Edition 1.3.2a and The Factory Must Work CE 2.1.1.
- Skybound Client Patches 1.6.1 and Skybound Extras 1.1.0.

Removed:
- Xaero's Regions.


# Skybound SMP Season 2, v2.34

Changed:
- config/fml.toml no longer lists ScalableLux in its dependency overrides (ScalableLux was removed in 2.33).


# Skybound SMP Season 2, v2.33

Removed:
- ScalableLux, the light engine added in 2.31. It could crash the game near moving ships (Sable sub levels). Lighting goes back to the vanilla engine.


# Skybound SMP Season 2, v2.32

Updated:
- Create: Deep Seas 3.0.0, the biggest update of the mod. It now includes Create: High Seas (living wind, sails, boat engine, helm and rudder, anchor, oars, buoys, Seaglide, wind vane), real flooding and sinking, hull pressure and implosions, and a computer, sonar and autopilot for submarines.
- Mechanical Chicken now also produces raw chicken.
- Video Settings now opens the Sodium settings screen directly.

Removed:
- Create High Skies, it does not work with Deep Seas 3.0.0 yet. Its blocks disappear from the world.

Heads-up:
- The old Weather Vane and Submarine Rudder from Deep Seas are gone. Use the new High Seas Wind Vane and Rudder.
- Symmetric Sails no longer push ships, replace them with the new Sail.
- Hull strength values were rebalanced per material. Glass holds about 20 to 30 blocks of depth, iron about 100.


# Skybound SMP Season 2, v2.31

Added:
- ScalableLux, a faster multithreaded light engine based on Starlight, on both your game and the server. Sable sub level lighting keeps working thanks to a compatibility fix, and config/fml.toml now tells Sable to accept it.
- Catalyst, client side Create optimizations: belt items, fluids, machine items and block entities render with less detail or stop rendering at a distance, Blaze Burner smoke is lighter and repeated machine sounds are limited.


# Skybound SMP Season 2, v2.30

Added:
- Skybound Client Patches, client side FPS fixes: Protection Pixel armor stands no longer scan every block entity each frame, boiler hiss sounds are limited to nearby boilers, Veil GPU debug labels are off, Create: Tracks wheels stop rendering past 128 blocks, Sound Physics uses lighter settings once per install (you can change them back in its menu) and Cable Facades skips its lookup when there are no facades nearby.

Removed:
- Async Particles. It made every sound wait for its particle threads, which cost more frames than it saved.
- FastBoot and GPUTape, they did nothing (FastBoot only printed log lines, GPUTape's fix never ran and gpumemleakfix already covers it).


# Skybound SMP Season 2, v2.29

Added:
- CBC Modern Warfare is now craftable: medium cannons, rotary cannons, gun launchers, rockets, torpedoes, ERA and composite armor. Infrared seekers, APDS and HE autocannon rounds stay uncraftable.

Removed:
- Sauce Delight.

Fixed:
- Menus now follow your GUI scale instead of forcing their own, and the title screen cloud frame no longer repeats on large or ultrawide screens.
- An interrupted update could leave the game marked as up to date with no Update button, so you could not join the server. The updater now only marks the version once the update finishes cleanly, and repairs installs that got stuck.


# Skybound SMP Season 2, v2.28

Removed:
- Create: Cosmonautics, and its Deep Seas bridge (Cosmonautics Deep Air). The Moon and Deep Space dimensions are gone with it.
- Aeronautics: Interstellar Expansion (AeroIE).
- Creatures and Beasts.
- Let's Do Furniture. Create Furniture Seats stays.

Fixed:
- Main menu and updater screens now scale to any resolution, aspect ratio and GUI scale.
- Updating through the .mrpack (Modrinth App, Prism, CurseForge import) no longer resets your keybinds and video settings.


# Skybound SMP Season 2, v2.27

Added:
- Create: Ship Glue: crouch and right click with Super Glue or Honey Glue to glue a whole ship at once.
- Create Aeronautics: Explosion Physics: explosions now push ships instead of only breaking their blocks.
- Sable View Distance: ships stay visible out to your view distance.
- Create: Blueprinted: render any schematic to an isometric PNG with one click.


# Skybound SMP Season 2, v2.26

Fixed:
- Falling Oxide cement no longer throws a ticking entity error on the server.
- Re-packagers process crafting order packages again.

Changed:
- Create: Schematic Checker updated to 2.27.47.
- FTB Chunks updated to 2101.1.22.
- Added Create: FTB Chunks Compat on the server: drills, saws, Schematicannons, Super Glue, contraptions and machine settings now respect FTB Chunks claims. Item logistics and rotation still cross claim borders as before, and Redstone Links still talk across claims.

Removed:
- Create: World of Colors.
- CC: Aeroworks.
- Create: Rolling Tones.


# Skybound SMP Season 2, v2.25

Fixed:
- The game no longer crashes on launch with TFMW. The Factory Must Grow Community Edition blocked TFMW, it now loads with a patched TFMW made compatible with the Community Edition.
- Surface Scanners use the Community Edition detection again (they no longer show TFMW Oil Rock deposits).

Changed:
- Create: TFMG Community Edition updated to 1.3.1 (coke ovens work again, light bulb redstone intensity control, cable connector mode on the multimeter).
- The Update button on the title screen now only appears when a newer version is available, and the latest version is checked live.


# Skybound SMP Season 2, v2.24

Added:
- Create: The Factory Must WORK (TFMW) 1.1.0: bug fixes and new content for The Factory Must Grow (Boiler multiblock, Oil Rock, fuel explosions and burning fluids). Oil deposits stay infinite as before.
- Create: Security Program 2.01: card readers, card inscriber, ticket gates and train tickets.
- CC-Aeroworks 1.3.3: ComputerCraft peripherals for Aeroworks.
- Oxide 0.2.0: industrial decay building blocks (corrugated iron, cement, cinder and clinker bricks, rebar, paint).
- Create: World of Colors 1.3: paint fluids to dye blocks and items with Create filling and mixing.
- Create: Rolling Tones is back (client side train and vehicle sounds).

Changed:
- Distant Horizons updated to 3.3.2.
- SSRD updated to 1.8.7 (beta), fixes sub-level rendering with the new Distant Horizons.
- Vista updated to 5.5.7.

Credits and thanks to Novi1i for telling me about TFMW, the Create: Security Program mod and Oxide.


# Skybound SMP Season 2, v2.23

Changed:
- Sable Cleanup Tools replaced by Sable Watch, a staff tool for Sable sub-levels that also measures how much server time each one costs. All existing sub-level data is kept.

Fixed:
- Sub-levels no longer hit an invisible ceiling around y1510.
- Tablecloth shops: small sales (1 and 2 euro) now reach the seller in full, VAT is rounded down.


# Skybound SMP Season 2, v2.22

Added:
- EntityJS 1.5.0 (groundwork for custom bosses).

Removed:
- Create: Mind the Gap
- Create Simurail
- Create Smart Diesel Generator (Create Diesel Generators stays)
- Simulated Coasters and Coasters Engineered
- No Elytra Boost
- Create Assembly Animation
- Fast IP Ping

Blocks from the removed mods are gone from the world.


# Skybound SMP Season 2, v2.21

Added back:
- SimplyTooltips 0.1.5 (client side). Legendary Tooltips stays out.


# Skybound SMP Season 2, v2.20

Cleanup update: 20 mods removed, 2 added.

Added:
- Skybound Extras 1.0.0. Small server utility mod.
- World Spawn 0.2.1. World Spawner block that moves the world spawn along with a Sable sublevel.

Removed:
- Ender Storage. Placed ender chests and their shared inventories are gone.
- Create: Things and Misc, Create Alerted, Industrial Immersive Blocks, Create Integrated Farming and Create Factory Metrics. Their placed blocks disappear from the world.
- Sable Pathfinder and World Backup.
- Client side: SimplyTooltips, Legendary Tooltips (with Iceberg and Prism), MineMenu, Visuality, CreativeCore, Instaload, Easy Mob Spawn Control, FTB Essentials, Aeronautics Wind Sound and Rolling Tones.
- The "Install MineMenu" button is gone from the updater screen.

Recipes:
- Crushed magma no longer exists, magma blocks crush only into sulfur.


# Skybound SMP Season 2, v2.19

Performance update for Create factories.

Added:
- StellarCreateOptimization 1.0.6. Cuts CPU and rendering cost in large Create builds: belts, chutes, encased fans, pumps, crushing wheels, steam engines, fluid tanks, factory panels and chain conveyors. Most of the gain is client side FPS around big factories, and the server also ticks those machines cheaper.

Server side only, nothing to install:
- Sterilization Fixer was removed from the server. It rewrote unknown blocks to air with no way to preview the change, and some of those blocks belong to mods that are only temporarily downgraded.


# Skybound SMP Season 2, v2.18

Create Train Utilities is back in the pack.

Added:
- Create Train Utilities 3.1.0, removed in 2.17, back by request. Train doors and the rest of its train blocks work again.


# Skybound SMP Season 2, v2.17

Biomancy and its Create add-on Bio-Factory join the pack, along with Assembly Animations, High Skies and CreateFix. Seven mods are gone.

Added:
- Biomancy 2.9.8.5.
- Create: Bio-Factory 0.6.1.
- CreateFix 1.8.1.
- Create: Assembly Animations 1.0.1 (client side).
- Create: High Skies 0.1.0.

Changed:
- Create: Power Chip updated to 2.1.1.
- The Primordial Cradle can no longer be crafted.

Removed:
- Immersive Armors.
- Fancy Entity Renderer.
- Create Train Utilities.
- Create More: Parallel Pipes.
- ChoiceTheorem's Overhauled Village. Villages already generated will lose their modded blocks.
- Saro's Road Blocks. Saro's Road Signs stays in the pack.
- Computationally Expensive.


# Skybound SMP Season 2, v2.16

Vista and Distant Horizons back to their previous versions, Create: Estrogen added, and bee-free honey now comes out of a mixer as fluid.

Added:
- Create: Estrogen 2.0.0.

Changed:
- Vista reverted to 5.4.4.
- Distant Horizons reverted to 3.2.0-b.
- Sugar (x3) + slime ball in a Create mixer now gives 250 mB of honey fluid instead of a honey bottle. Fill bottles with a spout.
- Honeycomb is now made in a Create mixer from paper + 250 mB of honey.


# Skybound SMP Season 2, v2.15

Distant Horizons updated so it works with Vista again.

Changed:
- Distant Horizons updated to 3.3.1 (Vista 5.5.6 requires 3.3.1 or newer).

---
Older versions: see changelog_archive.md in the pack repo.
