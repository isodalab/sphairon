# Changelog

All notable changes to IsodaLab SPHAIRON: Polyharmonic Geometry.

## 1.2.1 (2026-11-27)

- Part writing keeps every chord complete: all chord tones sound except,
  possibly, the fifth, so a seventh chord always keeps its seventh (and an
  added-sixth chord its sixth), as Aldwell & Schachter and Kostka & Payne
  require. Before, the search could leave the seventh out (for example the
  B of Cmaj7) when that made the voice leading smoother. With more tones
  than voices (ninth to thirteenth chords) the root, third and seventh are
  required. The voice-leading check reports any incomplete chord as an
  error. Voices, orchestration and the piano part all follow.

## 1.2.0 (2026-11-27)

- Play from anywhere: click a note, chord, rest or bar in a Realise score,
  or a bar (or its chord) in the Progression tab, and Play starts there
  (“Play from bar 2, beat 3”). The bar being played is marked in the score.
- The harmony map follows the music: while a progression or a realisation
  plays, the 2D and 3D maps show the bar being played and light the notes
  sounding, with quick, smooth transitions (instant with reduced motion).
- Tempo in Realise too; scrolling on the number steps through the
  traditional metronome markings.
- Exports no longer name the program in their content: the printed or PDF
  sheet is titled by the music, default file names are plain, and the MIDI
  tempo track is called “Tempo”. The program name stays in the file
  metadata only (SVG, PNG, MIDI, MusicXML, PDF).

## 1.1.2 (2026-11-27)

- A new icon and mark, in the flat line style of the other IsodaLab tools:
  a polychord in a sphere. A staff runs across the sphere; a teal triad on
  the lines (the lower layer) carries an amber triad in the spaces above
  (the upper layer). The two layers meet a second apart, so their
  noteheads sit on either side, as in engraving.

## 1.1.1 (2026-11-27)

- A new icon and mark: a sphere (sphaira) with two orbits, the lower
  layer (blue) and the upper layer (orange) of a polychord, three notes on
  each. It replaces the two overlapping triangles, which could read as a
  hexagram or a flag.
- Header and footer as in the other IsodaLab tools (CPX, AGM, MCA,
  ESTAVION): the SPHAIRON mark and name with “Polyharmonic Geometry” at
  the top left; at the bottom, IsodaLab | “For anyone exploring harmony on
  Earth and everywhere else”, then the copyright and the version (click it
  for About).

## 1.1.0 (2026-11-27)

**Examples and key**

- 41 example progressions, grouped: contemporary techniques first
  (hexatonic and octatonic cycles, hexatonic poles, chromatic mediants,
  dominants a minor third apart, planing, pedals, Lydian colour, sus and
  augmented chords), then jazz, classical and Romantic, and pop.
- The key is suggested from the typed chords (Krumhansl–Schmuckler key
  finding with the Krumhansl–Kessler profiles); examples set their own key.
  It can always be changed in the Key menu.

**Theory and scoring**

- Roman numerals tell a major seventh from a dominant seventh: IM7, IVM65
  (Kostka & Payne), not I7.
- The double bass is written an octave above its sound, as usual (also in
  MusicXML, with an octave transposition), and doubles the bass voice an
  octave lower.
- A moving bass line stays in the register of a bass voice (E2–C4; the
  double bass an octave lower): no more tuba or bassoon lines in the
  extreme low register. Every example is tested in every scoring with
  every bass line for practical ranges.
- New sources: Julian Hook, *Exploring Musical Spaces* (2023), and
  Krumhansl, *Cognitive Foundations of Musical Pitch* (1990).

**Interface**

- Tempo: type any value; the arrow keys and the mouse wheel step through
  the traditional metronome markings (40 … 208); a menu names the tempo
  (Largo … Prestissimo) with its range on a traditional metronome dial.
- Help → Sources lists the references without check labels; About gives
  the project's background (since 2023, inspired by Hook and Tymoczko).
- Copyright © 2023–2026. The status bar no longer repeats the privacy
  note (it stays in Help → About).
- The octaves bass line is called “Octaves (driving eighths)”.

## 1.0.0 (2026-11-26): first release

**Composing with polyharmony**

- Type a chord progression (chord symbols, slash chords) and get
  alternatives for every bar: substitute chords in context and polychords
  (upper layers), each with reasons, sources and an authority tier.
- Strata (formerly the Polyharmony Lab): ranked upper layers for any chord,
  smooth to rich; add, set, replace or remove the upper layer of any bar.
- Whole-progression polyharmonic strategies (planing, pedal, bitonal,
  tritone, mode-bound, neo-Riemannian; phasing as experimental).

**Hearing it in music (Realise)**

- Automatic part writing: SATB for the lower layer and three voices for an
  upper layer, chosen under the voice-leading rules and checked again.
- Alternatives beside the best arrangement: melody from the 3rd, 5th or
  root, close or open position, smooth bass with inversions.
- Orchestration built on the arrangement (every instrument plays one voice),
  in five scorings, with practical ranges.
- Playable piano arpeggios and repeated chords; moving bass lines (held,
  root–fifth, arpeggio, passing, walking, octaves, tonic pedal).
- Counterpoint melody (first or second species) with alternative lines.

**Analysis and geometry**

- Chord readings, set classes, available notes (Berklee and Messiaen
  lenses), substitutions, modulation routes with both Roman-numeral
  readings.
- 3D torus Tonnetz and spiral of fifths; 2D clock, circle of fifths and
  Tonnetz.

**Output**

- Print and PDF sheets; SVG, high-resolution PNG, MIDI and MusicXML export.
  Exported and printed scores are black. SVG, PNG and MIDI files carry the
  copyright in their metadata; printed and PDF pages do not.

**Quality**

- Every reference checked before release (status in Help, Sources).
- Licence inventory generated at build time (THIRD-PARTY-LICENSES.txt);
  Verovio (LGPL) kept replaceable outside the application archive.
- Offline, no telemetry; keyboard operable; dark and light themes (the
  window frame follows).

Review builds before release: 0.1.0 to 0.4.0 (same day).
