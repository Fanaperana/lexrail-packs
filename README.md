# Lexrail language packs

Word language packs for [Lexrail](https://github.com/Fanaperana), a cozy pixel-art word-train game.
The game downloads these from **Settings → Words**; you don't need to download anything by hand.

Each release holds `index.json` (the list of packs, with sizes and SHA-256 checksums) and one
`<id>.zip` per language. A pack contains `manifest.json` (alphabet, vowels, letter weights and
points), `words.txt`, optionally `definitions.txt`, and `LICENSE.txt`.

| Pack | Language | Sources |
|---|---|---|
| `fr` | French | Hunspell French dictionaries (MPL 2.0), FrequencyWords / OpenSubtitles 2018 (CC-BY-SA-4.0), LDNOOBW blocklist (CC-BY-4.0) |
| `es` | Spanish | Hunspell RLA-ES (GPL/LGPL/MPL), FrequencyWords (CC-BY-SA-4.0), LDNOOBW (CC-BY-4.0) |
| `de` | German | igerman98 Hunspell (GPLv2/GPLv3), FrequencyWords (CC-BY-SA-4.0), LDNOOBW (CC-BY-4.0) |
| `mg` | Malagasy | English Wiktionary via kaikki.org and Malagasy Wiktionary (CC-BY-SA-4.0) |

Each pack's word list is licensed under the terms of its sources, listed in the pack's
`LICENSE.txt`. Word lists are derived data: forms were checked against the spelling
dictionaries, ranked by subtitle frequency, folded to game letters and filtered for an
all-ages game.
