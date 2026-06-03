# JpnTree

> *Learn Japanese the way the monkey brain learns anything: by seeing the whole tree.*

[![license](https://img.shields.io/badge/data-CC_BY--SA_4.0-blue?style=flat-square)](https://www.edrdg.org/edrdg/licence.html)
[![kanji](https://img.shields.io/badge/kanji-Grade_1_(77)-00d4ff?style=flat-square)]()

---

## What this is

An interactive kanji learning tree built with the same engine as [MachineNet](https://github.com/vsavytsk1/Mnetv1).

Every kanji is a node. Radical families are edges.
? (tree) -> ? (grove) -> ? (forest).
The tree grows as you explore.

**The monkey brain learns by seeing shapes, not memorizing rules.**
Show it the whole family at once. Let it find the pattern.

---

## Data source

- **KANJIDIC2** -- Jim Breen / EDRDG, 1991-2026. CC BY-SA 4.0.
- Simplified JSON: [scriptin/jmdict-simplified](https://github.com/scriptin/jmdict-simplified)
- Grade 1 seed: 77 kanji, 12 radical family edges

---

## The tree (v1 seed -- Grade 1)

```
NATURE:
  ?(tree) -> ?(grove) -> ?(forest)
  ?(tree) -> ?(book/origin)
  ?(tree) -> ?(village)
  ?(tree) -> ?(school)
  ?(sun)  -> ?(early)
  ?(eye)  -> ?(see)
  ?(ear)  -> ?(hear)

PEOPLE:
  ?(person) -> ?(rest)
  ?(rice field) -> ?(man)
  ?(rice field) -> ?(town)
  ?(king) -> ?(ball/jewel)
```

---

## Files

```
data/grade1_kanji.json  -- 77 nodes, 12 edges, CC BY-SA 4.0
jpntree_v1.html         -- interactive tree (coming)
build.py                -- extract + filter from source data
```

---

## Roadmap

- [ ] v1: interactive tree HTML (same engine as MachineNet math tree)
- [ ] v2: add Grade 2 (160 kanji)
- [ ] v3: add vocabulary branches (? -> ??? Thursday)
- [ ] v4: the KARAOKE TYPOGRAPHY SYSTEM for readings
- [ ] v5: Quest 3 VR -- walk through the kanji forest

---

*Buenos Aires. June 2026.*
*The monkey loves trees. Always.*
*P=12. chi=2.*
