# Skybound SMP Season 2, v1.89

Fixed the update that never finished, the one that left the launcher sitting on
"downloading the modpack" instead of starting the game.

What was happening: the update package carried the updater's own program file. Windows keeps
that file locked while the updater is running, so it could never be written, and the updater
kept seeing it as a file that was still out of date. That single file made it give up on the
quick update and re-download the entire 1.2 GB pack instead, every version, forever. Updates
again download only the files that actually changed, which is a few MB on a normal release.

New installs get a rebuilt updater as well: it never tries to overwrite itself, one file it
cannot write no longer cancels the whole quick update, and it prints download progress in the
console so a long download no longer looks frozen.

You do not need to reinstall. The fix above works with the updater you already have. If you
want a completely clean instance, or the rebuilt updater, use the installer again.


# Skybound SMP Season 2, v1.88

Kosmo, the custom space add-on, gets a big fix and a new world.

Fixed: Kosmo was painting its space star field over the sky of the Overworld and of every
other mod's dimension. Nights looked like deep space, planets hung over them, and the
vanilla sun was replaced everywhere. Kosmo now only draws the skies it owns, so the
Overworld and every other dimension are back to their own sky, sun, moon and stars included.

Added: Venus. A new dimension with its own terrain, coronae and lava lakes, the longest
channel in the system, and its own blocks and ores.

Added: Mars ores, and ore veins across Kosmo's worlds no longer generate far too thickly.


# Skybound SMP Season 2, v1.87

Hotfix for v1.86, which could not start.

NeoForge is now 21.1.248 (it was 21.1.238). The launcher updater bumps your instance for you.

Six mods from the v1.86 mass update were rolled back, the ones the NeoForge bump does not fix:
- Bits and Bobs 2.2.9 -> 0.0.44, Create More Girder 2.3.0 -> 2.2.0 and Jaden's Nether
  Expansion 2.4.1 -> 2.4.0-RC.2 (their newest versions need library mods this pack does not ship).
- Photon 2.2.5 -> 2.1.5 and AeroIE 1.0.1 -> 1.0.0-hotfix2 (version mismatch between the two).
- GPUBooster 1.3.2 -> GPUTape 1.0.3 (the newer one crashed on startup, missing library).

Create Crafts & Additions, Supplementaries and Forgified Fabric API keep their v1.86 versions,
they work now that NeoForge is 21.1.248. Everything else from v1.86 is unchanged.


# Skybound SMP Season 2, v1.86

Added:
- Kosmo: a new custom addon with moon ores, titanium, and more (custom mod, work in progress).
- Abyssal Decor.

Updated:
- Industrial Hellscape 1.1.1 -> 1.1.94.
- Mass mod update: 97 other mods bumped to their latest compatible version.

Removed:
- StasisMod.


# Skybound SMP Season 2, v1.85

Added:
- The Mechanical Chicken now also produces feathers (about 50% chance) and leather (about 10% chance) alongside its eggs each cycle.
- Crafting recipes for the Legendary Monsters spike traps (small and big), which previously had none.


# Skybound SMP Season 2, v1.84

Removed:
- Click Signs is removed (it was crashing the dedicated server).


# Skybound SMP Season 2, v1.83

New mod:
- Click Signs, create custom highway and street signs for city building with customizable text and colors.
Removed:
- Creative Mode Tweaks is removed.


# Skybound SMP Season 2, v1.82

New mods:
- Create: Computationally Expensive, adds compute power into Create: Power Grid.
- Create: Mechanical Chicken and Create: Mechanical Cow, kinetic egg and milk generators.
- Create: Backtank Trims & Dyes, cosmetic trims and dyes for backtanks.
- Create: FPS Optimizer, a client-side render optimizer for Create contraptions.
- Creative Mode Tweaks, quality-of-life tweaks for creative mode.
Removed:
- Simulated Coasters and its add-ons (Coasters Engineered, Coasters Magnetized) are removed for now.
- Coaster blocks already placed in the world will show as missing until coasters return.


# Skybound SMP Season 2, v1.81

Mod removals:
- Removed Northstar Redux (the space dimensions mod) and its Aeronautics add-on (AeroStar), plus the Northstar Curios compat.
- Removed Create Aeronautics FTB Chunks compat.
- Anything built inside the Northstar dimensions will no longer be reachable.
- The Eclipse Alloy Mechanism no longer has a recipe (it used Northstar parts); the Mekanism-key tree is unaffected in progression outside that branch.
Server restart needed for this to fully take effect.


