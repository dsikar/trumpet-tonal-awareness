# Scratchpad

Short practice ideas in development. The scores here are deliberately small and may later be expanded into a numbered book section.

## 01 — Chromatic major-second expansion in C

Written pitch for B-flat trumpet. Always return to C5 after the descending or ascending chromatic note, before playing the interval extension.

- **Cell 1** (mm. 1–3): Chromatic frame `C5–B4–C5–C♯5–C5–B4–C♯5–C♯5` with major-second extension `D♯5–B4–A4–C5`.
- **Cell 2** (mm. 4–7): Chromatic frame `C5–B4–B♭4–B4–C5–C♯5–D5–C♯5–C5` with major-third extension `B♭4–D5–D5–F♯5–B♭4–G♭4–C5`.
- **Cell 3** (mm. 8–12): Chromatic frame `C5–B4–B♭4–A4–B♭4–B4–C5–C♯5–D5–D♯5–D5–C♯5–C5` with augmented-fourth extension `A4–D♯5–D♯5–A5–A4–D♯4–C5`.

Each cell resolves to a quarter-note C5 and connects immediately to the next cell's opening C5 without rests or minims.

Score: [`scores/scratchpad/01-chromatic-major-second.musicxml`](scores/scratchpad/01-chromatic-major-second.musicxml)

## 02 — Interval study in C

Enharmonic spelling for this study is defined in `SKILLS.md`. Interval spelling follows the diatonic relationship to the lower/current reference note; playing direction only sets the order of the pair. In particular, descending Major 2nd cells retain adjacent-letter spellings such as `C♯5 – B4` (B4 with its major second above), rather than using flats merely because the cell is played downward. Minor 2nd and Minor 3rd sequences below follow the established rule.

Ascending and descending interval sequence starting from C4, ending on the target pitch so that the final interval (octaves) resolves at C6.

- **Minor 2nd** (mm. 100–125):
  - **Ascending** (mm. 100–112):
    - mm. 100–101: `C4 – D♭4 – C4 – D♭4` | `D4 – C♯4 – D4 – C♯4` (resolves on `C♯4`)
    - mm. 102–103: `D4 – E♭4 – D4 – E♭4` | `E4 – D♯4 – E4 – D♯4` (resolves on `D♯4`)
    - mm. 104–105: `E4 – F4 – E4 – F4` | `G♭4 – F4 – G♭4 – F4` (resolves on `F4`)
    - mm. 106–107: `F♯4 – G4 – F♯4 – G4` | `A♭4 – G4 – A♭4 – G4` (resolves on `G4`)
    - mm. 108–109: `G♯4 – A4 – G♯4 – A4` | `B♭4 – A4 – B♭4 – A4` (resolves on `A4`)
    - mm. 110–111: `A♯4 – B4 – A♯4 – B4` | `C5 – B4 – C5 – B4` (resolves on `B4`)
    - m. 112: `C5 – D♭5 – C5 – D♭5` (resolves on `D♭5`)
  - **Descending** (mm. 113–125, direct chromatic step-down):
    - m. 113: `D♭5 – C5 – D♭5 – C5`
    - m. 114: `C5 – B4 – C5 – B4`
    - m. 115: `B4 – A♯4 – B4 – A♯4`
    - m. 116: `B♭4 – A4 – B♭4 – A4`
    - m. 117: `A4 – G♯4 – A4 – G♯4`
    - m. 118: `A♭4 – G4 – A♭4 – G4`
    - m. 119: `G4 – F♯4 – G4 – F♯4`
    - m. 120: `G♭4 – F4 – G♭4 – F4`
    - m. 121: `F4 – E4 – F4 – E4`
    - m. 122: `E4 – D♯4 – E4 – D♯4`
    - m. 123: `E♭4 – D4 – E♭4 – D4`
    - m. 124: `D4 – C♯4 – D4 – C♯4`
    - m. 125: `D♭4 – C4 – D♭4 – C4` (resolves on `C4`)
