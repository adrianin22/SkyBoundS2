# Skybound SMP Season 2, v1.50

- Fixed a crash that closed the game whenever you ordered or received a package (Create: Mobile Packages). It was caused by a Create Fluid Logistics version mismatch; the pack now ships the matching version.


# Skybound SMP Season 2, v1.49

- The updater now shows a progress window when you launch: you can see it downloading and installing, with a percentage, instead of the launcher looking frozen.
- Reminder: the pack only updates when you press "Update" in the menu. If an update is interrupted, it finishes on the next launch on its own.


# Skybound SMP Season 2, v1.48

- Removed Qlobal Translator (voice and chat translation). It is gone from both the client and the server.


# Skybound SMP Season 2, v1.47

- Qlobal Translator: the menu is now in English, the sound on each translated message is gone, and chat translation is now per-player. Open the Qlobal menu and toggle "Chat Translation" OFF to stop receiving translations (your choice is remembered).
- Added Remorphed (with Woodwalkers and CraftedCore): transform into mobs you defeat.
- Added Create: Addictives.
- Fix: the Linked Controller Hub (Drive-by-wire) now drops when broken.


# Skybound SMP Season 2, v1.46

- Removed LinguaChat. It caused client lag and duplicated chat translation with Qlobal Translator (which handles both voice and chat).


# Skybound SMP Season 2, v1.45

- Added Qlobal Translator: real-time voice and text chat translation (offline Vosk speech recognition, speech bubbles, Dababel-style side panel with flags).
- Added LinguaChat: automatic chat message translation.
- Fixed the Mechanical Extruder pole models that caused an FPS drop near extruders. The fix is now built into the mod, so the ExtruderPoleFix resource pack has been removed.
- Restored the Create Haunting recipe for Infested Stone.


# Skybound SMP Season 2, v1.44

- Removed Create Backpack Pixel. It was crashing the server on every tick.


# Skybound SMP Season 2, v1.43

- Added rendering/perf mods: Vira, GPU Tape, MoreCulling, Better Biome Blend, gnetum, Sodium Options Compat, Flywheel OIT Fix, Iris Scale Fix.
- Replaced the old Iris/Flywheel compat with Colorwheel (+ Colorwheel Patcher) for better shader performance with Create.
- Added FTB Quests Optimizer and FastWorkbench/FastFurnace/FastSuite (smoother crafting and quests).
- Added content: Create: Clothes, Protection Pixel, and Create Backpack Pixel.
- Removed PneumaticCraft, More Propulsion, Biome Replacer, Create Aeronautics Automated Logistics, Ambient Environment, Better Grass-ify, Oil Canister, Lift n Load.
- Precision Mechanism and Blaze Burner now use their vanilla Create recipes again.
- Fixed the Mechanical Extruder pole rendering error that caused heavy FPS drops nearby (auto-applied resource pack).


# Skybound SMP Season 2, v1.42

- Removed Cosmetica. It was spawning many background threads and caused severe FPS drops and stutter.
- Replaced Sound Physics Aeronautics with Sound Physics Remastered for stability.


# Skybound SMP Season 2, v1.41

- Added FramedBlocks and Fix Framed Blocks.
- Removed Apex Network (it caused repeated disconnects for clients that had not updated).
- Removed AmbientSounds.
- Removed Vivecraft (VR support).
- Removed KubeJS Visual Recipe Maker.
- Removed Mekanism Nuclear Weapons and Explosives.
- Removed Puddles.
- Removed Vintage Animations.


# Skybound SMP Season 2, v1.40

- Added Connectivity (fixes join/disconnect issues on large modpacks).
- Added Chunk Sending, Fast Async World Save and Structure Essentials (server performance, smoother chunk loading).
- Added Better FPS - Render Distance and Fix GPU Memory Leak (client FPS).
- Removed SpiffyHUD (it caused heavy per-frame HUD overhead and FPS loss).
- Fixed around 1450 broken Create add-on recipes.


# Skybound SMP Season 2, v1.39

- Removed the gnetum mod.


# Skybound SMP Season 2, v1.38

- Hotfix for v1.37: fixed startup crashes and the server connection error.
- Added WaterMedia binaries so Vista video screens work.
- Removed Really Fast Load (was crashing the game on startup).
- Removed Born in Chaos and Create Nuclear (they were blocking you from joining the server).


# Skybound SMP Season 2, v1.37

- New creatures: Creatures and Beasts, Mowzie's Mobs, Myths and Legends, Luminous Beasts, Undead Unleashed.
- New content: Vista (cameras and monitors that can play video via WaterMedia), plus decoration mods (Display Delight, Placeable Items, Portalium, Gradium).
- Added mob spawning control mods and Really Fast Load for faster world loading.
- Removed Chloride (it caused a startup crash together with the new video mod).


