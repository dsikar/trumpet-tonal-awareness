# Work diary

## 2026-08-03 — Part 1

- Read the brief and chose a concise five-score warm-up baseline: one MusicXML exercise per numbered item.
- Added written-pitch Bb-trumpet MusicXML for long tones, lip slurs, C-major scale, tonguing, and root-position arpeggios.
- Added concise practice notes in `notes/part-1-daily-warm-up.md`.
- Validated XML syntax with xmllint; MuseScore 4.6.5 imported and rendered all five scores to one-page A4 PDFs.
- Part 1 baseline complete; ready to begin Part 2.
- Next: Part 2.1–2.3 — one C-major progression score with labelled Verse, Chorus, and Middle 8; root-position triads, quarter-note block chords, and Roman numerals below each chord.

## 2026-08-05 — Part 1 refinements and rendering

- Rendered every Part 1 MusicXML score to an adjacent PDF and combined them in numeric order as `scores/part-1/part-1-complete.pdf`.
- Restored Part 1.1 to its C-major chromatic long-tone sequence, from F♯3 through C6.
- Expanded Part 1.2 with slurred root–third–fifth–third diatonic-triad sequences for C major, A minor, G major, E minor, D major, and B minor; added the appropriate key-signature changes and concise key labels.
- Updated the project plan with a written B♭-trumpet scoring-range note (F♯3–C5).
- Added reusable rendering and score-extension prompts under `prompts/`, including the corrected Part 1.2 D-major/B-minor prompt.

## 2026-08-05 — Current status

- Part 1 is rendered and available as `scores/part-1/part-1-complete.pdf`.
- Part 1.1 remains the C-major chromatic long-tone exercise (F♯3–C6).
- Part 1.2 now contains the C-major/A-minor, G-major/E-minor, and D-major/B-minor slurred triad sections, with the appropriate key-signature changes.
- The next Part 1.2 task is to extend the sharp-key sequence from A major/F♯ minor through C♯ major/A♯ minor. `prompts/06-extend-part-1-2-three-to-seven-sharps.md` specifies the required starting triads and notation conventions; its first implementation was reverted because the triad patterns need to be checked against that specification before reapplying.
- Part 2 remains the next main project section after the Part 1.2 sharp-key extension is complete.


## 2026-08-06 — Part 1.2 key-signature extension

- Extended the slurred diatonic-triad exercise through A major/F♯ minor, E major/C♯ minor, B major/G♯ minor, F♯ major/D♯ minor, and C♯ major/A♯ minor.
- Used correct key signatures and enharmonic spellings: E♯ in the six- and seven-sharp sections, plus B♯ in the seven-sharp section.
- Corrected the B-major ii and vii° triads to C♯–E–G♯ and A♯–C♯–E after review; no E♯ belongs in B major.
- Added the one-flat pair, F major/D minor, with B♭ supplied by the key signature. The F-major sequence now begins on F4 and was transposed as a complete eight-bar section, ending on F5–A5–C6.
- Rendered and verified `scores/part-1/1.2-lip-slurs.pdf` and rebuilt `scores/part-1/part-1-complete.pdf`; the lip-slur PDF is now three A4 pages and the combined Part 1 PDF is seven A4 pages.
- Next: continue Part 1.2 with the remaining flat-key pairs, beginning B♭ major/G minor (two flats).
