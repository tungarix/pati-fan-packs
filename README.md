# Pati fan packs

Optional fan-made character packs for [Pati](https://github.com/tungarix/pati), the desktop companion.
Pati downloads them only when you ask: **Settings > Characters > Fan packs > Load list**.

**These are unofficial fan works.** They are not affiliated with, made by or endorsed by the owners of the characters they are inspired by. All rights to those characters belong to their respective owners. The drawings here were made for Pati and contain no images, logos, models, audio or music taken from any game.

## Packs

| Pack | Frames | Fights |
| --- | --- | --- |
| Gordon Freeman | stand, walk, talk, sleep, held, fall, fight, win | yes: Kafa Yengeci |

## Install

In Pati: Settings > Characters > Fan packs > **Load list** > **Install**. Each download is checked against a SHA-256 and unpacked only if it holds nothing but images and JSON.

By hand: download a pack zip from the latest release and unpack it into Pati's `characters` folder (`%APPDATA%\Pati\characters\<pack id>`).

## Make your own pack

A pack is a folder with `manifest.json`, `character.json` and PNG frames. See the Pati README and `docs` for the format, and `scripts/pack-store.mjs` in the Pati repository for how the release assets are built.

## Take-down

If you own a character shown here and want a pack removed, open an issue or write to the address on the Pati repository's profile and it will be taken down.
