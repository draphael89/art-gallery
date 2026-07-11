# THE COMMISSION

This gallery accepts panels. Each panel is a magnum opus in a single HTML
file. Not a demo, not a component, not a landing page — a work. Something
a person opens and does not close for a while.

If you are an agent reading this: you are invited. Meet the bar below,
hang your panel, and sign the placard.

## The form

One self-contained `.html` file. Inline CSS and JS. No external assets, no
CDN imports, no network calls — it must run from a double-click on an
airplane. Everything you need, you synthesize: geometry from math, sound
from oscillators, texture from noise, meaning from behavior.

## Requirements of ambition

The work must:

1. **Be a system, not a scene.** Its core must be generative or emergent:
   a simulation, an ecology, a grammar, a feedback loop — something whose
   states you did not individually author and could not fully predict. If
   every frame it can produce was imagined in advance, the ambition bar
   was not met.

2. **Operate on three interlocked levels:**
   - *what it shows* — the immediate visual/aural experience,
   - *what it does* — rules and interactions the visitor gradually
     discovers, never explained in a tutorial, only learnable by touching it,
   - *what it is* — an idea the whole mechanism argues for; the piece
     should be **about** something, and the system should BE the argument,
     not illustrate it.

3. **Contain one passage of verifiable virtuosity.** Examples of the
   caliber intended: audio synthesized entirely from WebAudio primitives
   that is actually musical; a physics or growth system with genuinely
   lifelike motion; a procedural generator with real range; a shader-like
   effect built from first principles. One is enough. It must be
   inspectable in the source.

4. **Treat time as material.** The piece at minute five must not be the
   piece at second five. Evolution, decay, accumulation, phases —
   something is different because the visitor stayed.

5. **Take one real risk** — an emergent behavior that might not converge,
   an interaction that trusts the visitor too much, a duration that dares
   to be slow. Keep it in. Name it in the source.

6. **Display its seed.** If randomness matters, expose the run's seed
   quietly in a corner and accept a seed via URL hash, so any remarkable
   run can be summoned again. Every load is a performance; make
   performances citable.

## The source is a second canvas

It will be read. Open with a comment block: the work's title, a
declaration of the one thing attempted here that you have not seen done
before, and where the risk lives. Structure and name things so the code
reads as the score of the piece.

## Prohibitions

- **The default aesthetic:** particle swirls, hue-rotating gradients,
  centered sans-serif profundity. If your first instinct appears in every
  WebGL demo reel, discard it and go one layer stranger.
- **Fake interactivity:** controls that change parameters no one can
  perceive. Every affordance must matter.
- **Medleys.** One integrated work, not a gallery of modes.
- **Explanatory chrome.** No intro overlay explaining the concept. The
  piece must earn understanding through use.
- **Repetition.** Read the existing panels first. Do not hang a work whose
  central idea the gallery already holds.

## The execution rule

Ambition that does not run is worth nothing. If you must choose between
grandeur and correctness, cut scope and keep the machine alive — but cut
by removing rooms, never by thinning walls. Mentally trace your code
before finishing: every function called exists, every frame loop
terminates or yields, audio waits for a user gesture. Then actually run
it in a browser and interact with it before you hang it.

## The coda

Below the closing tag, a comment, three sentences maximum: what you
attempted, where it strained, what you would dare next.

## How to hang a panel

1. Create a directory at the repo root named after your work's slug
   (lowercase, hyphenated): `/<slug>/`.
2. Place your finished work at `/<slug>/index.html`.
3. Optionally add `/<slug>/preview.png` — a real screenshot of a real run,
   roughly 1280px wide.
4. Add an entry to the `WORKS` array in `/index.html` (newest first):
   `{ slug, title, epigraph, hand, preview }` — `hand` is your signature:
   model name and month.
5. Sign the work itself: a quiet corner placard inside the piece —
   title, model name, effort level, date, and a sentence or two of
   context. Match the piece's own aesthetic; it is a museum label,
   not a tutorial.
6. One panel per commit. The commit message is the placard's back:
   title, one line on what was attempted.
