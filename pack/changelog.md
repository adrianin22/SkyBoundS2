# Skybound SMP Season 2, v2.70

Fixes:
- Fixed a crash on AMD graphics when the new clouds load.
- Train tracks no longer turn invisible.
- Let It Walk and Walker Pistons items show in JEI again.
- JEI now uses the pack's settings on new installs.

Changes:
- APHE and Canister medium cannon cartridges can now be made.
- HE and APHE rockets are now crafted with packed gunpowder.
- APDS autocannon rounds can no longer be crafted.
- Cerisene can no longer be refined into oil products, napalm or biodiesel.
- Clouds now sit higher, at Y 300.
- Title screen shows the vanilla panorama and Minecraft logo again.
- Audio dependencies for radios install automatically.
- Contract Board rewards lowered, global contracts need much more.


# Skybound SMP Season 2, v2.69

Fixes:
- Fixed a crash on startup (KubeJS TFMG).
- LittleTiles rolled back to the previous build, the newer one crashed the server.


# Skybound SMP Season 2, v2.68

Added:
- Create: Engine Engineer (build your own engines).
- Contract Board, daily personal, global and team delivery contracts that pay spurs.
- Command menu, open /commands for a clickable menu of every command you can use.
- Invisible Block, a solid block you cannot see, for builds.
- Willow and flowering willow wood sets.
- Create Offroad: Narrow Roads (compact wheel mounts for small cars), credits to Novi1i.
- Create: Skys (3D clouds and local storms).
- Create: Oxidation (Create copper machinery now oxidizes, can be waxed and scraped).
- Living Wind, LittleTiles Create compat, Walker Pistons, Create Airspace, Deco Illuminated.
- Pantographs and Wires (with Spanish cantilevers), Linear Engineering, Infinite Railways.
- Giant Cogwheels, Create Lighting, World Wide Power Grid, Schematic Folders (client).
- Lift n Load is back.
- Let It Walk is back with Skybound recipes.
- New pets.
- pctype API on every computer: pctype.get() returns "tablet", "pocket", "turtle" or "computer".

Removed:
- Create: Step Up, replaced by Let It Walk. Its blocks and items are gone from the world.

Fixes:
- Performance and bug fixes for Sable ships, MALAHIT, Tracks+ and CBC Modern Warfare recipes.
- Fixed collisions with distant contraptions.
- Going Ballistic rolled back to 0.3.1, shells fly like before.
- Removed old unused textures and files, smaller download.

Changes:
- Loconautics updated to 0.1.3 (train performance fixes), experimental features enabled (boilers, diesel, industrial fluids, screw link, handbrake).
- 60+ mods updated.
- Recipe and JEI cleanups.


# Skybound SMP Season 2, v2.67

## Fixes
- When Mojang's login servers fail, the disconnect screen now shows a short message instead of a whole web page, and always has a Back to Title Screen button.


# Skybound SMP Season 2, v2.66

## Performance
- Gun animations from NTGL now only update for guns that are actually on screen, and leftover data from dead entities is cleaned up. Big FPS gain around many armed players and mobs.
- Sandevistan no longer costs FPS while it is not active.
- New toggle in Video Settings to switch the Create Ice Cream graphics preset between Performance and Balanced.
- Fewer lighting updates from lights on moving contraptions.
- Dynamic lights now use the fastest update mode.

## Fixes
- Copycat Casing no longer makes the blocks behind it disappear.

## Changes
- Liquid Hydrogen thrusters are stronger (thrust 2.3x to 3.0x), it now beats kerosene.
- Standing in Liquid Hydrogen freezes you, faster than powder snow. Leather armour still protects you from the damage.
- Heavy Water mixing now uses an iron nugget instead of an Ender Pearl.
- Loconautics blocks and items now have dye colour tags.


# Skybound SMP Season 2, v2.65

Added:
- Copycat Casing (Skybound Extras): encase shafts and give them the look of any block.
- Heavy Water.
- Liquid Hydrogen has its own textures and bucket, and more thrust.
- Chromatic Compound, Shadow Steel and Refined Radiance are craftable again.
- Create Submarine floaters can be picked up with sneak and wrench.

Removed:
- Easy NPC. Station NPCs and their shops are gone.
- FTB Quests. The quest book is gone.
- Biomancy, Biofactory, Hemodynamics, Cluttered, Voxelized Furniture, Januszowo Clothes, Saros Road Signs, Display Delight, Droingo's Harpoons, Sticky Wheels, CC Graphics, Local Expanders, Create Blueprinted, AeroEngine, Sable Scale, Space Compat. Their blocks and items are gone from the world.