# Skybound SMP Season 2, v1.36

- Removed mod: Psi.
- Create Sand Paper is back to its normal recipe (1 paper + sand).
- Sand + an item no longer crafts into suspicious sand.
- Updates no longer overwrite your video (Sodium) and shader (Iris) settings.


# Skybound SMP Season 2, v1.35

- Create Sand Paper now costs a second paper: 2 paper + sand (was 1 paper + sand).


# Skybound SMP Season 2, v1.34

- Big FPS fix for sound: high in-game volume no longer tanks framerate. The audio physics (Sound Physics) was doing very expensive per-sound raytracing; ray counts are lowered and the heaviest experimental effects (multipath, propeller diffraction, per-tick doppler) are disabled. Reverb and occlusion still work.


# Skybound SMP Season 2, v1.33

- Distant Horizons and the FTB minimap no longer get reset every update. Your render distance, LOD quality, minimap layout and related client settings now stay exactly as you set them.
- Mechanical Saw is craftable again (its recipe had been removed by mistake).


# Skybound SMP Season 2, v1.32

- Added **Create: Copycats+ Additions**: extra copycat variants (corner slopes, layered corner slopes, and wall-mounted slope layers).
- **Dimensional Drive** now has a proper recipe: Precision Mechanisms, a Gyroscope, Ender Pearls and Electron Tubes (replaces the old Northstar titanium and computer-chip recipe).


# Skybound SMP Season 2, v1.31

- Removed **Pehkui** (unused entity-scaling library) to cut server-side entity tick overhead.
- Removed **The Roads More Travelled**.
- Fixed **Basic Mechanism** crafting: its sequenced assembly no longer clashes with the Gyroscopic Mechanism. The first deploy step is now Andesite Alloy instead of a Cogwheel, so both are craftable.
- Fixed **Rose Quartz**: restored its crafting recipe (1 Quartz + 8 Redstone). It had no recipe before.


# Skybound SMP Season 2, v1.30

- Added Showcase Item: press Shift + X to show the item you are holding in chat, so others can hover it to see its full tooltip. Great for trading and showing off builds.


# Skybound SMP Season 2, v1.29

- Fixed the pack updater: the download is now checked for completeness and retried automatically, so the modpack no longer fails to download or installs only some of the mods for certain players.
- If an update cannot finish (for example a dropped connection), it now retries on the next launch instead of starting the game with a half-updated mods folder.


# Skybound SMP Season 2, v1.28

- Added **AppleSkin**: shows food saturation and hunger restored in the HUD and tooltips.
- Added **BandwidthOptimizer** and **Apex Network**: network optimizations to cut lag spikes and connection timeouts.
- Removed **NBT Compat**: it was retexturing Create casings (and could break them). Casings return to their normal look.
- Fixed: your **Xaero minimap / world map** settings and waypoints are no longer reset when you update.


# Skybound SMP Season 2, v1.27

- Removed **Create Grappling Hooks**: it crashed clients when a Plunger was rendered on the server. The Plunger Launcher from Create Aeronautics is unaffected.


# Skybound SMP Season 2, v1.26

- Fixed the **Install MineMenu** button: it now just applies the preset instead of opening the update screen. Restart once after clicking to see the radial menu.


# Skybound SMP Season 2, v1.25

- **MineMenu preset is now optional.** Click **Install MineMenu** on the main menu to get the preset radial menu (keybinds and entries). It no longer installs with the update, so your own MineMenu setup is left alone unless you click it.


# Skybound SMP Season 2, v1.24

- Reverted NeoForge back to 21.1.235.
- Removed **Coasters Simulated: Track Styles** (it required a newer NeoForge that broke other mods).
- Coasters: Magnetized and More Wheels stay.


# Skybound SMP Season 2, v1.23

## Engine
- **NeoForge updated 21.1.235 -> 21.1.248.** The launcher will download it automatically on next start.

## New roller coasters and wheels
- **Coasters: Magnetized**, **Coasters Simulated: Track Styles** and **More Wheels** (with the StickyWheels offroad addon).

## Create and Aeronautics additions
- Create Aeronautics: Covers, Radionautics, Sonar, Weight, Aeroclaims, Lift-n-Load, Analog Audio (radios and speakers), and more addons.
- **SSRD**: airships now render far beyond your view distance.
- **Distant Horizons**: you now see far terrain streamed from the server (no local generation needed).
- New airships and aircraft frameworks (Northstar, createaviation, avionics), plus Radar/Sonar and train parts.
- Create Mekanism Compatibility rework, Fluid Logistics, Parallel Pipes, Grappling Hooks.

