# Skybound SMP Season 2, v2.58

Changes:
- Blood effects from Hemodynamics are turned off (no blood from damage, no footprints, no blood rendering).
- Hollowgear boss: new visual effects for its attacks, warnings and death.

Fixes:
- Sounds that stopped playing or disappeared after a while (Doppler).
- Chat translate: pressing the up arrow in chat no longer selects the translate button, and messages from other players are now actually translated.
- A LittleTiles crash on the client.


# Skybound SMP Season 2, v2.57

Changes:
- Chromeware: every cyberware, implant, syringe, immunosuppressant and the surgery chair now need a Create production chain. New components: Neural Chip, Synaptic Processor and Military Neural Core, each made by sequenced assembly. Higher tier implants need higher tier chips. Check JEI for the new recipes.

Fixes:
- Voltworks and Power Grid solar panels had the same recipe, the Voltworks one now starts with rose quartz.
- LittleTiles and CreativeCore missing or duplicated for some players. The updater now removes extra copies of pack mods (for example newer versions added by a launcher mod update) and restores the right ones.
- NeoForge version now really changes to 21.1.259, also for instances that ended up on a newer NeoForge. When the updater changes it, the launch stops with a message: close Prism Launcher completely, open it again and press Play.


# Skybound SMP Season 2, v2.56

Added:
- Create: Chromeware 1.2.0 (Blood Update) with Hemodynamics: cyberware implants for Create. Sandevistan and the System Collapse, Suicide and Blackwall Gateway quickhacks are disabled.
- Beat Lamp: music reactive lamps, lasers and fog.
- Stackable Armor Trims: stack several trims on one armor piece.
- Olaf's Relatively Placed Blocks: place blocks relative to the one you look at.
- Style & Threads and MClothes: new clothing and cosmetics.
- Weavers Paradise: spin thread, weave fabric and dye your own clothing. Its enchantments and clothing abilities are turned off.
- Pocket Malahit Tablet: a pocket tablet for ComputerCraft.
- Immersive Computing with LittleTiles: build ComputerCraft computers out of small tiles.
- ItemSmith (staff tool for event rewards).
- Doppler: sounds change pitch with relative speed (client).
- Chat translation: messages from other players in another language are translated in place, hover to see the original.
- Asphalt slabs, train pavers lay them on slopes and curves when held in the offhand.

Removed:
- Train Utilities. Its platform, line and glass blocks are now part of Skybound Extras.

Fixes:
- Fixed moving and removing Screen Modules with the wrench (DashPanels Extra).
- Better FPS next to tracked vehicles and tanks.
- Contraptions on minecarts and gantries no longer render while hidden behind walls. Elevators and trains stay always visible.

Changes:
- Pets: third skill slot for final forms, 12 new skills and 8 pet effects, rebalanced abilities, new sounds, effects and menu, more idle behaviour, diet shown in the Care tab.
- Lower Create particle and belt item render distances, less lag near big bases.
- NeoForge updated to 21.1.259. The launcher updates it on the next launch; if the game crashes once, launch it again.


# Skybound SMP Season 2, v2.55

Fixes:
- Fixed a crash on startup when your network blocks Microsoft's text to speech service (Create: Tramways). The game now starts normally; train announcements only speak when that service is reachable.
- Fixed a client freeze near large Create builds (Create FPS Optimizer).
- The updater no longer downloads the same config files again on every launch.


# Skybound SMP Season 2, v2.54

Better FPS:
- Better FPS near large Create builds: Create block entities far away are no longer rendered in full (Create FPS Optimizer).
- Better FPS near vehicles with wheels.
- Block models load on demand, lower memory use.
- Enchanted Create machines no longer shimmer.

Removed:
- Optimized Block Entities.
- Sable Xaero Maps, ships are no longer drawn on the Xaero map.
- Functional Sculptures (golem statues). Its blocks and items are gone from the world.
- Memory cleanup after joining turned off.


# Skybound SMP Season 2, v2.53

