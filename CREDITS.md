# Image credits

Attribution record for the images served from the **`valence_quiz_images`** repo.

## Filename convention

Every filename starts with a **provenance prefix**, so the folder sorts into groups and you can see an
image's licence status without opening it:

| Prefix | Meaning | Attribution |
|---|---|---|
| `pd_` | Public domain / CC0 | none needed |
| `ccby_` | CC BY | **required** — credit strip stamped on the image + listed below |
| `ccbysa_` | CC BY-SA | **required** + ShareAlike applies to modifications |
| `gen_` | Generated for this course | none — our own work |
| `own_` | Instructor's own photo/diagram | none — yours |
| `canvas_` | Carried over from the Canvas export, **provenance unverified** | ⚠️ review before relying on it |

`canvas_*` files are named `canvas_<quiz>_<nn>` after a quiz that uses them. **They are the open to-do
list:** as each is reviewed it either becomes `own_` (confirmed yours) or is replaced and becomes
`pd_` / `ccby_` / `gen_`. When no `canvas_` files remain, the copyright review is complete.
Use `_INVENTORY.html` to review them visually; policy is in `_SOURCING.md`.

---

## Public domain / CC0 — no attribution required

Sourced from Wikimedia Commons under the **"No restrictions"** licence filter. Listed for provenance only.

| File | Depicts | Source | Licence |
|---|---|---|---|
| `pd_periodic-table.png` | Periodic table of the elements | [Simple Periodic Table Chart-en.svg](https://commons.wikimedia.org/wiki/File:Simple_Periodic_Table_Chart-en.svg) | CC0 / Public domain |
| `pd_bunsen-burner.jpg` | Bunsen burner (labelled AIR/GAS) | [Bunsen Burner (PSF).jpg](https://commons.wikimedia.org/wiki/File:Bunsen_Burner_(PSF).jpg) | Public domain (Pearson Scott Foresman donation) |
| `pd_erlenmeyer-flask.png` | Erlenmeyer flask | Erlenmeyer Flask (Filled) — NIH BioArt 631/660919 | Public domain (US Government work) |
| `pd_prism-dispersion.gif` | Prism dispersing white light | [Light dispersion conceptual.gif](https://commons.wikimedia.org/wiki/File:Light_dispersion_conceptual.gif) | PD-self |
| `pd_beaker.jpg` | Beaker | Wikimedia Commons | Public domain / CC0 |
| `pd_test-tubes.jpg` | Test tubes in a rack | Wikimedia Commons | Public domain / CC0 |
| `pd_volumetric-flask.jpg` | Volumetric flask | Wikimedia Commons | Public domain / CC0 |
| `pd_bohr-photon-emission.png` | Atom emitting a photon (Bohr model) | Wikimedia Commons | Public domain / CC0 |

## CC BY — attribution required

| File | Depicts | Source | Author | Licence |
|---|---|---|---|---|
| `ccby_em-spectrum.png` | Electromagnetic spectrum (gamma → radio) | ["Electromagnetic spectrum.gif"](https://commons.wikimedia.org/wiki/File:Electromagnetic_spectrum.gif), Wikimedia Commons | Unknown author (not supplied) | **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0)** |

**Attribution as used:** a credit strip is stamped along the bottom of the image itself, reading
`"Electromagnetic spectrum" (Wikimedia Commons, author unknown) - CC BY 4.0`, so the credit travels with
the image into every quiz that displays it.
*Modification note (per CC BY): converted GIF → PNG and this attribution strip was added; the diagram
itself is unaltered.*

**CC BY 4.0 in plain terms:** free to use, share, and adapt — even commercially — with **no ShareAlike**,
so it imposes nothing on Valence's code or these quizzes. The sole obligation is credit: the creator's
name (where supplied), a link to the source, the licence name + link, and a note if modified. All
satisfied above. Where no author is supplied, crediting title + source + licence is a complete attribution.

## Generated for this course — no third-party rights

| File | Depicts | Why generated |
|---|---|---|
| `gen_visible-light-spectrum.png` | Visible spectrum, 400–700 nm | No suitable PD/CC0 Commons version found. Replaces four copies of a watermarked sciencenotes.org graphic. |
| `gen_polyatomic-ions.png` | Polyatomic ion reference table | No Commons equivalent — it's this course's specific ion list. |
| `gen_em-spectrum-no-numbers-cb.png` | EM spectrum, regions labelled, **no numeric values** | Colour-blind-safe rebuild of an image Canvas never bundled. Used by 29 questions. |
| `gen_em-spectrum-cb.png` | EM spectrum **with wavelengths** (for c = λν) | Colour-blind-safe rebuild of an image Canvas never bundled. |
| `gen_visible-ranges-cb.png` | Visible colours **named + nm ranges** | Colour-blind-safe rebuild of an image Canvas never bundled. |
| `gen_d-block-orbital-d3.png` | d sublevel: 5 orbital boxes, 3 electrons (d³) | Rebuild of an image Canvas never bundled. |

**Accessibility note.** The four `*-cb` images replace the instructor's own colour-blind-safe variants,
which Canvas referenced but failed to export. They are rebuilt to be genuinely colour-blind-safe:
**every band carries a text label** (and the EM regions are greyscale-distinct), so colour is never the
only channel carrying information. A student with colour-vision deficiency can answer "which colour has
the shortest wavelength?" from the labels alone.

## Carried over from Canvas — `canvas_*` (107 files)

Provenance unverified: these came with the original Canvas course export and are a mix of the
instructor's own work and generic/functional diagrams. Review them in `_INVENTORY.html` and re-tag as
above. Anything that turns out to be a stock photo or a distinctive third-party infographic should be
replaced — during this migration we already removed a **Getty-watermarked** photo and four copies of a
**sciencenotes.org** graphic.
