# Changelog

All notable changes to the Circle of Fifths Trainer are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and the project uses [Semantic Versioning](https://semver.org/).

## [0.1.0] - 2026-10-10

### Added
- Circle of fifths with three rings: 12 major key positions (15 keys, including the
  enharmonic pairs B / C♭, F♯ / G♭, C♯ / D♭), the sharp/flat count for each key,
  and the relative minor keys.
- Grand staff showing the selected key signature in correct positions on both staves,
  drawn with Bravura glyphs. Updates when a major key, minor key, or count is clicked.
- Order of Sharps and Order of Flats lists above the staff, highlighting the
  accidentals in the selected key.
- "Build it step by step" button that adds the accidentals one at a time, with
  "Show all" to jump to the complete signature.
- Show/hide toggles for major keys and minor keys. Hidden labels keep their slots
  and reappear for the selected key, so the circle doubles as a self-test.
- List view: a table of all 15 keys with the same selection behavior as the circle.
- Tonic triad playback on selection (Tone.js + Salamander Grand Piano), with a
  one-click audio toggle.
- Keyboard navigation (arrow keys around and between rings, Enter/Space to select),
  screen-reader labels and announcements, and a visible warning if the music font
  fails to load.
- Display choices (rings shown, view, audio) remembered in the browser.