Removed:
- KeybindsGalore (radial keybind menu).
- Oxide (cement and rusting blocks). Its blocks and items are gone from the world.


# Skybound SMP Season 2, v2.52

Fixed:
- The game crashed on startup after the 2.51 update.


# Skybound SMP Season 2, v2.51

Added:
- Optimized Block Entities (client, faster chests, signs and other block entities).
- Sound Culling (client, fewer overlapping sounds near farms and machines).
- KeybindsGalore (choose which action runs when two keybinds share a key).

Removed:
- Diagonal Fences and Diagonal Windows (lower RAM use and faster loading). Fences and panes already placed stay where they are.
- Quark wooden posts (lower RAM use and faster loading).

Changes:
- Lower client memory use: bundled mods are loaded as separate files, and memory is freed a couple of minutes after joining.
- Psi Add Motion, Mass Add Motion and Mass Exodus tricks are disabled.
- The pack updater was improved.

Fixed:
- The Cogling pet no longer makes a constant gear ticking sound.


# Skybound SMP Season 2, v2.50

Added:
- Calcite can now be selected in the mechanical cobblestone generator.

Fixed:
- Client crash near Create fluid tanks (Stellar Create Optimization).
- The Hollow Waltz music disc now plays in jukeboxes.
- The Dual Wheel Mount drops itself when mined.
- Halloween cosmetics no longer cause server errors and crashes.
- Harvest Album trophies are recorded as soon as you pick them up, so displaying a trophy before using the album no longer loses it.
- The Hollowgear Signal Flare bonus is applied once instead of twice.
- Create machines next to claims no longer show "A claim blocked that Create operation" for linked controllers.
- /sables delete and /sables confirm accept the ship name as well as its number.


# Skybound SMP Season 2, v2.49

Added:
- Visual Creative Tab Editor.

Removed:
- Vanilla Backport spears. They can no longer be crafted or used.
- More Wheels tractor tires. They can no longer be crafted, placed or used.

Changes:
- Create: Lanterns updated to Alpha 20.7.
- The Vanilla Backport locator bar is turned off.

Fixed:
- Modules on DashPanels: Extra panels can be removed with the wrench again.


# Skybound SMP Season 2, v2.48

Removed:
- NextSpace. Its items and blocks are gone.


# Skybound SMP Season 2, v2.47

Fixed:
- The game crashed when joining the server after 2.45. Creative Tab Organizer is removed, it is not compatible with our JEI version.


# Skybound SMP Season 2, v2.46

Fixed:
- The game failed to load after updating to 2.45. Forgified Fabric API is back to 0.116.15+2.3.5 (the 2.3.6 build needs a newer NeoForge).
- Gravity Control no longer stops the game from loading (Lithium entity collision optimization turned off for it).


# Skybound SMP Season 2, v2.45

Added:
- Create: Tramways.
- Gravity Control.
- Aero Dual Mount.
- Create: Trackwright.
- Create Aeronautics: Automated Logistics.
- DashPanels: Extra.
- Creative Tab Organizer.
- Decorative Redstone Link: a block with the redstone link look, made from andesite casing and a redstone torch. It does not carry a signal.

Removed:
- Starcatcher and Starcatcher's Delight.
- Skyport, replaced by Create Aeronautics: Automated Logistics.

Changes:
- 54 mods updated to their latest compatible versions (bug fixes and performance).
- Mechanical Livestock: sheep machines can now drop raw mutton.
- Freeze Staff: range raised to 128 blocks and a new recipe (packed ice and two sticks).
- Drive by Sable: more sources allowed per ship.
- Lodestone compasses work on ships again. Compasses no longer work in the Nether and the End, like vanilla.
- RCS thrusters now show the same stress draw as the server (4 SU per RPM).

Fixes:
- Pilot seats can be used on trains and contraptions.


# Skybound SMP Season 2, v2.44

Changes:
- RCS thrusters: max thrust lowered a lot, and shaft driven thrusters now draw stress from the network (16 SU per RPM).
- Psi: max Psi and regeneration lowered, spells cost twice as much.
- Decorative Levitite blocks now connect their textures.
- Mirrors render at a shorter distance and lower resolution, for better FPS near them.

