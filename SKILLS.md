# Interval accuracy

Before naming an interval or writing an interval extension, count the semitone distance explicitly. Do not infer the quality solely from letter names or direction.

- Major second: 2 semitones
- Minor third: 3 semitones
- Major third: 4 semitones
- Augmented fourth / Tritone: 6 semitones

For a descending interval, count downward from the starting note. Example: B♭ down to G is 3 semitones (a minor third); a major third below B♭ is G♭, 4 semitones below.

State the semitone count when confirming a proposed interval sequence, and check every derived note before adding it to a score.

# Enharmonic spelling (interval study)

Count semitone distance first (see Interval accuracy), then choose the letter names.

The two notes of an oscillating pair must sit on different staff degrees (line vs neighbouring space). Do not spell a semitone as the same letter with an accidental (C–C♯, D–D♯, F–F♯, B–B♭).

- **Ascending:** spell the lowest pitch first. Chromatic lowest notes are sharps (C♯, D♯, F♯, G♯, A♯). The upper note takes the spelling that leaves that degree (often a flat).
  - Example: `C4 – D♭4 – C4 – D♭4` | `D4 – C♯4 – D4 – C♯4`
- **Descending:** spell the highest pitch first. Chromatic highest notes are flats (D♭, B♭, A♭, G♭, E♭). The lower note takes the spelling that leaves that degree (often a sharp).
  - Example: `D♭5 – C5 – D♭5 – C5`, then `C5 – B4 – C5 – B4`, then `B4 – A♯4 – B4 – A♯4`

This rule applies to the interval study (`scratchpad.md` section 02). It does not change key-signature diatonic spelling in Part 1, and it does not rewrite the chromatic-frame cells unless those sequences are revised separately.

# Scratchpad exercise structure

- End every scratchpad cell with a quarter note C5 and begin the next cell immediately with a repeated C5 across the barline; do not use rests or minims.

# Instruction-scope abstraction

Maintain a strict distinction between representing an instruction and executing it:

- **Representation (Specification & Analysis)**: Defining, drafting, or verifying exercise designs, prompt text, and interval/semitone mathematics without altering canonical scores or repository state.
- **Execution (Scoring & Rendering)**: Applying changes to MusicXML files, rendering PDFs, or modifying scores only after proposed sequences and designs have been verified and confirmed.

# Chromatic frame pattern structure

Start at the tonic center (C5), descend chromatically to the lower boundary, ascend chromatically all the way through center to the upper boundary, then descend chromatically back to center (C5):

- **Cell 1 (±1 semitone: B4 to C♯5)**:  
  - Full sequence (12 notes): `C5 – B4 – C5 – C♯5 – C5 – B4 – C♯5 – C♯5 – D♯5 – B4 – A4 – C5`
- **Cell 2 (±2 semitones: B♭4 to D5)**:  
  - Full sequence (16 notes): `C5 – B4 – B♭4 – B4 – C5 – C♯5 – D5 – C♯5 – C5 – B♭4 – D5 – D5 – F♯5 – B♭4 – G♭4 – C5`
- **Cell 3 (±3 semitones: A4 to D♯5)**:  
  - Full sequence (20 notes): `C5 – B4 – B♭4 – A4 – B♭4 – B4 – C5 – C♯5 – D5 – D♯5 – D5 – C♯5 – C5 – A4 – D♯5 – D♯5 – A5 – A4 – D♯4 – C5`
