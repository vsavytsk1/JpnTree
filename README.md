# JpnTree

> The language tree is the center of this workspace. This repo is the public-facing home for the kanji-tree experiments, the seed data, and the VladTrees engine pieces.

[![license](https://img.shields.io/badge/data-CC_BY--SA_4.0-blue?style=flat-square)](https://www.edrdg.org/edrdg/licence.html)
[![kanji](https://img.shields.io/badge/kanji-Grade_1_(77)-00d4ff?style=flat-square)]()

---

## What this repo is

JpnTree is an interactive kanji-learning tree built around the same visual logic as the larger MachineNet tree experiments.

Each kanji is a node. Radical families become the edges. The goal is simple:

- show the whole family at once
- let the brain spot the pattern
- grow the tree as exploration deepens

The monkey brain learns by seeing structure, not by memorizing isolated rules.

---

## Current center of gravity

This repository is now treated as the language-tree hub for the local workspace.

- [jpntree_v1.html](jpntree_v1.html) — first pass
- [jpntree_v2.html](jpntree_v2.html) — expanded iteration
- [jpntree_v3.html](jpntree_v3.html) — current working view
- [data/grade1_kanji.json](data/grade1_kanji.json) — Grade 1 seed data
- [vladtrees](vladtrees) — supporting tree engine and related assets

---

## Data sources

- KANJIDIC2 — Jim Breen / EDRDG, 1991–2026. CC BY-SA 4.0.
- Simplified JSON source: scriptin/jmdict-simplified
- Current seed: 77 Grade 1 kanji with 12 radical-family edges

---

## Tree seed (Grade 1)

```text
NATURE:
  tree -> grove -> forest
  tree -> book/origin
  tree -> village
  tree -> school
  sun  -> early
  eye  -> see
  ear  -> hear

PEOPLE:
  person -> rest
  rice field -> man
  rice field -> town
  king -> ball/jewel
```

---

## Working notes

- Keep the tree visual and legible before adding more complexity.
- Preserve the core structure of radical families.
- Use the vladtrees folder as the engine layer, not as a place for ad-hoc patching.
- Keep private Windows-folder paths and secrets out of the public repo docs.

---

## Roadmap

- [x] Establish the public language-tree center in this repo
- [ ] tighten the interactive tree experience across the three versions
- [ ] expand from Grade 1 to Grade 2 and beyond
- [ ] add vocabulary branches
- [ ] introduce richer reading/typography layers
- [ ] explore a VR/immersive version of the kanji forest

---

*Buenos Aires. June 2026.*
*The monkey loves trees. Always.*
*P=12. chi=2.*
