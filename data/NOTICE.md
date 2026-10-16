# Lexicon data

The pronunciation lexicons in this directory (`gb_gold.json`, `gb_silver.json`,
`us_gold.json`, `us_silver.json`) are taken unmodified from
[Misaki](https://github.com/hexgrad/misaki) 0.9.4 by hexgrad, licensed under the
Apache License 2.0 (see `LICENSE-misaki`). The rest of this crate remains under its own
MIT licence.

They replace the crate's original lexicons, which were regenerated with espeak-ng and
mispronounce some common words (for example "Covid" and "coronavirus") and write
diphthongs in a notation Kokoro's vocabulary lacks.
