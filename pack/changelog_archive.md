# Skybound SMP Season 2, v1.96

The game starts again.

Since v1.91 the pack shipped a modified build of Protection Pixel. That edit is what gives the
wings, jetpack, thruster and the other powered modules real durability, but it left one piece of
class data inconsistent, and the mod could not be created at startup. When that happens the whole
mod loading phase stops, so the game never reaches the main menu and shows a loading error
instead. There is no crash report, which is why it looked like a freeze.

The mod is rebuilt correctly in this update. Nothing about it changes for you: same durability
values, same recipes, same flare rod consumption. No other mod is added, removed or updated.

If your game was stuck on the loading error screen, update and it will start.


# Skybound SMP Season 2, v1.95

Controllable is out of the pack.

The controller mod added in v1.93 is removed. It crashed against the pack's version of JEI,
v1.94 shipped it with the JEI part cut out, and it is now gone entirely rather than half
working. Its library, Framework, goes with it since nothing else uses it.

Both are deleted from your install by this update. Nothing else changes: keyboard and mouse
were never touched, the server is unchanged, and there are no recipe or world content changes.

If you want a controller in the meantime, install Controllable yourself from CurseForge, but be
aware its JEI integration is what crashes and the pack cannot ship around that.


# Skybound SMP Season 2, v1.94

Crash fix for the controller update.

Controllable, added in v1.93, crashed the game against the pack's version of JEI. Its JEI
integration targets an older JEI layout, and the mismatch was fatal rather than silent. The mod
now ships without that integration, so it no longer crashes.

- Controllable still works for playing and for menus. Keyboard and mouse are untouched.
- What is gone: moving through the JEI item list with the controller. Use the mouse there.

Client side only, the server is unchanged, and no recipe or world content changes.


# Skybound SMP Season 2, v1.93

Controller support.

Controllable is now part of the pack, so a gamepad works for playing, for menus and for the
JEI item list. Plug the controller in, open Options and Controller Settings to pick it and to
remap buttons. Keyboard and mouse keep working exactly as before, nothing is forced on you.

- Controllable 0.25.4, with the SDL controller library it needs.
- Framework 0.13.11, the library Controllable depends on.

Both are client side only, the server is unchanged, and no recipe or world content changes.


# Skybound SMP Season 2, v1.92

The recipe book now matches the server.

A dozen recipe scripts had been running on the server for weeks without ever reaching the pack,
so JEI on your side was showing recipes the server does not use, and hiding ones it does. They
ship with this update:

- Steel from Create Factory Machines and Guns is its own material again, and no longer mixes
  with the steel of other mods, including inside multi-step Create recipes.
- Fireclay, bauxite, galena, nickel, brass pipes and the furniture blueprint get their recipes.
- Gadgets and Gizmos blocks, Saros bitumen, Interiors kelp and the lead split are craftable.
- CC:Tweaked wireless and ender modems work again, they were pointing at empty tags.
- Ink sacs are craftable and the Radar Warning Receiver finally has a recipe.
- Honey rubber can be made instead of only being an ingredient.
- Duplicate recipes for the same item are cleaned up.

No mods change in this update.


# Skybound SMP Season 2, v1.91

Kosmo is out of the pack. The space add-on a friend of ours was building is no longer part of
Skybound, on the server or in the pack. Nothing was built in its dimensions, so nothing is lost.

Create: Bits and Bobs was shipping twice. The pack carried both 1.0.7 and 1.0.8, which is the
same mod installed two times over. Only 1.0.8 ships now.

Create FPS Optimizer is gone. It was the suspect behind the long freeze some of us hit while
the world loaded.

Sodium settings and config keybinds are yours again. Updates no longer overwrite your Sodium
and Sodium Extra settings, or the FzzyConfig menu keybinds. Whatever you have set stays set.

Wings, jetpacks and thrusters now wear out, and the coin mod matches the server. Both were
already running on the server and only now reach your game.

Recipe fixes: wrenches pick up blocks from add-on mods, redstone links cost a netherite ingot,
and the Hammer Bid recipes are gone.


# Skybound SMP Season 2, v1.90

Two follow-ups to the update fix in v1.89.

The shaderpacks that come with the pack now actually arrive. The pack has carried eight
shaderpacks since v1.77, but the updater was not looking at that folder, so only people who
installed from the mrpack ever got them. They are part of what an update installs now.

An update that cannot finish no longer claims it did. If a file cannot be written, for example
because antivirus is holding it, the pack keeps showing as outdated and asks you to press
Update again, instead of marking itself up to date with an old file inside.

Both of these live in the rebuilt updater, so they apply to new installs. Nothing to do on an
existing install.


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

---
Older versions: see changelog_archive.md in the pack repo.
