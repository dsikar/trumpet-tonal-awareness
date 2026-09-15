# Work diary

## 2026-09-12 — Minor 6th audit

- An audit identified an error in the Minor 6th ascending study at m. 427: its mirrored G5–B♭4 pattern is nine semitones (a major sixth), but it must mirror m. 426's B4–G5 minor sixth. Replace B♭4 with B4 when correcting the score.

## 2026-09-12 — Major 7th interval study

- Added and user-reviewed the Major 7th study (mm. 518–555): mirrored chromatic ascent from C4–B4 through C5–B5, followed by a direct chromatic descent from B5–C5 to B4–C4. Every pair is eleven semitones and written as a major seventh.
- The Minor 6th m. 427 audit correction is also user-reviewed and complete: B♭4 was replaced by B4, restoring the mirrored G5–B4 minor-sixth cell.

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

## 2026-08-07 — Part 1.2 flat-key extension (2 to 7 flats)

- Extended `scores/part-1/1.2-lip-slurs.musicxml` with the remaining 6 flat-key pairs (measures 145 through 240): B♭ major/G minor (2 flats), E♭ major/C minor (3 flats), A♭ major/F minor (4 flats), D♭ major/B♭ minor (5 flats), G♭ major/E♭ minor (6 flats), and C♭ major/A♭ minor (7 flats).
- Enforced strict diatonic spellings including C♭, F♭, and G♭ where required by stacked thirds, with flats supplied by key signatures and no explicit `<accidental>` tags.
- Rendered `scores/part-1/1.2-lip-slurs.pdf` (now 5 pages) and rebuilt `scores/part-1/part-1-complete.pdf` (now 9 pages).
- Validated XML with `xmllint --noout`, verified PDFs with `pdfinfo`, and confirmed no whitespace errors with `git diff --check`.

## 2026-08-10 — Part 2 core diatonic progression set

- Added `scores/part-2/2.1-2.3-core-diatonic-progressions.musicxml`: the C-major Verse, Chorus, and Middle 8 in one twelve-bar score, using root-position quarter-note triads with chord symbols and Roman numerals.
- Added supporting practice notes in `notes/part-2-core-diatonic-progressions.md`.
- Next: Part 3 — transpose the full Verse/Chorus/Middle 8 set clockwise through the circle of fifths, confirming Bb-trumpet transposition in each MusicXML file.


## 2026-08-11 — Part 1.3 scale expansion

- Extended `scores/part-1/1.3-scales.musicxml` through all sharp and flat major key signatures, each followed by its relative natural minor.
- Rendered and verified `scores/part-1/1.3-scales.pdf` (three A4 pages) and rebuilt `scores/part-1/part-1-complete.pdf` (11 A4 pages).
- Next: add the harmonic-minor, melodic-minor, and chromatic scale work.

## 2026-08-19 — Session handoff

- Agreed to resume from the repository itself: identify the most recently modified MusicXML/PDF pair and check Git status, rather than maintain a separate project tracker.
- Current resume point: `scores/part-1/1.3-scales.musicxml` and its PDF; add harmonic-minor, melodic-minor, and chromatic scale work.

## 2026-08-20 — Scratchpad chromatic interval study

- Added a lightweight project scratchpad in `scratchpad.md`, with local interval-accuracy guidance in `SKILLS.md`.
- Added and rendered `scores/scratchpad/01-chromatic-major-second.musicxml` and its PDF.
- Scored the first C-centred chromatic frame and its major-second extension, then the expanded frame `C–B–B♭–B–C–C♯–D–C♯–C`.
- Added the confirmed major-third extension `B♭–D | D–F♯ | B♭–G♭ | C`; each major third was checked as four semitones.
- Next: continue the chromatic expansion only after confirming each proposed note sequence and interval semitone count.

## 2026-08-23 — Scratchpad structure update & re-render

- Added scratchpad exercise structure rule to `SKILLS.md`: end with a minim (half note) and begin next exercise immediately without rests.
- Updated `scores/scratchpad/01-chromatic-major-second.musicxml` to remove padding rests and conclude measure 7 on a minim C5.
- Re-rendered `scores/scratchpad/01-chromatic-major-second.pdf` via MuseScore and verified output with `pdfinfo`.
- Added instruction-scope abstraction rule to `SKILLS.md`, strictly distinguishing instruction representation/specification from execution/scoring.
- Added the formal chromatic frame pattern structure contour rules for Cells 1–3 to `SKILLS.md`.
- Corrected Cell 2 (mm. 4–7) to full 9-note frame plus major-third extension ending on quarter-note C5.
- Scored Cell 3 (mm. 8–12) with full 13-note frame (down to A4, up to D♯5) and true augmented-fourth (tritone / 6 semitones) extension (`A4–D♯5–D♯5–A5 | A4–D♯4–C5`), repeating C5 across barlines with no rests or minims.
- Cleaned up score annotations in `scores/scratchpad/01-chromatic-major-second.musicxml`, retaining "Trumpet Tonal Awareness" as title/composer and labelling bar 1 with "2nd", bar 4 with "Major 3rd", and bar 8 with "Augmented 4th".
- Re-rendered and verified `scores/scratchpad/01-chromatic-major-second.pdf` via MuseScore (1 page A4).
- Updated `scratchpad.md` and `SKILLS.md`.

