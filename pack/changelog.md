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

# Skybound SMP Season 2, v1.16

## Fixed
- Fixed the KubeJS startup errors on the main menu. The custom Mekanism chemicals (Helium-3, Refined/Unrefined Stellarite, the silica and rare-metal slurries), the Artificial Void fluid and the Stellarite blocks were using an old KubeJS/Mekanism API that no longer exists on the current versions, so they failed to register and their recipes were broken. Rewritten against the current Chemical registry.

# Skybound SMP Season 2, v1.17

## Added
- Puddles & Floods: rain now pools into puddles and can cause light flooding.
- Immersive Aircraft plus the Better Engines, Civilian Aviation and Man of Many Planes addons, restyled to fit Create via the Create Immersive Aircrafts resource pack and matching recipe overhaul (Create-themed recipes and textures for every aircraft).
- Immersive Furniture: build custom furniture and decor in-game.
- Immersive Vehicles plus Create: Automotives (Create-powered cars) and the official traffic Sign Pack.
- Create: Compact Gearbox Transmission: compact multi-ratio gearboxes with manual and wireless shifting.

# Skybound SMP Season 2, v1.16

## Added
- Respawning Structures: dungeons and structures regenerate automatically after a set time, so groups can farm the same dungeon again instead of it staying looted forever.
- Terrain Slabs: smoother terrain generation using slabs (new chunks only, does not affect already-generated terrain). Includes an optional bundled resource pack for alternative grass-slab textures, enable it yourself in Options > Resource Packs if you want it.

# Skybound SMP Season 2, v1.15

## Fixed
- Fixed the server error when right-clicking a Create: Radar Monitor block (swapped to a build with the dedicated-server and Sable compatibility fixes).

# Skybound SMP Season 2, v1.14

## Changed
- Reworked the KubeJS recipe scripts across the pack.
- Removed the experimental Create-gated machine progression. Machine recipes are back to their standard form.

# Skybound SMP Season 2, v1.13

## Fixed
- Fixed the crash on the title screen (removed Borderless Window, it conflicted with the custom menu).
- Wind no longer lifts loose blocks or shoves builds sitting on the ground during storms. Ground wind was toned down further.

## Changed
- Re-added the loading screen so the main menu only appears once everything (including the custom menu) is fully loaded.
- Create progression overhaul v2: gated machine recipes now ADAPT to each machine. Ingredients depend on what the machine does (grinding, fluids, logic, power, transport) and on how powerful it is, using a much wider range of Create parts. Stronger machines demand rarer endgame materials.
- Signature alloy matrices are now made through different Create processes (mixing, compacting, sequenced assembly) instead of one.

# Skybound SMP Season 2, v1.12

## Removed
- Drippy Loading Screen (client), HoloMap, Sable Photomancy, Towers of the Wild: Modded, Wan's Ancient Beasts and Concentration.

## Added
- Borderless Window (client), a borderless fullscreen mode with no flicker when alt-tabbing.

# Skybound SMP Season 2, v1.11

## Changed, Create progression overhaul
- Every gated tech machine (Mekanism, Immersive Engineering) now has a UNIQUE recipe. The old shared filler is gone, so no two machines craft the same way anymore.
- New progression parts: tier cores, role modules and branch signature materials (Infused / Reinforced / Atomic Alloy Matrix, Engineered Circuit Board, Heavy Field Coil), most built through multi-step Create assembly.
- The Mekanism alloy line now runs through Create: alloys feed the signature matrices, and Infused Alloy now needs a pressed copper sheet to start.
- Top-tier machines demand rare endgame materials (Nether Stars, Netherite blocks, Echo Shards, Dragon's Breath, End Crystals and more), varied per machine.
- Ore doubling must go through Create crushing first, and the Mekanism raw-block shortcut was removed, so ore processing is no longer trivial.

# Skybound SMP Season 2, v1.10

## Added
- MineMenu, a client radial menu for keybinds, commands, and quick actions.

## Changed
- Wind now pushes physics sub-levels much less at ground level. Surface friction reaches up to Y 120 so builds sitting on terrain or on mountains stay put; only vehicles that climb above that height catch real wind. Hull drag and the wind acceleration cap were also lowered.

# Skybound SMP Season 2, v1.9

## Added
- Psi (magic tech spellcasting), with Patchouli
- Tiny Gates
- Tiny Create (bridges Tiny Redstone with Create's analog components)

## Changed
- Space content now runs on Create: Cosmonautics again (Create: Northstar and its bridge were removed).
- Weather2 storms are less frequent and their wind pushes physics sub-levels less.
- Fixed a duplicated Forgified Fabric API that could block joining the server.

## Removed
- Oritech and its Create gate recipes
- Sable Destructive

# Skybound SMP Season 2, v1.8

## Changed
- Reworked the Create-centric gate crafts. Every Mekanism, Immersive Engineering and Oritech machine now keeps its original ingredients merged with deep Create crafting, unique per machine, with no duplicated recipes.
- Removed unobtainable Create items (refined radiance, shadow steel, chromatic compound) from every gate recipe.
- Added five role modules (grinding, reaction, capacitor, turbine, precision) and reworked the tier cores.

## Added
- Create: More Girder
- Tiny Redstone
- HT's TreeChop
- Droingo's Harpoons
- Rechiseled and Rechiseled: Create (with SuperMartijn642's Core Lib and Fusion)

# Skybound SMP Season 2, v1.7

## Added
- Create-centric progression overhaul. Mekanism, Immersive Engineering, Oritech and TACZ are now gated behind Create.
- New KubeJS gate items (reinforced, industrial and singularity cores) built with large mechanical crafting.
- Machine recipes for the gated mods now require the matching Create core of their tier.
- Ore processing rerouted through Create: gated machines consume Create crushed ores instead of raw ore.
- TACZ guns rebalanced into 8 power tiers, each requiring Create materials scaled by the gun's power.
- Added mods: KubeJS Mekanism, KubeJS Mekanism Extends, TaCZ JS.

# Skybound SMP Season 2, v1.6

## Removed
- Enderscape (End dimension content mod). Removed to shrink the pack and reduce load.
