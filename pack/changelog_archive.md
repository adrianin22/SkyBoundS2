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


# Skybound SMP Season 2, v2.14

Server patches now shipped to everyone, plus new building and TV content.

Added:
- Yuushya Townscape: 2600+ building and decoration blocks.
- Glaiden's Vista improvements: URL Cassette Maker, paste a link and pick a colour to make your own cassette.

Fixed:
- Create seats on moving ships: the camera no longer looks one way while your body faces another (Cosmonautics free look only kicks in with 6DOF on).

Changed:
- Vista updated to 5.5.6.
- Create: CC Better Recipes, Create: Things and Misc and Protection Pixel: rewritten scheduled task queue (no longer scans the whole queue every tick).
- Farmer's Delight: same patched build the server runs.
- Sable Quota: swivel bearings no longer count as physics structures (splits still do).
- KubeJS server scripts synced with the server, and the JEI hide list updated (fireworks, Legendary Monsters eyes, Ender Pouch and Ender Tank hidden).


# Skybound SMP Season 2, v2.13

Cosmonautics update.

Changed:
- Create: Cosmonautics updated from the 26.08.307 release to a newer 26.09.349 development build (patched by us so it runs on the server). Brings the upstream work since August, including the MFD screens and 6DOF free movement in space.

Fixed:
- Cleaned up the client startup log: missing block models, blockstates and textures from several mods now resolve (Tiny Gates, Cluttered signs, More Traffic lights, Create Propulsion, Simulated Coasters, Create Wings Plus, Pandas Decor lanterns, Diversity Delight pies, TFMG fuses, Hot Stuff link relay and others).
- Broken or missing sounds from Design n Decor chains, Create Gunsmithing, NTGL, Create Aviation mail, Electro Energetics and Legendary Monsters.
- The Mekanism key item texture.


# Skybound SMP Season 2, v2.12

New mod.

Added:
- Cosmonautics: Deep Air. Sealed, unbreached ships and stations built with Create Deep Seas now keep breathable air and gravity in space. Fill a sealed room with oxygen from a Deep Seas oxygen diffuser and you can breathe inside without a helmet. Gravity needs at least one room with air on the ship.


# Skybound SMP Season 2, v2.11

Fixes and removals.

Fixed:
- Extruding recipes from the Mechanical Extruder now show up in JEI. The extruder pole model was never loaded, which broke every extruding recipe page and caused lag near extruders.

Removed:
- Create: Sulfuric Resonance. Blocks and items from this mod are lost.


# Skybound SMP Season 2, v2.10

New content batch.

Added:
- Drive By Sable, replaces Drive By Wire and its Typewriter addon (it covers everything they did, now built for Sable sub-levels).
- Create Coasters Simulated and Coasters Engineered are back. Rivets have new limits: one rivet per sub-level, and a rivet cannot be placed on another rivet or on anything built onto one, so rivet chains are no longer possible.
- Skyport (Create Aeronautics).
- Aeronautics Player Tilt.
- Create: Who Touched My Train.
- Estrogen. The dash ability it grants is disabled.
- Diversity Delight. Its food effects are disabled, the food itself works normally.
- Sauce Delight.
- Hearth and Harvest.

Removed:
- Drive By Wire and Drive By Wire Typewriter. Blocks placed from those mods are lost.


# Skybound SMP Season 2, v2.09

Create FluidLogistics goes back down to 1.2.0, which fixes the client crash when a package arrives.

FluidLogistics 1.2.5 renamed an internal class that Create Mobile Packages 0.7.7 still calls when it draws the package toast, so the game died with a NoClassDefFoundError every time anyone ordered or received a package. 1.2.0 is the last version that still has that class, and Mobile Packages has no fix upstream yet.

The cost is the FluidLogistics features added since 1.2.0, among them the fluid factory gauges, fluid schematics and the copper frogport. They come back as soon as Mobile Packages is updated.


# Skybound SMP Season 2, v2.08

Sable Cat is out of the pack, and with it gone Sable moves up to 2.0.5.

Sable Cat patched the same sub-level storage code that Sable 2.0.5 rewrote, which is what crashed the server on autosave in 2.06. Removing it also removes the rest of its fixes, so if something that used to be quietly patched starts misbehaving, that is where to look.

Sable Scale ships with the mixin fix for 2.0.5.


# Skybound SMP Season 2, v2.07

Hotfix on top of 2.06.

Sable is back on 2.0.3. The 2.0.5 build we shipped in 2.06 crashes the dedicated server during autosave, inside its sub-level region file cache, and Sable Cat patches that same code but is built against 2.0.3. Sable Scale goes back to its stock jar for the same reason.

Nothing else changes.


# Skybound SMP Season 2, v2.06

