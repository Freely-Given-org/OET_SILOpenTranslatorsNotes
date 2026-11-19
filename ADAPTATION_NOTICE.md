# Adaptation notice

This repository contains an adaptation of the English [SIL Open Translator’s Notes](https://github.com/BibleAquifer/SILOpenTranslatorsNotes)
(_Open Translator's Notes_ © 2024 [SIL International](https://opentn.bible); see `SIL_README.md`),
which are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en).
These adaptations are released under the same licence.

Only the JSON files are included (in `eng/json/`).

## Changes made

These changes were made automatically by `adaptSILOpenTranslatorsNotes.py` (version 0.11)
to match the [Open English Translation](https://github.com/Freely-Given-org/OpenEnglishTranslation--OET) Readers’ Version (OET-RV):

- In the notes’ content, the OET-RV form of each name (from `OET-RV_names_table.tsv`) is given in parentheses
  after the first use of the traditional name in each note (and again after about 10 paragraphs of a long note),
  e.g., ‘Samuel (Shmuel)’ then just ‘Samuel’. (The traditional names are kept because the notes refer to the BSB.)
- Other OET-RV wording was added in parentheses after the first use of their term in each note, e.g., ‘the LORD (Yahweh)’:
  - LORD → Yahweh

The note titles and metadata, Bible book names in references (e.g., ‘John 1:19’),
and text quoted from other Bible versions (e.g., ‘“…” (NIV)’, and example translations attributed to a version) were not changed.
See `adaptation_log.tsv` for the number of times each change was made.
