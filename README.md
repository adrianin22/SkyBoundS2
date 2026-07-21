# Skybound S2

Modpack for Skybound SMP Season 2. NeoForge 1.21.1.

## Install

1. Download the latest `SkyboundS2.mrpack` from the **Releases** page:
   https://codeberg.org/SkyBoundSMPS2/SkyboundS2/releases/latest
2. In Prism Launcher: Add Instance, Import, select the `.mrpack`.
   (Also works in the Modrinth App: Add content from file.)
3. Prism downloads Minecraft 1.21.1, NeoForge 21.1.235, and the mods automatically.

## What's inside

- 194 mods (Season 2 set, without `observable`).
  - Most fetched automatically from Modrinth.
  - The rest bundled inside the pack (e.g. Voxy).
- Worldgen: Lithosphere + Still Life + Streams Reflowing + Ember's Floating Islands.
- Bundled `config/`, `defaultconfigs/`, `kubejs/` and `options.txt` for an identical setup.

## Why the pack is a Release, not a repo file

The `.mrpack` is a large binary that changes fully on every update. Committing it to
Git keeps every old copy in history forever, so the repo would grow without bound.
Releases store the file outside Git history, so updates never bloat the repo.