## Content, decoration and mobs
- Alex's Mobs, Born in Chaos, Mobs of Mythology, Critters and Companions, Starcatcher, Jaden's Nether Expansion, Simply Swords.
- Lots of decoration: Saros road blocks and signs, Ornamentum, Mo-Glass, industrial and immersive furniture, and more.
- Sophisticated Backpacks, PneumaticCraft Repressurized, Storage Drawers.

## Quality of life and clients
- Xaero's minimap and world map, Legendary Tooltips, Chat Heads, Inventory Management, Zoom, Cosmetica, ModernFix, Smooth Boot, world backups.
- **Vivecraft** (VR support) and **Simple Voice Chat**.
- Euro currency for Numismatics coins.

## Gameplay changes
- **Mekanism** is now gated: craft the Mekanism Key by hand to unlock it (per player).
- **Distant Horizons** set to stream from the server; **HighSeas** ocean waves enabled.
- ION thruster thrust reduced to match the standard fuel thruster.
- Alex's Mobs Fly no longer spawns naturally.
- Create Flight Control recipes disabled except the Attitude Display.
- Aeronautics: Interstellar Expansion recipes disabled for now.
- Plunger and Grapple launchers only work in the Overworld.
- Teleporter items removed to keep the Create/Aeronautics logistics focus.
- Main menu locked down (modpack mode).

## Removed
- All guns (TACZ, Elite Guns), keeping Create Gunsmithing.
- Immersive Engineering and the old aircraft/vehicle pack (Immersive Aircraft, Man of Many Planes, Immersive Vehicles, Civilian Aviation, Create Automotives, More Engines, Cosmonautics).
- PMWeather (and its shaders/aeronautics addons), Emotecraft, Vista, SableBeyond, Pondus, Sablewaves, and several tools replaced by newer versions.


# Skybound SMP Season 2, v1.22

## Removed
- **Overeating** - not compatible with dedicated servers (crashed on load).

# Skybound SMP Season 2, v1.21

## Removed
- **Music Maker** - removed by request.

# Skybound SMP Season 2, v1.20

## Added
- **Overeating** - oversaturation system with fat armor and perks.
- **Music Maker** - craftable instruments, sheets and multiplayer bands.
- **Create: Immersive TaCZ Integration** - craft TaCZ guns and ammo through Create.
- **MoreTraffic** + **TrafficCraft** - programmable traffic infrastructure and decorations.
- **Contraption Lights** - dynamic lighting on Create contraptions and Sable sub-levels.
- **CustomNPCs** - in-game NPC creator with dialogue, quests and trading.
- **ProtoManly's Weather** + Aeronautics compat + **PMShaders** - realistic weather and tornadoes.
- **Aeronautics Camera Sync** - camera tilts with Aeronautics contraptions.
- **Storage Drawers** + Create compat - drawers that mount on contraptions.
- **Emotecraft** - player emotes.

## Removed
- **Sable Dynamic Lights** - replaced by Contraption Lights.
- **Weather2** and **Tornado Physics** - replaced by ProtoManly's Weather.

## Changed
- Restored the Create-progression crafting: Mekanism, Immersive Engineering and TaCZ are gated behind Create cores again.

# Skybound SMP Season 2, v1.19

## Added
- **Civilian Aviation** 1.0.2 - civilian aircraft and airliners.
- **Create: Automotives** V2 - Create-powered cars and ground vehicles.
- **Man of Many Planes** 0.2.1 - a wider fleet of flyable planes.
- **More Engines** 3.0.2 - extra engines for vehicles and aircraft.
- **Dense Fuel** 1.0.0 - dense fuel for the vehicle mods.
- **Puddleflood** 1.1.5 - dynamic puddles and rain flooding.
- **Respawning Structures** 4.2 - structures regenerate over time.
- **Terrain Slabs** 3.1.2 - vertical slabs for natural terrain blocks.

These are required by the server, so this update lets everyone connect again.

# Skybound SMP Season 2, v1.18

## Added
- **Immersive Aircraft** 1.4.6 - flyable planes, biplanes and airships.
- **Immersive Vehicles** 24.0.0 - drivable vehicles (formerly MTS).
- **Immersive Furniture** 0.3.0 - craftable decorative furniture.
- **Create Compact Gearbox** 1.0.2 - compact gearbox for Create builds.

These are required by the server, so this update lets everyone connect again.

# Skybound SMP Season 2, v1.17

## Fixed
- Fixed the KubeJS startup crash on dedicated servers and the startup/client error screens: the plutonium/polonium pellet food tweak (item.foodProperties), the JEI item hiding (JEIEvents) and a client lang call all used APIs removed in the current KubeJS. Ported the food tweak to modifyFood, guarded the JEI hooks so they no longer error, and dropped the obsolete lang call.

---
Older versions: see changelog_archive.md in the pack repo.
