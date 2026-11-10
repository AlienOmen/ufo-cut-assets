# UFO Cut sounds

The sound and music shelf of **UFO Cut**, the video editor by A.L.I.E.N.
The app reads `audio/manifest.json` the first time someone opens the shelf
and downloads a sound the first time it is used.

Everything here is **CC0 1.0** (public domain dedication): free to use in
personal and commercial videos, with no credit owed. Each entry in the
manifest records where the file came from, so the licence can be checked.

## Where the sounds come from

| Source | What | Licence |
| --- | --- | --- |
| [Kenney](https://kenney.nl/assets/category:Audio) — Impact Sounds, Interface Sounds, Sci-fi Sounds, Digital Audio, Music Jingles | Effects and short jingles, files unchanged | CC0 1.0 |
| [OpenGameArt](https://opengameart.org) — tracks whose page lists CC0 only (checked 2026-11-10) | Music beds and ambience; large files re-encoded to Ogg Vorbis | CC0 1.0 |

Thank you to Kenney and to the OpenGameArt authors. CC0 asks for no credit;
it is given gladly.

## Layout

```text
audio/
  manifest.json     the list: id, name, category, duration, licence, source, sha256
  *.ogg, *.mp3      the files, flat
```

Categories: Whoosh, Impact, Riser, Ambience, Music, plus Interface and
Sci-fi (shown under "All").

If you made one of these files and it is not CC0, open an issue and it
will be removed.
