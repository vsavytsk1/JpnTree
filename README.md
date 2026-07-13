# JpnTree

> **The language tree.** Kanji radicals, multilingual etymology, and a full Age-of-Empires-II language-learning game -- all in self-contained HTML, no frameworks, no installs. Clone and open.

[![pages](https://img.shields.io/badge/live-vsavytsk1.github.io/JpnTree-00d4ff?style=flat-square)](https://vsavytsk1.github.io/JpnTree/)
[![license](https://img.shields.io/badge/code-MIT-green?style=flat-square)](LICENSE)
[![data](https://img.shields.io/badge/data-CC_BY--SA_4.0-blue?style=flat-square)](https://www.edrdg.org/edrdg/licence.html)

---

## Quick start

```
git clone https://github.com/vsavytsk1/JpnTree.git
cd JpnTree
# open index.html in any browser -- every page is self-contained
```

Or visit the live site: **[vsavytsk1.github.io/JpnTree](https://vsavytsk1.github.io/JpnTree/)**

---

## What is in this repo

Three projects live here, united by one thesis: **the monkey brain learns by seeing structure, not memorizing rules.**

### 1. JpnTree -- kanji radical families

Interactive kanji-learning tree. Each kanji is a node. Radical families are edges. Click to reveal the family; type a sentence and watch the kanji light up.

| Version | What it does |
|---------|-------------|
| [jpntree_v1.html](https://vsavytsk1.github.io/JpnTree/jpntree_v1.html) | click to reveal radical family, pan+zoom, the seed |
| [jpntree_v2.html](https://vsavytsk1.github.io/JpnTree/jpntree_v2.html) | sentence mode -- type eng/jpn/spanish, kanji light up |
| [jpntree_v3.html](https://vsavytsk1.github.io/JpnTree/jpntree_v3.html) | stepper, line color, 77 Grade 1 kanji -- **current** |

Data: 77 Grade 1 kanji, 12 radical-family edges. Source: KANJIDIC2 (Jim Breen / EDRDG, CC BY-SA 4.0).

### 2. vladTrees -- multilingual etymology engine

Six languages (ES/EN/PT/RU/UA/GR) on one tree. Each concept shows the word in your home tongue and the deep root (PIE/Greek/Latin) underneath. Cognate dots show where the branch broke. Plus: fog-of-war language hunts and language-physics kernel sims.

| Page | What it does |
|------|-------------|
| [VladTree](https://vsavytsk1.github.io/JpnTree/vladtrees/VladTree.dc.html) | the etymology tree -- 6 languages, deep roots, cognate dots |
| [VladBush / La Selva](https://vsavytsk1.github.io/JpnTree/vladtrees/VladBush.dc.html) | fog-of-war language hunt, catch the tiger, age advancement |
| [The Bush EN](https://vsavytsk1.github.io/JpnTree/vladtrees/VladTree_EN_Bush.dc.html) | english fog-of-war, scout the bush |
| [La Selva ES](https://vsavytsk1.github.io/JpnTree/vladtrees/VladTree_ES_Saturation.dc.html) | spanish saturation mode |
| [Kernel: Entrenchment](https://vsavytsk1.github.io/JpnTree/vladtrees/Kernel_Entrenchment.dc.html) | why L2 is uphill -- Hopfield energy landscape, the marble |
| [Kernel: TheLine](https://vsavytsk1.github.io/JpnTree/vladtrees/Kernel_TheLine.dc.html) | Yerkes-Dodson run-or-stay threshold, arousal vs learning rate |

### 3. Age of Lenguages -- learn a tongue like you master AoE2

A language is a civilisation. You learn it the way you master Age of Empires II -- not by memorising rules, but by seeing the whole tech tree, paying the real price for every unit, and drilling the counters until the monkey routes them automatically. **The goal is ELO 2000 in Hellenic.**

| Version | What it does |
|---------|-------------|
| [v1.1 -- The Tech Tree](https://vsavytsk1.github.io/JpnTree/aoe/AgeOfLenguages_v1.1.html) | civ = language, unit = structure, nodes + edges = the dependency graph |
| [v1.2 -- The War Council](https://vsavytsk1.github.io/JpnTree/aoe/AgeOfLenguages_v1.2.html) | draft an army, live cost meter, verdict, earnable badge |
| [v1.9 -- THE CLICK](https://vsavytsk1.github.io/JpnTree/aoe/AgeOfLenguages_v1.9_TheClick.html) | click-command = recall rep, survival stakes, combo dopamine -- **current** |
| [v2.2 -- High Ground](https://vsavytsk1.github.io/JpnTree/aoe/AgeOfLenguages_v2.2_HighGround.html) | elevation, siege, blast -- frozen dead-end (Path X: publish the dead ends too) |

The full design thesis is in [`scrolls/AgeOfLenguages.md`](scrolls/AgeOfLenguages.md). The AoE2 deep-research receipts are in [`scrolls/AgeTITANSbalance.md`](scrolls/AgeTITANSbalance.md) and [`scrolls/AOE2bowTITANs.md`](scrolls/AOE2bowTITANs.md).

---

## Folder structure

```
JpnTree/
  index.html                  -- landing page (links to everything)
  jpntree_v1.html             -- kanji tree v1
  jpntree_v2.html             -- kanji tree v2
  jpntree_v3.html             -- kanji tree v3 (current)
  data/
    grade1_kanji.json         -- 77 Grade 1 kanji seed data
  vladtrees/
    VladTree.dc.html          -- multilingual etymology tree
    VladBush.dc.html          -- fog-of-war language hunt
    VladTree_EN_Bush.dc.html  -- english bush
    VladTree_ES_Saturation.dc.html -- spanish saturation
    Kernel_Entrenchment.dc.html    -- L2 energy landscape
    Kernel_TheLine.dc.html         -- arousal threshold
    support.js                -- shared engine
    data/                     -- word lists (es, ru)
  aoe/
    AgeOfLenguages_v1.1.html  -- tech tree
    AgeOfLenguages_v1.2.html  -- war council
    AgeOfLenguages_v1.9_TheClick.html -- THE CLICK (current)
    AgeOfLenguages_v2.2_HighGround.html -- frozen dead-end
  scrolls/
    AgeOfLenguages.md         -- the capstone design thesis
    AgeTITANSbalance.md       -- AoE2 combat mechanics deep research
    AOE2bowTITANs.md          -- AoE2 design philosophy deep reference
    ONBOARDING_FOR_THE_NEXT_CLAUDE.md -- scroll for the next AI coworker
```

---

## The version rule

Every version is its own immutable file. vN+1 is a copy of vN; the frozen one is never edited; the highest number is current. The whole lineage publishes -- the dead ends too.

---

## The prime analogy (Age of Lenguages)

| Age of Empires II | Age of Lenguages |
|---|---|
| Civilisation | A language (ES/EN/PT/RU/UA/GR) |
| Unit | A core structure (phoneme, cognate, case, conjugation) |
| Building | A faculty (phonology, lexicon, syntax, morphology, idiom, listening) |
| The four Ages | CEFR fluency (A1 dark age to C2 imperial) |
| The four resources | Time, Reps, **Immersion** (scarce gold), Grammar |
| The tech tree | The dependency graph |
| The counter system | Cavalry (syntax) > archers (lexicon) > infantry (phonology) > cavalry |
| Winning | Speaking without translating |

---

## Roadmap

- [x] JpnTree kanji lineage v1-v3
- [x] vladTrees multilingual etymology engine
- [x] Age of Lenguages v1.1 to v1.9 (THE CLICK)
- [x] Landing page with all projects linked
- [ ] Age of Lenguages v2.0 -- the next grounded step after THE CLICK
- [ ] Expand kanji from Grade 1 to Grade 2+
- [ ] Per-language word-family packs for vladTrees
- [ ] Quest 3 VR -- walk the canopy, leap the nodes

---

## Related repos

- [MNetv1](https://github.com/vsavytsk1/Mnetv1) -- the MachineNet kernel, grimoire, and visual engine
- [SpiderEngineering](https://github.com/vsavytsk1/SpiderEngineering) -- ARACNIUM spider engineers + HELENA Genesis-LLM

---

*Buenos Aires + Ancient Korinthos. 2026.*
*A language is a civilisation. You field only what you pay for.*
*The monkey loves trees. The spider loves the leap. Always.*
*P=12. chi=2.*