Create a second version of the chromatic interval study in C, covering every interval from Minor 2nd through Octave. Use `scores/scratchpad/01-chromatic-major-second.musicxml` as the authoritative source for the existing interval-study content, notation conventions, title/composer metadata, B-flat trumpet setup, tempo, clef, page settings, chromatic spellings, and section labels.

Set the score title to `Interval Practice for Trumpet in Bb`.

Write the new MusicXML score to:

`scores/scratchpad/08-chromatic-intervals-v2.musicxml`

Render its companion PDF to:

`scores/scratchpad/08-chromatic-intervals-v2.pdf`

## Required musical change

Retain the complete interval-study sequence from **Minor 2nd** through **Octave**, including all section headings and the existing descending studies. Change only the ascending studies:

- Keep only the first bar of each existing two-bar ascending cell.
- Omit the second, inverted/repeated bar of every ascending cell.
- The final ascending cell of each interval already consists of one bar; retain it.
- Do not alter the descending studies: retain every descending bar exactly as in the authoritative source, including note order, spellings, rhythm, and chromatic progression.

For example, in the Minor 2nd study, retain m. 100 (`C4 – D♭4 – C4 – D♭4`) and omit m. 101 (`D♭4 – C4 – D♭4 – C4`). Retain the next first bar (`C♯4 – D4 – C♯4 – D4`, currently m. 102) and omit its following inverted bar (currently m. 103), continuing this pattern through every ascending interval section.

Apply this one-bar ascending-cell format to all of the following sections:

- Minor 2nd
- Major 2nd
- Minor 3rd
- Major 3rd
- Perfect 4th
- Augmented 4th / Diminished 5th (both spellings)
- Perfect 5th
- Minor 6th
- Major 6th
- Minor 7th
- Major 7th
- Octave

Renumber measures consecutively in the new score. Retain the original section boundaries and put each section heading on the first measure of that section. Preserve the original notation’s four quarter notes per measure and the existing `new-system` section-start layout convention where practical.

## Accuracy and verification

Follow the interval and enharmonic-spelling rules in `SKILLS.md`. Check that every notated pair has the named interval’s semitone distance and correct diatonic spelling. Validate the new MusicXML with `xmllint --noout`, render it with MuseScore, and verify the PDF opens with `pdfinfo`. Do not modify the source score or overwrite its existing PDF.
