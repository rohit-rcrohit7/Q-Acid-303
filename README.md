<p align="center">
  <img src="banner.svg" alt="Q-ACID 303 — Quantum Acid Machine" width="100%"/>
</p>

<p align="center">
  <strong>A non-deterministic acid machine powered by quantum mechanics.</strong><br>
  <em>7-track drum machine · authentic 303 bass synth · quantum physics · all in one HTML file.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-3.1-39ff14?style=flat-square&labelColor=0a0a0e" alt="Version"/>
  <img src="https://img.shields.io/badge/PWA-installable-bf00ff?style=flat-square&labelColor=0a0a0e" alt="PWA"/>
  <img src="https://img.shields.io/badge/dependencies-zero-00d4ff?style=flat-square&labelColor=0a0a0e" alt="No dependencies"/>
  <img src="https://img.shields.io/badge/export-WAV%20%7C%20MIDI-ff3c00?style=flat-square&labelColor=0a0a0e" alt="Export"/>
  <img src="https://img.shields.io/badge/created%20by-SheffRave-39ff14?style=flat-square&labelColor=0a0a0e" alt="Created by SheffRave"/>
</p>

---

## What is this

Every drum machine and sequencer ever made is deterministic — you program a pattern, press play, it plays back the same thing. Every time.

Q-ACID 303 isn't. It applies quantum mechanical principles to music sequencing. Steps can exist in **superposition** (all possible states at once), **collapse** when observed into patterns that have roughly a 10⁻²⁸ chance of ever repeating, and instruments can be **entangled** so their states are instantly correlated.

It's a working instrument — you can make music with it, export WAV and MIDI files, and perform live. It's also a science project exploring what happens when the rules of quantum physics become the rules of musical composition.

One HTML file. No dependencies. No install. No server.

---

## What's new in 3.1

- **7-track drum machine** — kick, snare, clap, hat, open hat, ride and perc are now fully independent tracks. Have any or all playing simultaneously. Show/hide each via the "+ ADD TRACK" buttons.
- **Rebuilt 303 engine** — cascaded two-pole filter, pre-filter tanh saturation via new **Drive** knob, exponential envelope, legato slides with no envelope retrigger. Much closer to real 303 squelch.
- **Upgraded drum sounds** — 3-layer kick (body + click + sub), two-band snare with detuned triangles, six-oscillator 808-style metallic hats, proper 909 clap, ride with bell harmonics.
- **Quantum gates** — Hadamard (H) for random-phase superposition with interference, Pauli-X (X) for bitflip inversion, Zeno effect (⟨Zeno⟩) to freeze quantum states through continuous observation.
- **Upgraded Bell entanglement** — kick↔bass now has proper anti-correlation. Bass is suppressed when the entangled kick step doesn't fire.
- **Phase-weighted collapse** — quantum states now carry complex phase amplitudes. Collapse probability uses cos²(φ/2) bias.

---

## Features

### Instruments

**7 independent drum tracks**, any or all active simultaneously:
- **Kick** — saturated sine sweep + click + sub punch
- **Snare** — two-band noise + detuned triangle body
- **Clap** — three bursts + reverberant tail (909-style)
- **Hat** — six-oscillator inharmonic metallic (808-style)
- **Open Hat** — long-tail version of the hat engine
- **Ride** — bell harmonics + metallic noise sustain
- **Perc** — low tom / floor thud + noise attack

**303 acid bass synth** — sawtooth/square/triangle/sine oscillators, resonant cascaded low-pass filter, pre-filter saturation (Drive), sub-oscillator, portamento/glide, true legato slides

**Full envelope** — attack, decay, release, per-step accent (affects cutoff/reso/decay/gain together), env mod

**15 preset templates** — from classic acid to London-style 32-step phrases, all now using the 7-track system where appropriate

### Effects

Distortion · Delay with feedback · Reverb · Phaser · Sidechain compression

### Quantum Engine

**Core:**
- **Superposition** — steps exist as all possible hits simultaneously
- **Wave function collapse** — observation locks indeterminate steps into fixed values
- **Bell entanglement** — kick and bass linked with proper anti-correlation (|Φ+⟩ state)
- **Decoherence** — quantum states gradually degrade over time, patterns crystallise from chaos
- **Weighted probability** — shape collapse distributions with scale presets (minor, pentatonic, blues)
- **Observer effect** — slider that live-modulates filter, note range, and trigger probability

**Quantum gates (advanced):**
- **Hadamard (H)** — equal superposition with random phases; enables interference-weighted collapse
- **Pauli-X (X)** — bitflip gate, inverts classical states leaving quantum ones untouched
- **Zeno effect** — continuous observation pins quantum states; superposed steps mostly stay silent while active

### Production