## 2026-08-25 — Interval study: Minor 2nd

- Added ascending (C4 to C♯5, mm. 100–112) and descending (C♯5 to C4, mm. 113–125) Minor 2nd interval study to `scores/scratchpad/01-chromatic-major-second.musicxml`, validated with `xmllint`, and re-rendered PDF (3 pages A4).

## 2026-08-26 — Interval study: Major 2nd

- Added ascending (C4 to D5, mm. 126–138) and Major 2nd descending (D5 to C4, mm. 139–145) interval study to `scores/scratchpad/01-chromatic-major-second.musicxml`, validated with `xmllint`, and re-rendered PDF (3 pages A4).

## 2026-09-01 — Interval study: Major 2nd ascending pattern fix

- Replaced the Major 2nd ascending pattern in `scores/scratchpad/01-chromatic-major-second.musicxml` with the fixed 2-measure cell structure (`Root–M2–Root–M2 | M2–Root–M2–Root`), advancing chromatically by semitone from C4 to C5 (mm. 126–150).
- Applied standard diatonic enharmonic spellings (e.g. D♯4–E♯4 and A♯4–B♯4 for stacked diatonic 2nds).
- Renumbered subsequent measures: Major 2nd descending (mm. 151–157), Minor 3rd ascending (mm. 158–170), and Minor 3rd descending (mm. 171–175).
- Re-rendered `scores/scratchpad/01-chromatic-major-second.pdf` via MuseScore 4.6.5, validated XML with `xmllint`, and verified output with `pdfinfo` (3 pages A4).
- Updated `scratchpad.md` and `TODO.md` with the new measure ranges and completed task.

## 2026-09-02 — Interval study: Major 2nd descending semitone steps

- Replaced the Major 2nd descending study in `scores/scratchpad/01-chromatic-major-second.musicxml` so each cell is a descending major second (2 semitones) and the upper note steps down chromatically from D5 to D4 (mm. 151–163, 13 measures).
- Spelled each pair as an adjacent-letter major second, matching the TODO example `D5 – C5` / `C♯5 – B4` and using F♭ for the G♭ cell.
- Renumbered subsequent measures: Minor 3rd ascending (mm. 164–176) and Minor 3rd descending (mm. 177–181).
- Re-rendered `scores/scratchpad/01-chromatic-major-second.pdf` via MuseScore 4.6.5, validated XML with `xmllint`, and verified output with `pdfinfo` (3 pages A4).
- Updated `scratchpad.md` and `TODO.md` with the new measure ranges and completed task.

## 2026-09-02 — Interval-study enharmonic spelling rule

- Added an Enharmonic spelling (interval study) section to `SKILLS.md`: pairs on different staff degrees; ascending lowest-note-first with sharps; descending highest-note-first with flats.
- Pointed `scratchpad.md` section 02 at that rule; left the listed sequences unchanged pending rescoring.
- Added a TODO to apply the rule to the existing Minor 2nd, Major 2nd, and Minor 3rd studies. The chromatic-frame cells and Part 1 key-signature spellings are out of scope.

## 2026-09-02 — Interval study: Minor 2nd enharmonic respelling

- Respelled Minor 2nd mm. 100–125 in `scores/scratchpad/01-chromatic-major-second.musicxml` to the interval-study rule in `SKILLS.md`: pairs on different staff degrees; ascending lowest-note-first with sharps; descending highest-note-first with flats.
- Opening cell is now `C4 – D♭4 – C4 – D♭4` | `D4 – C♯4 – D4 – C♯4`. Same-degree bars such as `F♯–F` and `B–B♭` became `G♭–F` and `B–A♯`.
- Descent now starts on `D♭5 – C5` (matching the end of the ascent) rather than `C♯5 – C5`.
- Re-rendered `scores/scratchpad/01-chromatic-major-second.pdf` via MuseScore 4.6.5, validated XML with `xmllint`, and verified output with `pdfinfo` (3 pages A4).
- Updated `scratchpad.md` and `TODO.md`. Major 2nd and Minor 3rd spelling still pending.
- Parked a tomorrow note: the baked-in spelling rule may not fit the Major 2nd. Bar 152 is the second descending step and currently raises C as `C♯5 – B4` rather than flattening to `D♭5`.

