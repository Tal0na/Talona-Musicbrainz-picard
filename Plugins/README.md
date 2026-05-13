[Back to main overview](../README.md)

# MusicBrainz Picard Plugin Configuration

This file summarizes the plugin settings and active plugin list from `Picard_Talona_Backup.ini`.

## Enabled Plugins
- `additional_artists_variables`
- `fanarttv` (cover art fallback, details in `Cover/README.md`)
- `format_performer_tags`
- `genre_mapper`
- `lrcget`
- `theaudiodb` (cover art fallback, details in `Cover/README.md`)

## Plugin Settings
- `check_for_plugin_updates=true`: Picard checks for plugin updates automatically.
- `check_for_updates=true`: Picard checks for general application updates.

## Plugin Notes
- `genre_mapper` helps map genres from MusicBrainz or external metadata into your preferred tag format.
- `lrcget` supports saving synchronized or unsynchronized lyrics files alongside audio tags.
- `fanarttv` is used for additional artwork and related media resources.
- `theaudiodb` provides an alternative metadata source for artwork, artist, and release information.

## Related Files in This Folder
- `Genre Mapper.md`: configuration or notes for the genre mapper plugin.
- `LRCLIB.md`: configuration or notes for the lyrics plugin support.

## Notes
This document focuses on plugin-related behavior. For metadata and cover art specifics, refer to the root `README.md` links.
