# Electribe ES-1 — Pattern Change

Web MIDI pattern changer for the Korg Electribe ES-1, designed for mobile browsers.

## Features

- **Pattern selection**: 1–128 patterns (Bank A: 1–64, Bank B: 65–128)
- **MIDI**: Program Change only (no Bank Select needed for ES-1)
- **8-slot chain**: Build a sequence of patterns with repeat counters (×1 to ×9)
- **Chain playback**: Auto-plays with 4-second delay between patterns, loops support
- **Quick jump**: Instant access to common patterns
- **Mobile-first**: Dark theme, responsive, works on phone browsers

## Requirements

- Korg Electribe ES-1 connected via USB-MIDI interface
- Chrome on Android (Web MIDI API) or desktop Chrome
- iOS has limited Web MIDI support

## Usage

1. Connect USB-MIDI interface → ES-1 MIDI IN
2. Open the page in Chrome
3. Select a chain slot, enter a pattern number, tap GO
4. Or tap a quick jump button for instant access
5. Build a chain sequence and tap Play Chain

## MIDI Mapping

- ES-1 patterns: 1–128
- Bank A: PC 0–63
- Bank B: PC 64–127
- No Bank Select CCs required
