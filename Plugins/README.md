[← Back to main overview](../README.md)

# MusicBrainz Picard — Plugin Configuration

This file summarizes the active plugins and their settings from `Picard_Talona_Backup.ini`.

## Enabled Plugins

| Plugin | Purpose |
|---|---|
| `additional_artists_variables` | Exposes extra artist credit variables for scripting |
| `fanarttv` | Cover art fallback — see [`Cover/README.md`](../Cover/README.md) |
| `format_performer_tags` | Formats performer and instrument tags consistently |
| `genre_mapper` | Maps genres from MusicBrainz or external sources into preferred tag format |
| `lrcget` | Saves synchronized (`.lrc`) or plain lyrics alongside audio files |
| `theaudiodb` | Cover art fallback — see [`Cover/README.md`](../Cover/README.md) |

## Plugin Settings

- `check_for_plugin_updates=true` — Picard checks for plugin updates automatically.
- `check_for_updates=true` — Picard checks for general application updates.

## Plugin Notes

- **`genre_mapper`** — Maps genres from MusicBrainz or external metadata into your preferred tag format. Configuration details in [`Genre Mapper.md`](Genre%20Mapper.md).
- **`lrcget`** — Supports saving synchronized or unsynchronized lyrics files alongside audio tags. Configuration details in [`LRCLIB.md`](LRCLIB.md).
- **`fanarttv`** — Used for additional artwork and related media resources. Acts as a cover art fallback provider.
- **`theaudiodb`** — Provides an alternative metadata source for artwork, artist, and release information. Acts as a cover art fallback provider.
- **`additional_artists_variables`** — Adds extra scripting variables for detailed artist credit formatting, useful for classical music tagging.
- **`format_performer_tags`** — Ensures performer and instrument credits are tagged in a consistent, readable format.

## Related Files in This Folder

- [`Genre Mapper.md`](Genre%20Mapper.md) — Configuration and notes for the genre mapper plugin.
- [`LRCLIB.md`](LRCLIB.md) — Configuration and notes for the lyrics plugin support.

## Notes

This document focuses on plugin-related behavior. For cover art and metadata specifics, refer to the root [`README.md`](../README.md) links.
