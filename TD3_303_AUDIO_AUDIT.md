# ACID-08 TD-3 comparison: experimental 303 filter mode

This branch contains **ACID-08-v1.4.0-PWA-Source.zip**, built from the original v1.3.9 archive without overwriting it.

## Changes
- A selectable **303** filter mode, beside LPF and BPF.
- Two 12 dB/oct low-pass sections in cascade (~24 dB/oct), with mild prefilter saturation, gentler resonance scaling, and longer, more musical filter-envelope motion.
- Cleaner dry/wet blend at high distortion in 303 mode.
- Previous LPF/BPF route and original envelope preserved for an A/B comparison.
- Older saved projects remain on their selected mode; new projects default to 303.

## Validation and limits
Archive structure and unchanged entry compressed payloads are preserved; modified files are stored with new CRC-32 values. **No realtime Android/Web Audio listening or automated app tests have been performed yet**. This is an audition candidate, not a confirmed TD-3 sound match.

## First A/B test
Use SAW / 303; cutoff 30%, resonance 75%, env mod 65%, decay 50%, accent 50%, distortion 20%. Switch 303/LPF without changing pattern or levels. TD-3 microphone recording and screen capture cannot support direct spectral equality claims.

Original v1.3.9 archive remains intact on main.
