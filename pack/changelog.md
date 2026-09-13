# Skybound SMP Season 2, v2.01

FIXED: Create: Cosmonautics crashed the server at startup

The build of Create: Cosmonautics that shipped in v1.99 could not start on a dedicated server.
One of its classes registers an event handler that only exists on the client, so the server
aborted while loading mods and never came up. The mod is rebuilt with that handler marked
client side, and the server boots normally again.

Same mod, same version, same content: only the broken registration is fixed. The jar keeps its
name, so the updater repairs it in place on your next launch.


# Skybound SMP Season 2, v2.00

REMOVED: WorldEdit (client side only)

WorldEdit is gone from the modpack, but it is still installed and working on the server, so the
commands you use in game are unchanged. It was only ever used server side, and a copy sitting in
your own mods folder did nothing but cost memory and loading time.

Nothing else changes: same mod list otherwise, same recipes, same configs. If you kept your own
WorldEdit schematics, they stay where they are, the folder is not touched.


# Skybound SMP Season 2, v1.99

ADDED: Create: Cosmonautics

Space addon for Create: Aeronautics. Build rockets, leave the ground and fly to orbit with the
same Create machinery you already use. It brings its own orbital flight model, so a ship that
leaves the atmosphere keeps behaving like a real craft instead of teleporting to another world.
It runs on top of Aeronautics and Sable, both already in the pack, and it is installed on the
server too, so anything you build there flies for everyone.

FIXED: client crash when opening the pause menu

FTB Chunks saved the minimap on the render thread while its own worker thread was still adding
map regions, and the two collided. Pressing ESC at the wrong moment closed the game with a
ConcurrentModificationException, most often right after exploring or flying over new land.
The pack now ships a patched FTB Chunks jar that takes a snapshot of the regions under the
mod's own lock before saving them. Same mod, same version, same map data, no crash.

Nothing else changes: same recipes, same configs, no other mod added or removed.


# Skybound SMP Season 2, v1.98

REMOVED: Create Parachute

Create Parachute shipped in v1.97 and it cannot run on a dedicated server. One of its blocks
is registered through code that loads a client-only screen class, so the server aborts while
registering blocks and never finishes starting. It also broke registration for Create: Power
Grid, Dashpanels and Rechiseled: Create on the way down. The mod is out of the pack and off
the server, and everything it dragged with it works again.

If you placed a parachute block or kept a parachute item, it is gone with the mod. Nothing
else in this update changes: same mod list otherwise, same recipes, same configs.


# Skybound SMP Season 2, v1.97

A big clear-out and a big restock.

REMOVED (16 mods)
Create: Radionautics, Create: Flight Control, Create: Ironworks, Create Redstone Link GUI,
Create: Sonar, Floating Islands, Mowzie's Mobs, Vestalihy, Unlocked Void Sea, Placeable Items,
Integrated Dungeons and Structures, HBs Foundation, Simply Swords: Create Lines,
Myths and Legends, Mo Glass and Luminous Beasts. Simply Swords itself stays, only its Create
add-on is gone. One unused library, Integrated API, went with them.
If you had blocks or items from any of these placed in the world, they will disappear. Anything
in a chest or in your inventory is lost the same way. Move what you care about before updating.

ADDED (17 mods)
Searchlights, Create: Alerted, Create: Rolling Tones, Create: Under Pressure, Create Parachute,
Tracksta, Farming for Blockheads, Let's Do Furniture seats for Create and Sable, Talking Heads,
Bathymetry, Cool Rain and Sable: Cool Rain, Sable: Quota, Sablecat, Sable Ragdoll Patch,
Jade Sable compatibility, and Xaero's Map support for Sable ships. Three small libraries these
need come along with them.

TWO NEW RECIPES
Honey Bottle can now be crafted from three sugar, one slime ball and a glass bottle, so a bottle
of honey no longer depends on finding bees.
Seabrass Ingot can now be crafted from one brass ingot and two prismarine shards. Seabrass ore
only generates in a short list of plain vanilla biomes, and this world runs custom ones, so the
ore never appeared and every seabrass block was unobtainable. Now the whole set is reachable.

The server is running the same list.


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

---
Older versions: see changelog_archive.md in the pack repo.
