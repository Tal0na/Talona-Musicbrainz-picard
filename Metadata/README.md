[Back to main overview](../README.md)

# MusicBrainz Picard Metadata Settings

This file summarizes the main metadata and classical music configuration from `Picard_Talona_Backup.ini`.

## General Metadata Behavior
- `auto_overwrite=true`: tags are automatically overwritten when files are saved.
- `clear_existing_tags=true`: existing file tags are removed before writing new metadata.
- `dont_write_tags=false`: writing tags to files is enabled.
- `album_tags=true`: album-level metadata is preserved and written.
- `artists_genres=true`: artist genre metadata is included.
- `enable_tagger_scripts=true`: custom tagging scripts are enabled.
- `add_unsynced_lyrics=true`: unsynced lyrics are written when available.
- `add_synced_lyrics=false`: synced lyrics are not used.
- `enable_ratings=false`: ratings are disabled.

## Classical and Work Handling
- `classical_extra_artists=true`: includes additional classical performer roles.
- `classical_work_parts=true`: supports work part segmentation for classical releases.
- `cwp_hierarchical_works=true`: enables hierarchical work handling.
- `cwp_partial=true` with `cwp_partial_text=(part)`: partial works are marked accordingly.
- `cwp_top_tag="top_work, style, grouping"`: top work metadata tags are supported.
- `cwp_genre_tag=genre` and `cwp_subgenre_tag=sub-genre`: genre and sub-genre are written to separate tags.
- `cwp_workdate_tag=work_year`: work date is stored in the `work_year` tag.
- `cwp_workdate_include=true`: work date is included when available.
- `cwp_workdate_annotate=true`: work date annotation is added to metadata.

## Classical Artist and Credits
- `cea_composer_album=true`: composer credits are included at the album level.
- `cea_arranger=arr.`: arranger credits use the `arr.` label.
- `cea_orchestrator=orch.`: orchestrator credits use the `orch.` label.
- `cea_translator=trans.`: translator credits use the `trans.` label.
- `cea_concertmaster=leader`: concertmaster is labeled as leader.
- `cea_performer_credited=true`: performers are credited whenever possible.
- `cea_recording_relationship_credited=true` and `cea_release_relationship_credited=true`: recording and release relationships are credited.
- `cea_group_credited=true`: group credits are enabled.
- `cea_inst_credit=true`: instruments are credited in metadata.
- `cea_lyricist=lyrics` and `cea_writer=writer`: lyricist and writer fields are mapped to their respective tags.

## Notes
This folder document focuses on the metadata and classical tagging settings for your Picard configuration. The root `README.md` links to other folders for cover art and plugin details.
