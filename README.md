# Tech Blog Podcast

Automatically generated podcast from tech blog RSS feeds using Text-to-Speech (TTS).

## Structure

- `feed.xml` - The main RSS podcast feed following podcast standards
- `audio/` - MP3 audio files for each episode (tracked with Git LFS)
- `metadata/` - JSON metadata containing episode and channel information

## Feed Information

- **Title**: RSS Caster: Favourite Blogs in Sound
- **Audio Format**: MP3 files with TTS audio
- **RSS Standard**: Compatible with iTunes and major podcast platforms

## Enclosure URLs

Audio files are hosted via GitHub raw URLs:
`https://raw.githubusercontent.com/winston-bosan/tech_audio_agg/refs/heads/main/audio/`

## Technical Notes

This podcast was generated using:
- RSS Caster (Rust-based RSS-to-podcast converter)
- TTS for audio generation
- JSON-based metadata storage
- Git LFS for audio file storage
- Incremental processing for efficiency

The RSS feed follows the iTunes podcast specification and includes proper enclosure tags for podcast players.