## 2026-09-03 — Interval study: Minor 3rd ascending cell correction

- Corrected the ascending Minor 3rd study (mm. 164–176) so each two-bar cell alternates one base pitch with its minor third, then reverses that same pair: for example, `C4–D♯4` in m. 164 and `D♯4–C4` in m. 165.
- Advanced the base pitch chromatically for each following cell: C, C♯, D, D♯, E, F, then F♯ in the final single measure. The spellings preserve true minor thirds (three semitones), including F–A♭.
- Re-rendered `scores/scratchpad/01-chromatic-major-second.pdf`, validated the MusicXML with `xmllint`, and verified the three-page A4 PDF with `pdfinfo`.

## 2026-09-03 — Interval study: Minor 3rd full chromatic ascent and descent

- Extended the corrected two-bar ascending cell pattern through C5–D♯5 (mm. 164–188), retaining the reversal in m. 177 (`A4–F♯4`) before moving on to the G-based cell.
- Replaced the premature descent with a 13-cell chromatic descent from D♯5–C5 through D♯4–C4 (mm. 189–201).

## 2026-09-04 — Interval study: Major 3rd and pattern decision

- Closed the descending-pattern design decision: retain the direct one-bar chromatic descent. It deliberately requires roughly half the work of the mirrored two-bar ascending cells.
- Added Major 3rd study to `scores/scratchpad/01-chromatic-major-second.musicxml`: mirrored chromatic ascent from C4–E4 to C5–E5 (mm. 202–226), then direct chromatic descent from E5–C5 to E4–C4 (mm. 227–239).
- Used true four-semitone major-third spellings throughout, including D♯–F𝄪, A♯–C𝄪, E♭–C♭, and D♭–B𝄫.
- Validated XML with `xmllint --noout` and rendered the companion PDF with MuseScore; output is four A4 pages.


## 2026-09-05 — Scratchpad interval-study handoff

- Completed and user-reviewed the Perfect 4th study in `scores/scratchpad/01-chromatic-major-second.musicxml`: chromatic mirrored ascent in mm. 240–264 and direct chromatic descent in mm. 265–277. Every cell is five semitones; its TODO is checked.
- Completed and user-reviewed the tritone study in the same score: mm. 278–302 ascend and mm. 303–315 descend. The score title is **“Augmented 4th / Diminished 5th (Augmented 4th spelling)”**. Every cell is six semitones and written as an augmented fourth (four staff degrees), including high-note-first descending cells.
- For the augmented-fourth study, use simple enharmonic spellings that preserve a written fourth and avoid double accidentals. The approved spellings include D♭–G (not C♯–F𝄪), E–A♯ (approved specifically for mm. 286–287 rather than F♭–B♭), G♭–C, C♭–F, D♯–A, C♯–G, A♯–E, G♯–D, F♯–C, and G–D♭. In particular, m. 314 `G4 – D♭4` is already an augmented fourth: identify the lower/reference pitch first, so D♭ up to G is a fourth.
- Resolved Major 3rd study notation (mm. 202–239): removed the problematic double accidentals in mm. 208–209, 222–223, and 230; m. 236 is `G4 – E♭4`; m. 237 is `F♯4 – D4`. The Major 3rd study is user-reviewed and complete.
- Updated `scratchpad.md`, `SKILLS.md` (interval semitone references), and `TODO.md`. The next unchecked interval-study task is: **Repeat the tritone interval practice with Diminished 5th spelling.**
- Review gate: do **not** mark any future TODO task complete after technical validation alone. Leave it unchecked until the user explicitly reviews/approves the rendered exercise.
- Rendering/validation command: `musescore -o scores/scratchpad/01-chromatic-major-second.pdf scores/scratchpad/01-chromatic-major-second.musicxml`, followed by `xmllint --noout` and `pdfinfo`. Current companion PDF is six A4 pages.
- Do **not** use `agy`/Gemini for further work; the user explicitly asked not to use it. `update-major-third-notation.sh` remains an ignored local helper for the earlier mm. 236–237 correction; it is not the workflow for future studies.

## 2026-09-08 — Interval-study handoff

