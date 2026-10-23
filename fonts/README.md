# Manrope local font assets

Unmodified variable WOFF2 subsets downloaded from the official Google Fonts service. Both files use normal style and the `wght` axis from **200 to 800**.

| File | Subset | Bytes |
| --- | --- | ---: |
| `manrope-latin-wght.woff2` | Latin | 24,836 |
| `manrope-latin-ext-wght.woff2` | Latin extended | 15,120 |
| **Total font data** | | **39,956** |

`Manrope-SOURCES.json` records exact download URLs, retrieval time, SHA-256 hashes, Unicode ranges and validation results. `Manrope-Google-Fonts-CSS.txt` preserves the official CSS response used to identify the subsets. This text snapshot is source documentation and includes additional language subsets that are not part of this local bundle.

The fonts retain their original SIL Open Font License 1.1; see `Manrope-OFL.txt`, copied from the official Google Fonts repository. No font bytes, names or metadata were modified.

The WOFF2 files were decoded with fontTools and Brotli. Both contain the expected variable weight axis; generating weight-200 and weight-800 instances produces different glyph outlines. The combined character maps cover German `ÄÖÜäöüßẞ`, including capital sharp S in the Latin-ext subset.

Use the local WOFF2 files in application font declarations, retaining the corresponding subset Unicode ranges from the source manifest. The application does not need to fetch Google Fonts at runtime.

Official sources:

- [Google Fonts CSS](https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&display=swap)
- [Google Fonts Manrope repository directory](https://github.com/google/fonts/tree/main/ofl/manrope)
- [Upstream Manrope project](https://github.com/googlefonts/manrope)
- [Official OFL text](https://raw.githubusercontent.com/google/fonts/main/ofl/manrope/OFL.txt)