- **Major 2nd** (mm. 126–163):
  - **Ascending** (mm. 126–150):
    - mm. 126–127: `C4 – D4 – C4 – D4` | `D4 – C4 – D4 – C4` (resolves on `C4`)
    - mm. 128–129: `C♯4 – D♯4 – C♯4 – D♯4` | `D♯4 – C♯4 – D♯4 – C♯4` (resolves on `C♯4`)
    - mm. 130–131: `D4 – E4 – D4 – E4` | `E4 – D4 – E4 – D4` (resolves on `D4`)
    - mm. 132–133: `D♯4 – E♯4 – D♯4 – E♯4` | `E♯4 – D♯4 – E♯4 – D♯4` (resolves on `D♯4`)
    - mm. 134–135: `E4 – F♯4 – E4 – F♯4` | `F♯4 – E4 – F♯4 – E4` (resolves on `E4`)
    - mm. 136–137: `F4 – G4 – F4 – G4` | `G4 – F4 – G4 – F4` (resolves on `F4`)
    - mm. 138–139: `F♯4 – G♯4 – F♯4 – G♯4` | `G♯4 – F♯4 – G♯4 – F♯4` (resolves on `F♯4`)
    - mm. 140–141: `G4 – A4 – G4 – A4` | `A4 – G4 – A4 – G4` (resolves on `G4`)
    - mm. 142–143: `G♯4 – A♯4 – G♯4 – A♯4` | `A♯4 – G♯4 – A♯4 – G♯4` (resolves on `G♯4`)
    - mm. 144–145: `A4 – B4 – A4 – B4` | `B4 – A4 – B4 – A4` (resolves on `A4`)
    - mm. 146–147: `A♯4 – B♯4 – A♯4 – B♯4` | `B♯4 – A♯4 – B♯4 – A♯4` (resolves on `A♯4`)
    - mm. 148–149: `B4 – C♯5 – B4 – C♯5` | `C♯5 – B4 – C♯5 – B4` (resolves on `B4`)
    - m. 150: `C5 – D5 – C5 – D5` (resolves on `D5`)
  - **Descending** (mm. 151–163, semitone step-down):
    - m. 151: `D5 – C5 – D5 – C5`
    - m. 152: `C♯5 – B4 – C♯5 – B4`
    - m. 153: `C5 – B♭4 – C5 – B♭4`
    - m. 154: `B4 – A4 – B4 – A4`
    - m. 155: `B♭4 – A♭4 – B♭4 – A♭4`
    - m. 156: `A4 – G4 – A4 – G4`
    - m. 157: `A♭4 – G♭4 – A♭4 – G♭4`
    - m. 158: `G4 – F4 – G4 – F4`
    - m. 159: `G♭4 – F♭4 – G♭4 – F♭4`
    - m. 160: `F4 – E♭4 – F4 – E♭4`
    - m. 161: `E4 – D4 – E4 – D4`
    - m. 162: `E♭4 – D♭4 – E♭4 – D♭4`
    - m. 163: `D4 – C4 – D4 – C4` (resolves on `C4`)
- **Minor 3rd** (mm. 164–201):
  - **Ascending** (mm. 164–188):
    - mm. 164–165: `C4 – D♯4 – C4 – D♯4` | `D♯4 – C4 – D♯4 – C4`
    - mm. 166–167: `C♯4 – E4 – C♯4 – E4` | `E4 – C♯4 – E4 – C♯4`
    - mm. 168–169: `D4 – F4 – D4 – F4` | `F4 – D4 – F4 – D4`
    - mm. 170–171: `D♯4 – F♯4 – D♯4 – F♯4` | `F♯4 – D♯4 – F♯4 – D♯4`
    - mm. 172–173: `E4 – G4 – E4 – G4` | `G4 – E4 – G4 – E4`
    - mm. 174–175: `F4 – A♭4 – F4 – A♭4` | `A♭4 – F4 – A♭4 – F4`
    - mm. 176–177: `F♯4 – A4 – F♯4 – A4` | `A4 – F♯4 – A4 – F♯4`
    - mm. 178–179: `G4 – B♭4 – G4 – B♭4` | `B♭4 – G4 – B♭4 – G4`
    - mm. 180–181: `G♯4 – B4 – G♯4 – B4` | `B4 – G♯4 – B4 – G♯4`
    - mm. 182–183: `A4 – C5 – A4 – C5` | `C5 – A4 – C5 – A4`
    - mm. 184–185: `A♯4 – C♯5 – A♯4 – C♯5` | `C♯5 – A♯4 – C♯5 – A♯4`
    - mm. 186–187: `B4 – D5 – B4 – D5` | `D5 – B4 – D5 – B4`
    - m. 188: `C5 – D♯5 – C5 – D♯5` (resolves on `D♯5`)
  - **Descending** (mm. 189–201, Minor 3rd step-down):
    - m. 189: `D♯5 – C5 – D♯5 – C5`
    - m. 190: `D5 – B4 – D5 – B4`
    - m. 191: `C♯5 – A♯4 – C♯5 – A♯4`
    - m. 192: `C5 – A4 – C5 – A4`
    - m. 193: `B4 – G♯4 – B4 – G♯4`
    - m. 194: `B♭4 – G4 – B♭4 – G4`
    - m. 195: `A4 – F♯4 – A4 – F♯4`
    - m. 196: `A♭4 – F4 – A♭4 – F4`
    - m. 197: `G4 – E4 – G4 – E4`
    - m. 198: `F♯4 – D♯4 – F♯4 – D♯4`
    - m. 199: `F4 – D4 – F4 – D4`
    - m. 200: `E4 – C♯4 – E4 – C♯4`
    - m. 201: `D♯4 – C4 – D♯4 – C4` (resolves on `C4`)

- **Major 3rd** (mm. 202–239):
  - **Ascending** (mm. 202–226): mirrored two-bar cells advance chromatically from C4–E4 through B4–D♯5; m. 226 completes the C5–E5 cell.
  - **Descending** (mm. 227–239, direct chromatic step-down): one four-note cell per chromatic upper pitch from E5–C5 to E4–C4. The descent retains its intentionally shorter, single-bar form.
- **Perfect 4th** (mm. 240–277):
  - **Ascending** (mm. 240–264): mirrored two-bar chromatic cells from C4–F4 through B4–E5; m. 264 completes C5–F5.
  - **Descending** (mm. 265–277): direct chromatic cells from F5–C5 to F4–C4, each five semitones.
- **Augmented 4th / Diminished 5th (Augmented 4th spelling)** (mm. 278–315):
  - **Ascending** (mm. 278–302): mirrored two-bar chromatic cells from C4–F♯4 through B4–F5; m. 302 completes C5–F♯5.
  - **Descending** (mm. 303–315): direct chromatic cells from F♯5–C5 to G♭4–C4. Each pair is six semitones and written as an augmented fourth, using simple enharmonic spellings where needed to avoid double accidentals.
