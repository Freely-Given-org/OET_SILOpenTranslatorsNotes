# Adaptation notice

This repository contains an adaptation of the English [SIL Open Translator’s Notes](https://github.com/BibleAquifer/SILOpenTranslatorsNotes)
(_Open Translator's Notes_ © 2024 [SIL International](https://opentn.bible); see `SIL_README.md`),
which are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en).
These adaptations are released under the same licence.

Only the JSON files are included (in `eng/json/`).

## Changes made

These changes were made automatically by `adaptSILOpenTranslatorsNotes.py` (version 0.10)
to match the [Open English Translation](https://github.com/Freely-Given-org/OpenEnglishTranslation--OET) Readers’ Version (OET-RV):

- In the notes’ content, traditional forms of names were changed to the OET-RV forms from `OET-RV_names_table.tsv`.
  The traditional form is given in parentheses at the first use in each note
  (and again after about 10 paragraphs of a long note), imitating the OET-RV,
  e.g., ‘Yeshua (Jesus; Grk. Yesus)’ then just ‘Yeshua’.
- Other wording changes:
  - LORD → Yahweh
  - John the Baptist → John the immerser
  - John the Baptizer → John the immerser

The note titles and metadata, and Bible book names in references (e.g., ‘John 1:19’) were not changed.
See `adaptation_log.tsv` for the number of times each change was made.
