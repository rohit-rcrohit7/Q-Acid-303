<p align="center">
  <img src="banner.svg" alt="Q-ACID 303 — Quantum Acid Machine" width="100%"/>
</p>

<p align="center">
  <strong>A non-deterministic acid machine powered by quantum mechanics.</strong><br>
  <em>Drum sequencer · 303 bass synth · quantum physics · all in one HTML file.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-3.0-39ff14?style=flat-square&labelColor=0a0a0e" alt="Version"/>
  <img src="https://img.shields.io/badge/PWA-installable-bf00ff?style=flat-square&labelColor=0a0a0e" alt="PWA"/>
  <img src="https://img.shields.io/badge/dependencies-zero-00d4ff?style=flat-square&labelColor=0a0a0e" alt="No dependencies"/>
  <img src="https://img.shields.io/badge/export-WAV-ff3c00?style=flat-square&labelColor=0a0a0e" alt="WAV Export"/>
  <img src="https://img.shields.io/badge/created%20by-SheffRave-39ff14?style=flat-square&labelColor=0a0a0e" alt="Created by SheffRave"/>
</p>

---

## What is this

Every drum machine and sequencer ever made is deterministic — you program a pattern, press play, it plays back the same thing. Every time.

Q-ACID 303 isn't. It applies quantum mechanical principles to music sequencing. Steps can exist in **superposition** (all possible states at once), **collapse** when observed into patterns that have roughly a 10⁻²⁸ chance of ever repeating, and instruments can be **entangled** so their states are instantly correlated.

It's a working instrument — you can make music with it, export WAV files, and perform live. It's also a science project exploring what happens when the rules of quantum physics become the rules of musical composition.

One HTML file. No dependencies. No install. No server.

---

## Features

### Instruments
- **16/32 step drum machine** — kick, snare, hi-hat with per-step programming
- **303 acid bass synth** — sawtooth/square/triangle/sine oscillators, resonant low-pass filter, sub-oscillator, portamento/glide
- **Full ADSR envelope** — attack, decay, release, accent, env mod
- **11 preset templates** — from classic acid to London-style 32-step phrases

### Effects
- Distortion · Delay with feedback · Reverb · Phaser · Sidechain compression

### Quantum Engine
- **Superposition** — steps exist as all possible hits simultaneously
- **Wave function collapse** — observation locks indeterminate steps into fixed values
- **Entanglement** — kick and bass linked by non-separable quantum correlations
- **Decoherence** — quantum states gradually degrade over time, patterns crystallise from chaos
- **Weighted probability** — shape collapse distributions with scale presets (minor, pentatonic, blues)
- **Observer effect** — slider that live-modulates filter, note range, and trigger probability

### Production
- **WAV export** — render 1, 4, 8, or 16 bars to 16-bit WAV
- **4 pattern banks** — switch between patterns live
- **Tap tempo** — set BPM by feel
- **32-step mode** — two-bar phrases for longer sequences
- **Keyboard shortcuts** — space, arrows, tap tempo

### Science Modules
- Wave function visualiser (superposition, collapsed, interference, decoherence views)
- Entangled pair experiment
- Observer effect with live probability display
- Quantum statistics — collapse counter, Shannon entropy, decoherence events

---

## Use it

### Online
👉 **[Launch Q-ACID 303](https://rohit-rcrohit7.github.io/Q-Acid-303/)** 

### Local
Download `index.html` and open it in any modern browser. That's it.

### Install as app
On mobile or desktop, open the URL and use your browser's "Add to Home Screen" or "Install App" option. It works offline once installed.

---

## Quick start

1. **Press SPACE** to play (loads with a pattern ready)
2. **Click steps** in the grid to toggle beats on/off
3. **Pick a template** from the Templates section
4. **Twist the synth knobs** — Cutoff and Resonance change the sound the most
5. **Hit ⟨ψ⟩ Quantum** on a section, click empty steps — they go purple and resolve differently each loop
6. **Superpose All** for full indeterminacy, **Collapse** to freeze a pattern
7. **Export** when you land on something you like

### Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Stop |
| `T` | Tap tempo |
| `↑` `↓` | BPM ±1 |
| `←` `→` | Switch pattern bank |

---

## Templates

| Name | BPM | Steps | Style |
|------|-----|-------|-------|
| Classic Acid | 138 | 16 | Four-on-the-floor, squelchy 303 |
| Hard Acid | 150 | 16 | Pounding kicks, screaming resonance |
| Minimal Quantum | 140 | 16 | Sparse beats, heavy quantum uncertainty |
| Warehouse Rave | 148 | 16 | Relentless 4/4, offbeat hats |
| Dark Acid | 134 | 16 | Menacing low-end, slow filter sweeps |
| Square Acid | 142 | 16 | Square wave, heavy sub |
| London Acid | 145 | 16 | SUF-style relentless 303 workout |
| Squat Party | 145 | 16 | Gritty broken hats, heavy slides |
| 303 Disorder | 146 | 16 | Shredded acid line, tight loop |
| Acid Freight | 143 | 16 | Rolling percussion, chugging bass |
| London 32 | 145 | 32 | Two-bar phrase, building second half |
| Squat 32 | 145 | 32 | Two-bar breakdown into drop |
| Disorder 32 | 146 | 32 | Two-bar shredded acid |
| Freight 32 | 143 | 32 | Two-bar rolling builder |
| Quantum Chaos | 155 | 16 | Everything superposed |

---

## The physics

Each sequencer step can be represented in Dirac notation:

```
|step⟩ = α|on⟩ + β|off⟩       where |α|² + |β|² = 1
```

For bass notes, superposition extends across the note space:

```
|bass⟩ = Σᵢ cᵢ|noteᵢ⟩         coefficients shaped by probability weights
```

Probability of two identical 64-step collapses:

```
P(identical) ≈ (0.6)¹⁶ × (0.5)¹⁶ × (0.65)¹⁶ × (1/7)¹⁶ ≈ 10⁻²⁸
```

Decoherence modelled as density matrix decay:

```
ρᵢⱼ(t) → ρᵢⱼ(0)e⁻ᵗ/τ        τ = decoherence time
```

Currently running on pseudorandom number generation. Connecting to quantum hardware (IBM Quantum, etc.) would make the randomness genuinely irreducible.

---

## Tech

- **Audio**: Web Audio API — oscillators, filters, waveshapers, convolution reverb, offline rendering
- **Synthesis**: Sawtooth/square/triangle/sine + sub-oscillator through resonant LP filter (303 emulation)
- **Effects**: Distortion → 4-stage allpass phaser → delay with feedback → convolution reverb → sidechain compressor
- **Export**: OfflineAudioContext → 16-bit PCM WAV encoding
- **Interface**: Single-file HTML/CSS/JS, zero dependencies, PWA-enabled
- **Size**: ~85KB total

---

## Browser support

Works in any modern browser with Web Audio API:
- Chrome / Edge 
- Firefox
- Safari (iOS and macOS)
- Samsung Internet

---

## License

© 2026 **SheffRave**. All rights reserved.

Created by SheffRave. Q-ACID 303 is an original work. Unauthorised reproduction, distribution, or commercial use without permission is prohibited.