Removed:
- Create: Flight Control.
- Aeronautics roller fix. Rollers in Tunnel Pave no longer replace the slabs on track slopes with full blocks.

Fixes:
- The Xaero minimap no longer hides while you type on a Tom's Peripherals keyboard.
- Better FPS with girder struts on Fast graphics and while the world map updates.
- The Psi guide book should show its entries again.
- Watcher bat morph is animated now.
- Psimetal Exosuit hidden from JEI (it cannot be crafted).


# Skybound SMP Season 2, v2.43

Added:
- Psi: spell programming with CADs and Psimetal gear.
- MmmMmmMmmMmm: target dummy that shows the damage of every hit.

Removed:
- Critters and Companions. Its animals, blocks and items are gone from the world.

Fixes:
- Create elevators and contraptions should no longer turn invisible.
- Build dimension: the swivel joint part of your ship now counts as yours, you and your plot friends can use it off your plot.


# Skybound SMP Season 2, v2.42

Added:
- 16 dyed Decorative Levitite: decorative levitite + any dye, no lift.

Fixes:
- Fixed a crash when joining the server caused by JEI 19.64 and JEIOptimizer. JEI is back to 19.57.
- Dyed levitite from Aeronautics Dyeable Components lifts ships again.


# Skybound SMP Season 2, v2.41

Added:
- Create Aeronautics: Freeze Staff: right click a ship or contraption to freeze it in place, together with everything resting on it or roped to it, so it stops costing server performance while parked. Right click again to unfreeze. Crafted from blue ice, a precision mechanism and 3 gold ingots.
- Create: Tilting Controls: tilting propeller and swivel bearings, gimbal propeller bearing, linked joystick, bidirectional throttle lever and more compact controls for Aeronautics builds.
- Create: Autonavigation: the Navigation Workbench lets ships steer themselves without being tied to magnetite, works with Create Radar.
- Create: Atomic: nuclear reactors and steam turbines for rotational power, uranium, plutonium and hazmat gear. Uranium ore only shows up in newly generated chunks.
- Create: Teleporters, reserved for the server owner for now.

Removed:
- Immersive Portals.

Changed:
- Camera screen shake effects are back.
- RCS Thrusters from Gadgets & Gizmos are back to their reduced power (140 per nozzle) and twice the backtank air use, this was lost in 2.38.
- Hearth & Harvest 1.4.0: new crops and food (hops, keg, pizzas, pies and more). Cheddar cheese is now regular cheese, elote is now street corn and the grape trellis is now the crop trellis, existing items convert on their own.
- Supplementaries 4.0.1: adds the Pinata.

Fixes:
- CBC Neo Warfare: rotary cannon bearings can be finished again by right clicking them with a shaft, and the nethersteel bearing now gives a nethersteel bearing instead of a steel one.

Mod updates:
- Aero Player Tilt 0.2.3, Aeroportals 1.3.4, AzureLib 3.1.19, Chunk Sending 4.1, Collective 8.47, Contraption Lights 1.5.4, Corpse Curios Compat 4.2.0, Create Central Kitchen 2.6.2b, Create Enchantment Industry 2.5.4b, DragonLib 3.0.29, Drive By Sable 2.0.2, Entity Culling 1.11.3, Framed Blocks 10.6.3, Gadgets & Gizmos 1.2.10, JEI 19.64.0, Kilagraph 21.1.0.16, Mekanism Ponders 1.0.4, ModernFix 5.27.26, Moonlight 3.7.2, Photon 2.2.8, Puzzles Lib 21.1.64, Server Warashi 2.1.1.4, Skyport 1.1.0, Starcatcher 3.3.8, Stellar Create Optimization 1.1.1fix, Streams Reflowing 2.15.0, TFMW CE 2.1.2, Veil 4.5.2, Sable Hose Connectors 0.2.2, XaeroPlus 2.36.6.


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

---
Older versions: see changelog_archive.md in the pack repo.