# Skybound SMP Season 2, v1.80

Mob change:
- Removed Alex's Mobs. It was causing repeated server ticking crashes (froststalker), so it has been taken out for everyone.
- Any Alex's Mobs creatures or blocks already in the world will disappear. Citadel stays (other mods use it).
Server restart needed for this to fully take effect.


# Skybound SMP Season 2, v1.79

Updater:
- The update screen is back. When you launch and the pack needs updating, you now see a window with a progress bar and a status line instead of a silent wait.
- It shows real progress for both the small incremental updates and the full first-time download.
No gameplay changes, and no server restart needed.


# Skybound SMP Season 2, v1.78

Compass fix:
- Fixed lodestone compasses pointing the wrong way when the lodestone is placed on a ship (sublevel). Attune a compass to a lodestone on your ship and the needle now tracks it correctly as the ship moves, whether you are standing on the ship or watching from the ground.
- Note: attune the compass AFTER the lodestone is part of the ship. A compass locked to a lodestone before it was assembled still points at the old spot.
Server restart may be needed for this to take effect.


# Skybound SMP Season 2, v1.77

Dimensional Drive fix + shaders:
- Fixed the AeroStar Dimensional Drive not detecting your ship's altitude, so ships never left for space. It now reads the correct Sable ship and transfers it once you reach the required altitude.
- Added a set of shaderpacks (Complementary, Solas, Noble, Photon, Rethinking Voxels, Aurora's, Miniature) to your shaderpacks folder. Enable one in Video Settings > Shaders if you want; off by default, your own selection is never overwritten.
Server restart may be needed for the drive fix to take effect.


# Skybound SMP Season 2, v1.76

Lodestone compass fix:
- Fixed the compass needle pointing in a fixed wrong direction when the lodestone it tracks is placed on a Sable ship or sublevel. The needle now points to where the ship is actually rendered in the world, not to its anchor spot.
- This also keeps the earlier fix for using the compass while standing on a ship.
Client only, no server restart needed.


# Skybound SMP Season 2, v1.76

Lodestone compass fix:
- Fixed the compass needle pointing in a fixed wrong direction when the lodestone it tracks is placed on a Sable ship or sublevel. The needle now points to where the ship is actually rendered in the world, not to its anchor spot.
- This also keeps the earlier fix for using the compass while standing on a ship.
Client only, no server restart needed.


# Skybound SMP Season 2, v1.75

New content, four additions:
- Create: Blocks & Bogies. New train blocks and bogies for Create and Steam'n'Rails builds.
- Coasters: Engineered. Buildable roller coasters that tie into Create.
- Create: Schematic Checker. Shows the exact materials a schematic still needs before it can print.
- Dashpanels: Expanded. More dash panels and movement options on top of the base Dashpanels mod.


# Skybound SMP Season 2, v1.74

- Fixed the lodestone compass on Sable sub levels. While standing on a sub level the needle was stuck pointing a fixed direction instead of tracking the lodestone; it now points to the correct block. Overworld and normal use are unchanged.


# Skybound SMP Season 2, v1.73

- Reworked how you unlock Mekanism. The Mekanism Research Catalyst now has a full custom crafting tree built from Create: Many More Mechanisms cores: five top-tier mechanisms (Industrial, Factory, Arcane, Primal and Pioneer) each assembled from parts across the pack's Create add-ons.
- The Research Catalyst finally has its own item icon.


# Skybound SMP Season 2, v1.72

- Removed Mobs of Mythology. If you had any of its mobs or blocks placed, they will disappear.


# Skybound SMP Season 2, v1.71

- Removed the default recipes from Create: Many More Mechanisms; the pack will provide its own recipes for those items.


# Skybound SMP Season 2, v1.70

- Added Create: Many More Mechanisms, a Create add-on with extra mechanical blocks and gadgets.


# Skybound SMP Season 2, v1.69

- Swapped the Create Northstar bridge (cnbridge) for AeroStar, patched to work with Create Northstar Redux. This enables the Dimensional Drive to travel to the planets. If you hit a one-time crash right after updating, relaunch.


# Skybound SMP Season 2, v1.68

- Switched Create: The Factory Must Grow to the Community Edition (1.2.4b), a bug-fix fork. Your factories and recipes carry over.
- Removed the Fix TFMG Controller add-on: it is incompatible with the Community Edition (which reworked the engine controller) and would crash the game. The engine controller now behaves as it does in stock TFMG CE.


# Skybound SMP Season 2, v1.67

- Fixed the charcoal dust split from v1.66: Create Ironworks charcoal dust no longer shows up on the Crushing Wheel. The Crushing Wheel now gives only Create Gunsmithing charcoal dust, and Create Ironworks charcoal dust comes from the Millstone.


# Skybound SMP Season 2, v1.66

- Charcoal dust processing is now split across machines so each mod's dust has its own path. The Crushing Wheel and the Millstone each produce their own charcoal dust. Mekanism charcoal dust now needs an extra step: press Charcoal into Pressed Charcoal first, then crush the Pressed Charcoal. New item added: Pressed Charcoal.


# Skybound SMP Season 2, v1.65

- Fixed the in-game updater so it only updates when you press Update in the main menu. Before, an interrupted or failed update could leave it re-running on every launch; now each Update press is a single attempt.


# Skybound SMP Season 2, v1.64

- Removed Undead Unleashed. Wraiths and dreadknights were flooding the world and crowding out other mobs; the mod is now gone so you should see much more mob variety.
- Fixed Tiny Create so it can run again (patched a crash when saving a Redstone Link frequency that had an enchanted item).
- Added Starcatcher's Delight (a Farmer's Delight add-on).