- **WAV export** — render 1, 4, 8, or 16 bars to 16-bit WAV (all 7 drum tracks rendered through full effects chain)
- **MIDI export** — export to General MIDI with drums on channel 10, bass on channel 1, proper GM drum mapping for all 7 tracks
- **4 pattern banks** — switch between patterns live
- **Tap tempo** — set BPM by feel
- **32-step mode** — two-bar phrases for longer sequences
- **Per-track mute/solo** — independent M/S on all 8 tracks (7 drums + bass)
- **Per-step velocity** — VEL mode lets you drag to set individual hit velocity
- **Per-step probability** — PROB mode cycles 100 → 75 → 50 → 25 → 100
- **Fill** — hold button for a temporary busy fill pattern
- **Preset save/load** — localStorage-backed with v2 format including track visibility
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
3. **Add more drum tracks** — scroll to the bottom of the drum machine, click "+ ADD TRACK" buttons for clap, open hat, ride, perc
4. **Pick a template** from the Templates section — most now include multiple drum tracks
5. **Twist the synth knobs** — Cutoff, Resonance and **Drive** change the sound the most
6. **Hit ⟨ψ⟩ Quantum** on a section, click empty steps — they go purple and resolve differently each loop
7. **Try the quantum gates** — H puts everything in superposition with interference, X inverts classical states, ⟨Zeno⟩ freezes the current quantum state
8. **Export** when you land on something you like — WAV for audio, MIDI for your DAW

### Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Stop |
| `T` | Tap tempo |
| `↑` `↓` | BPM ±1 |
| `←` `→` | Switch pattern bank |

---

## Templates

| Name | BPM | Steps | Tracks used | Style |
|------|-----|-------|-------------|-------|
| Classic Acid | 138 | 16 | kick, snare, hat | Four-on-the-floor, squelchy 303 |
| Hard Acid | 150 | 16 | +clap, +openhat | Pounding kicks, screaming resonance |
| Minimal Quantum | 140 | 16 | kick, snare, hat | Sparse beats, heavy quantum uncertainty |
| Warehouse Rave | 148 | 16 | +clap, +openhat | Relentless 4/4, offbeat hats |
| Dark Acid | 134 | 16 | +ride | Menacing low-end, slow filter sweeps |
| Square Acid | 142 | 16 | kick, snare, hat | Square wave, heavy sub |
| London Acid | 145 | 16 | +perc | SUF-style relentless 303 workout |
| Squat Party | 145 | 16 | +clap | Gritty broken hats, heavy slides |
| 303 Disorder | 146 | 16 | kick, snare, hat | Shredded acid line, tight loop |
| Acid Freight | 143 | 16 | +perc | Rolling percussion, chugging bass |
| London 32 | 145 | 32 | +perc | Two-bar phrase, building second half |
| Squat 32 | 145 | 32 | +clap | Two-bar breakdown into drop |
| Disorder 32 | 146 | 32 | kick, snare, hat | Two-bar shredded acid |
| Freight 32 | 143 | 32 | +ride | Two-bar rolling builder |
| Quantum Chaos | 155 | 16 | kick (rest superposed) | Everything superposed |

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

v3.1 adds phase amplitudes — each superposed step carries a complex phase φ:

```
|step⟩ = cos(φ/2)|on⟩ + e^(iφ) sin(φ/2)|off⟩
```

Collapse probability uses the phase bias: P(on) ∝ cos²(φ/2). The Hadamard gate randomises these phases, creating interference patterns.

**Bell state entanglement** (kick ↔ bass):

```
|Φ+⟩ = (|kick⟩|bass⟩ + |silence⟩|silence⟩) / √2
```

Measuring the kick instantly determines the bass — not just "kick-on correlates bass-on" but also "kick-off correlates bass-off". This is why entanglement sounds different from simple triggering.

**Probability of two identical 112-step (16 × 7) collapses:**

```
P(identical) ≈ 10⁻⁴⁰
```

More tracks, less repeatability. The chance of hearing the same pattern twice is effectively zero.

**Decoherence** modelled as density matrix decay:

```
ρᵢⱼ(t) → ρᵢⱼ(0)·e⁻ᵗ/τ        τ = decoherence time
```

**Quantum Zeno effect** — continuous observation projects the state onto the current measurement basis at every timestep, effectively freezing it. In the sequencer this means superposed steps stay near their current state while Zeno is active.

Currently running on pseudorandom number generation. Connecting to quantum hardware (IBM Quantum, etc.) would make the randomness genuinely irreducible.

---

## Tech

- **Audio**: Web Audio API — oscillators, filters, waveshapers, convolution reverb, offline rendering
- **Synthesis**: cascaded two-pole low-pass filter with pre-filter tanh saturation, sub-oscillator, exponential envelopes (303 emulation)
- **Drums**: synthesized from oscillators and noise buffers, shared buffer cache for performance
- **Effects**: distortion → 4-stage allpass phaser → delay with feedback → convolution reverb → sidechain compressor
- **Export**: OfflineAudioContext → 16-bit PCM WAV encoding; custom MIDI SMF Type 0 encoder with variable-length delta times
- **Quantum**: phase-amplitude collapse, density matrix decoherence, Bell state entanglement with anti-correlation, quantum Zeno projection
- **Interface**: single-file HTML/CSS/JS, zero dependencies, PWA-enabled
- **Size**: ~160KB total

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
