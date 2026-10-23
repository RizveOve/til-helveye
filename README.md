# Til helvete

A 3D browser game set in a rainy Oslo. Rent an e-scooter, smash café tables and electric cars, dodge trams and buses, and outrun the neighbourhood Facebook group and the mounted police.

**Play:** https://rizveove.github.io/til-helveye/ (or open `index.html` in a browser).

## Controls

| Action | Keyboard | Phone |
|---|---|---|
| Throttle | W / ↑ | Gass |
| Brake / reverse | S / ↓ | Brems |
| Steer | A D / ← → | ◀ ▶ |
| Boost | Shift / Space | Boost |
| Horn | H | Tut |
| Sound bomb | B | Bombe |
| Sound on/off | M | Lyd |

## Voice lines

All voice lines are recorded clips. The source files are in `sounds/` (listed by category in `sounds/sounds.json`) and are embedded in `index.html`, so the game works anywhere, even opened as a local file. They were generated with the Piper Norwegian voice *talesyntese* (trained on Språkbanken data, CC0), with pitch and effects to make different characters.

To use your own recordings, replace the files in `sounds/` and ask for the clips to be re-embedded in `index.html`. Only use clips you recorded yourself or have permission to use.

## Tech

Three.js (r128 from cdnjs), a procedurally generated city, hand-written collision, Web Audio synthesis for all sound effects, and the browser's speech synthesis for the Norwegian voice lines. No build step: everything is in `index.html`.

Inspired by *Baper Rasta* by Omar Faruqe Riyad.
