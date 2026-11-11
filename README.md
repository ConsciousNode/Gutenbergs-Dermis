# Gutenberg's Dermis

**The fingerprint printing press.** An experimental morphogenesis lab that grows fingerprint ridge patterns from a reaction–diffusion (Turing) model. It follows Glover et al. (2023, *Cell*), where activator (WNT/EDAR) and inhibitor (BMP) fields form ridges that spread as waves from initiation sites on the fingertip. Where those wavefronts start and collide decides the pattern: arch, loop, whorl or tented arch.

Open `index.html` in any browser, or visit the GitHub Pages site. Offline, single-file, zero-dependency (Xinu).

- **Presets:** arch, loop, whorl, tented arch, EDAR ablation, and a custom sandbox.
- **Controls:** reaction–diffusion kinetics, digit anatomy, and draggable wave initiation sites.
- **Views:** activator, inhibitor, combined, a press-ink ridge map, wavefronts and the anatomy substrate.
- **Deterministic:** seeded (Mulberry32), with config JSON import/export and PNG prints.
- **Note:** it simulates pattern formation, not real tissue or anyone's actual prints.

## Checks (Kehai Interim, 2026-11-11)

This was a first-look check, not a full audit. The page loads with 0 console errors, and the built-in self-test suite reports **10/10 passed** (whorl preset, seed 4210, a 23-component ridge map).

MIT License · ConsciousNode SoftWorks