- Corrected the Minor 2nd ascending study to use complete mirrored two-bar cells: lower-to-upper in the first bar, upper-to-lower in the second, then a chromatic semitone rise to the next pair. It now occupies mm. 100–124; the untouched Minor 2nd descent is mm. 125–137.
- Renumbered every later interval study after the expanded Minor 2nd ascent. Restored the **Interval study / Minor 2nd** heading and a new-system break at m. 100.
- Added and rendered the complete **Augmented 4th / Diminished 5th (Diminished 5th spelling)** study in mm. 328–365. Each pair is a six-semitone diminished fifth (five staff degrees); the user reviewed it and its TODO is complete.
- Current scratchpad PDF is seven A4 pages. MusicXML was validated with `xmllint`, rendered with MuseScore, and checked with `pdfinfo`.
- **Perfect 5th interval study was added, rendered, and user-reviewed; its TODO is complete.**

## 2026-09-09 — Interval study: Perfect 5th

- Added the Perfect 5th study in mm. 366–403: a mirrored chromatic ascent from C4–G4 through C5–G5, followed by a direct chromatic descent from G5–C5 to G4–C4.
- All 38 cells were verified as seven semitones spanning five staff degrees; MusicXML was validated and the companion PDF re-rendered as seven A4 pages.
- User reviewed the study; its TODO is complete.

## 2026-09-09 — Interval studies: sixths and Minor 7th

- Added and user-reviewed the Minor 6th study (mm. 404–441): every cell is eight semitones over six staff degrees; its TODO is complete.
- Added and user-reviewed the Major 6th study (mm. 442–479): every cell is nine semitones over six staff degrees; its TODO is complete. User-approved enharmonic spellings: mm. 462–463 are B♭–G / G–B♭, matching m. 469, and m. 470 is F♯–A, matching m. 461.
- Added and user-reviewed the Minor 7th study (mm. 480–517): every cell is ten semitones over seven staff degrees; its TODO is complete.
- MusicXML was validated with `xmllint`; the companion score was rendered with MuseScore and is now nine A4 pages.
- **Next interval-study task:** Major 7th on the chromatic scale. The Octave chromatic study is also queued. Leave each TODO unchecked until user review.

## 2026-09-14 — Interval-study completion and v2 handoff

- The complete original interval study now runs from **Minor 2nd** (m. 100) through **Octave** (m. 593) in `scores/scratchpad/01-chromatic-major-second.musicxml`. Major 7th is mm. 518–555; the user-reviewed Octave study is mm. 556–593. The Octave uses 12-semitone, same-letter pairs: mirrored chromatic ascent C4–C5 through C5–C6, then direct chromatic descent C6–C5 through C5–C4.
- Corrected original-study m. 431 to alternate G♭5 and B♭4, restoring the intended minor sixth.
- The companion `scores/scratchpad/01-chromatic-major-second.pdf` was regenerated after the octave addition. Validate and render this source with `xmllint --noout scores/scratchpad/01-chromatic-major-second.musicxml`, then `musescore -o scores/scratchpad/01-chromatic-major-second.pdf scores/scratchpad/01-chromatic-major-second.musicxml`, followed by `pdfinfo`.
- `SKILLS.md` is authoritative for interval semitone counting and enharmonic spelling; it now explicitly lists an octave as 12 semitones. The review gate remains in force: leave a newly created score task unchecked until the user has reviewed its rendered PDF.
- The next actionable task is unchecked in `TODO.md`: execute `prompts/08-chromatic-intervals-v2.md`. That prompt creates `scores/scratchpad/08-chromatic-intervals-v2.musicxml` and `.pdf`, titled **“Interval Practice for Trumpet in Bb”**. It retains all descents unchanged but reduces each mirrored ascending two-bar cell to its first bar only, renumbering measures consecutively. Do not alter the original score or PDF while doing so.
- Commit `05d320d` is pushed to `origin/main`; it includes the original octave study/PDF, the v2 prompt, documentation/TODO updates, and the repository's `.obsidian/` configuration artifacts.

## 2026-09-15 — Streamlined chromatic interval study (v2)

- Created `scores/scratchpad/08-chromatic-intervals-v2.musicxml` and its rendered PDF, **“Interval Practice for Trumpet in Bb”**. It condenses each ascending interval cell from two bars to one, retains every existing descending bar unchanged, and renumbers the score consecutively (437 measures; eight A4 pages).
- User reviewed the v2 score. Corrected the Minor 3rd spellings in mm. 152 and 177 from C–D♯ / D♯–C to C–E♭ / E♭–C; each is a minor third (three semitones spanning three staff degrees).
- Validated the MusicXML with `xmllint --noout`, rendered with MuseScore, and verified the PDF with `pdfinfo`. The v2 TODO is complete.