# Skybound SMP Season 2, v1.63

- Faster updates: the updater now downloads ONLY the files that changed (via HTTP range + CRC32), instead of the whole ~1.2GB pack every time.
- The updater now also sets your instance NeoForge to 21.1.238 automatically (only bumps up). If the game crashes once right after this update, just launch again.


# Skybound SMP Season 2, v1.62

- Updated JEI (Just Enough Items) to 19.44.0.403 (latest for 1.21.1 NeoForge).


# Skybound SMP Season 2, v1.61

- NeoForge updated to 21.1.238. IMPORTANT: set your instance NeoForge to 21.1.238 (Edit Instance > Version > NeoForge) or the game will not launch.
- Added Create: Hammer (BID) auction house, Create: Sulfuric Resonance, and player ragdolls.
- Removed Copper Age Backport (copper armor material is now native at 21.1.238).
- Fixed TrafficCraft recipe type registration so it loads on 21.1.238.


# Skybound SMP Season 2, v1.60

- Removed Water Pressure (underwater pressure damage).


# Skybound SMP Season 2, v1.59

- Removed Opal Light (colored dynamic lighting).


# Skybound SMP Season 2, v1.58

- Added Opal Light (colored dynamic lighting).
- Disabled all Create: Hypertube crafting recipes.


# Skybound SMP Season 2, v1.57

- Added four Create add-ons: Create: Hypertubes, Create Big Cannons: Going Ballistic, Create Aeronautics: Gadgets & Gizmos, and Create Aeronautics: Compatibility.
- Removed Portalium.


# Skybound SMP Season 2, v1.56

- Hotfix: reverted a Skybound Numismatics change that could crash the game while loading. Everything else from v1.55 (removed Create: Bionics, All Tutta's Needs and High Seas; added Connected Textures Mod; recipe tweaks) is unchanged.


# Skybound SMP Season 2, v1.55

- Removed Create: Bionics. Its Anole item had a broken renderer that crashed the game whenever the item was shown in a GUI (for example the portable stock ticker search).
- Removed All Tutta's Needs.
- Removed High Seas.
- Added Connected Textures Mod (CTM).
- Recipe changes: the obsidian plate is now sawed first in its assembly, and the brass fluid pipe costs one extra brass ingot.


# Skybound SMP Season 2, v1.54

- Removed the Continuity connected-textures mod.


# Skybound SMP Season 2, v1.53

- Fixed a crash on load for everyone: Create: Gunsmithing 1.4.9 required a newer gun library. Updated NukaTeam's Gun Lib to 3.1.8.


# Skybound SMP Season 2, v1.52

- Fixed a server/client crash on load caused by a Sable version mismatch with Sable Scale. Reverted Sable to the compatible version (2.0.3).


# Skybound SMP Season 2, v1.51

- Updated ~70 mods to their latest compatible versions (Create add-ons, content, performance and libraries).
- Added Sable: Water Pressure and Create: Ironworks.
- Updated Sable (airship physics) to 2.0.5.
- Fixed a client crash caused by a bad Create Gunsmithing build (replaced with the normal build).
- Removed Bandwidth Optimizer (it was causing block and entity desync).


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

---
Older versions: see changelog_archive.md in the pack repo.
