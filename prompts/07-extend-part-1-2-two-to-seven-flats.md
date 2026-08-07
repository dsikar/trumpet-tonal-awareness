Extend `scores/part-1/1.2-lip-slurs.musicxml` after the existing D-minor section with the remaining flat-key pairs. Follow the score's established Part 1.2 pattern exactly: each bar is a slurred, four-quarter-note arpeggio in the order root–third–fifth–third; each major section contains its seven diatonic triads plus the octave triad, immediately followed by the corresponding relative natural-minor section in the same form. Add only the key name above the first bar of each section.

Before editing, inspect these XML files:

- `scores/part-1/1.2-lip-slurs.musicxml` is the authoritative model for the target's measure numbering, written B-flat-trumpet setup, treble clef, rhythm, slurs, key-signature changes, key labels, and the already-completed F-major/D-minor section.
- `scores/part-1/1.5-root-position-arpeggios.musicxml` is a secondary reference for the root-position arpeggio notation style and MusicXML note structure.
- `scores/part-1/1.1-long-tones.musicxml` is a secondary reference for the project's written-pitch B-flat-trumpet MusicXML conventions.

Add these pairs in this exact order. Change the key signature at the first measure of each major-key section and retain it for its relative minor:

1. B-flat major (two flats), then G minor.
2. E-flat major (three flats), then C minor.
3. A-flat major (four flats), then F minor.
4. D-flat major (five flats), then B-flat minor.
5. G-flat major (six flats), then E-flat minor.
6. C-flat major (seven flats), then A-flat minor.

Use correct diatonic spellings throughout. In particular, preserve flat letter names that arise from stacked thirds (including C-flat, F-flat, and G-flat where required), and encode them using the appropriate negative `<alter>` values. The active key signature must supply the flats: do not add explicit `<accidental>` elements or redundant printed accidentals. Check every triad against the applicable major or natural-minor scale; do not introduce non-diatonic major triads by raising a scale tone.

Preserve the F-major section's existing F4 opening and do not alter any completed section. Choose octave placements for the added sections by following the established neighbouring patterns and keep the sequence practical in the score's existing written-pitch register.

After updating the MusicXML:

1. Validate it with `xmllint --noout`.
2. Render `scores/part-1/1.2-lip-slurs.pdf` with the installed MuseScore command-line application.
3. Rebuild `scores/part-1/part-1-complete.pdf` by concatenating all Part 1 PDFs in numeric order, replacing the prior combined PDF.
4. Verify both regenerated PDFs open correctly with `pdfinfo` and confirm the working tree is free of whitespace errors with `git diff --check`.
