[Back to main overview](../README.md)

# MusicBrainz Picard — Cover Art Provider Priority

This section explains cover art sources and how Picard prioritizes them.

| Priority | Provider                             | Reason                                               |
| -------- | ------------------------------------ | ---------------------------------------------------- |
| 1st      | **Cover Art Archive: Release**       | Exact image for the specific release/edition         |
| 2nd      | **Cover Art Archive: Release Group** | Fallback for the same album                          |
| 3rd      | **fanart.tv**                        | Good quality but not always the official front cover |
| 4th      | **TheAudioDB**                       | Extra fallback                                       |
| 5th      | **Allowed URLs**                     | Manual source                                        |
| 6th      | **Local Files**                     | Last priority — since you want to update covers      |

## Cover Art Plugins
- `fanarttv`: used as a secondary source for non-official artwork and artist images.
- `theaudiodb`: used as an extra fallback for cover art when the main providers do not return a result.

## Notes
The preferred cover art source order is defined here. Plugin-specific cover behavior for `fanarttv` and `theaudiodb` is documented in this file instead of the main plugin overview.