Better FPS:
- Added Vanillin, Create IceCream, GeckoLib Better FPS, PartiCull and Create Tick Control.
- Removed Create FPS Optimizer, Create Better FPS, Saturn, Noisium, ZFastNoise, AI Improvements, SSRD, Irisveil and Colorwheel.


# Skybound SMP Season 2, v2.64

Added:
- Create: Step Up, mechanical legs for Create Aeronautics builds. Its items are not craftable yet.
- Liquid Hydrogen: freeze TFMG hydrogen in a steel vat with freezers and burn it in thrusters.
- Steel vats can split water into hydrogen and oxygen, and freeze oxygen into thruster oxidizer.
- High Skies gas cells now accept TFMG hydrogen.

Fixes:
- Fixed Quantum Tuner cooldowns (Chromeware).
- Fixed cyber arms with TACZ guns (Chromeware).
- Fixed some Create Food, Addictives and Create Teleporters recipes failing to load.
- Fixed the undyed Industrial Cogwheel not being dyeable (Create: Dreams and Desires).
- Some gameplay blocks that could not be broken can now be mined.

Changes:
- Chromeware updated to 1.2.1.
- Sable Watch updated to 1.2.1.


# Skybound SMP Season 2, v2.63

Added:
- Create: Loconautics, Create trains now run on Sable ships.

Fixes:
- Fixed Vista TVs crashing the game when playing a video (WaterMedia 3.0.1).
- Video playback on Vista TVs loads in the background again with the new WaterMedia, no freeze when the first TV starts.
- Fixed server stutter when Sable ships move near unloaded chunks.
- Less server lag from Create: Tracks vehicles and Hose Pulleys.
- Chat names and prefixes cost less server time.


# Skybound SMP Season 2, v2.62

Added:
- Kerria, faster animated textures (client).
- Jasione, less memory churn and fewer lag spikes from garbage collection.
- Create: Smart Bounds, Create machines skip rendering when they are off screen (client).

Removed:
- Uncharted Seas, Create: Integrated Farming and SN Assets. Their blocks and items are gone from the world.
- Glaidens Vista Improvements (client).

Fixes:
- Fixed missing depth on the Create Lanterns flight aura and Lodestone effects shown on Vista TVs.

Changes:
- The Fishing Net from Create: Integrated Farming now comes with Skybound Extras and works the same, also on Sable ships. Nets placed before are gone, craft new ones with the same recipe.
- Create machines hidden behind walls no longer run their animations on your screen, and Create: Tracks suspension updates less often far away, for better FPS.
- Stack Upgrade Tier 1 can be crafted again.
- Weavers Paradise cosplays and the player plushie are now crafted instead of found in chests. Rename a plushie with a rename token to change its skin.
- The Simulated Rubies Chunk Loader is back in JEI and craftable, placing it is still restricted.
- The Create: Gadgets and Gizmos Smart Vault is no longer available.


# Skybound SMP Season 2, v2.61

Removed:
- Trackwork, Let It Walk, Let It Walk Remote and Create: Construction Site. Their blocks and items are gone from the world.


# Skybound SMP Season 2, v2.60

Added:
- Trackwork, tank style tracks for your contraptions.
- Car Horn, a block that honks on a redstone signal and follows moving ships.

Removed:
- Mekanism, Mekanism Generators and their addons. Their blocks and items are gone from the world.

Fixes:
- Industrial Hellscape blocks now use their connected textures.

Changes:
- Recipes that needed Mekanism items were removed or reworked. Logic Mechanism, Processor and Guidance Mechanism no longer need control circuits.


# Skybound SMP Season 2, v2.59

Added:
- Create: Construction Site, Create: Lightworks, Aero Fuel, Let It Walk, Let It Walk Remote Control and The Block of Sky.
- Create: Integrated Farming is back.
- Omni Speed Controller, a block that combines two large cogwheels with a rotation speed controller.

Removed:
- Gadgets and Gizmos no longer has the Gyro Redstone Bridge and the Virtual Orientation Source. Its blocks and items are gone from the world.

Fixes:
- Elevators and other Create contraptions no longer vanish at a distance.
- Double name tag on players wearing a mantle.
- Stack Upgrade Tier 1 can be crafted again.
- Creative only items no longer show up in JEI.
- Startup warning screens and the extra config buttons on the main menu are gone.

Changes:
- Most mods updated, including Gadgets and Gizmos 2.0.0 and Industrial Hellscape 1.3 with new blocks.
- Balance: AeroEngine jets, kerosene and hydrogen thrusters, Water Thrusters and tier 3 and 4 Gadgets and Gizmos propulsion upgrades are weaker, Ion Thrusters use more power and lose their multiblock thrust bonus. Existing ships may need more engines to fly.


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

---
Older versions: see changelog_archive.md in the pack repo.