A big maintenance pass. 66 mods moved to their latest build, three were dropped and one was added.

**Updated, the headline ones:** TFMG 1.3.0, JEI 19.56, Sable 2.0.5, Supplementaries 3.9.9, Sophisticated Backpacks 3.26.3 (with Core and the Create integration), Quark 485, Create Integrated Farming, Copycats+ 3.0.9, Fluid Logistics 1.2.9, KubeJS, FTB Library and Quests, Xaero's Minimap and World Map, Voice Chat 2.6.23, Veil 4.5.0, Blueprint, Moonlight, Puzzles Lib, and a long tail of libraries and performance mods.

**Added:** Lodestone.

**Removed:** Zero Point Systems, Aerocopycats and plastic_fix. Any blocks those mods placed in your world will disappear, Aerocopycats copycat blocks included.

**Notes:** PowerGrid is back on its stock build, the compatibility patch we shipped for it is no longer needed now that TFMG 1.3.0 restores the API it expected. A handful of mods were deliberately left on their older version because their newest build crashes or breaks another mod: GPU Tape, Easy Stock Ticker, Vista, Photon, Bits 'n' Bobs and Create More Girders.


# Skybound SMP Season 2, v2.05

A CREATIVE BUILD DIMENSION IS BACK

Season 2 has a separate creative world again, replacing the old Stasis one. Type /plot to open
it. You get your own plot, 15 by 15 chunks, and you build there in creative without touching
survival.

YOUR SURVIVAL INVENTORY IS SAFE. The moment you go in, everything you carry is put away: items,
armour, Curios, cosmetic slots and your XP. You arrive empty. When you come back out, all of it
returns exactly as it was. Nothing you make in the build dimension can follow you home.

WHAT DOES NOT WORK IN THERE, and why:

Ender chests, ender tanks, ender pouches, backpacks, shulker boxes and the portable Mekanism
dashboard. All of them read the same storage back in survival, so any one of them would be a
way to walk creative items into the server economy. Bring one in and it is destroyed.

Leaving to anywhere except the overworld. Space, the Nether, the End and sublevels all send you
back to spawn instead. Use the normal way out.

Mekanism does not unlock in there. If you have already earned it, it works as usual. If you have
not, crafting the key inside does nothing, the build dimension hands out no progression.

Claiming chunks still works normally inside your plot.

Everything else is unchanged, no recipes were touched and nothing was removed from the pack.


# Skybound SMP Season 2, v2.04

FOUR MODS REMOVED FOR FRAME RATE

This update only takes things out. Several of you reported lower frame rates after the recent
updates, so four mods that cost every player performance whether they used them or not are gone.

REMOVED: SearchLights. Its lights were drawn every frame by everyone who had one in view.

REMOVED: Sable Ragdolls, Sable Ragdolls Patch and Ragdoll Reactions. The three go together, the
other two do not run without the base mod. Players and mobs now die the normal way instead of
flopping around.

IF YOU HAD SEARCHLIGHTS PLACED: they are gone from the world with the mod, and so is anything
still sitting in a chest or in your inventory. Nothing else is affected.

Nothing was added and no recipe changed, so everything you have built keeps working.


# Skybound SMP Season 2, v2.03

FASTER LAUNCH, and three mods that were quietly broken are fixed

Two new mods work on how long the pack takes to open. Lightspeed caches the resource pack
and loads it in parallel, so the second launch after this update should be noticeably
quicker than the first. Rhenium caps the memory the game holds for structure templates.
Neither changes anything you can see or craft.

FIXED: Electro Energetics had no JEI support at all. Its recipe integration was crashing on
startup against the current version of JEI, so none of its machines or recipes showed up when
you looked them up. They are back.

FIXED: the Analog Audio radio did nothing when placed on a moving contraption. The mod was
failing to hand itself to Create and had been failing silently since it was added.

FIXED: Contraption Lights is now on its finished 1.5.0 release instead of a beta. One of its
features was failing to load every single launch.


# Skybound SMP Season 2, v2.02

CHANGED: Create: Cosmonautics moved to the official release build

The pack was shipping a build made straight from the mod's development branch. That branch
carries unfinished work that cannot run on a dedicated server: it kept crashing the server,
first while loading mods and then on every entity tick.

Cosmonautics is now the team's published release, 26.08.307. Everything in it works on both
sides and the server stays up. What you lose is only the unreleased part of the development
branch, the multifunction display and the free flight controls, which were never in a release
yet. Rockets, orbit and the rest of the mod are unchanged.

Recipes for this mod are still disabled on the server for now, so its items cannot be crafted
yet even though you can see them.


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

---
Older versions: see changelog_archive.md in the pack repo.
