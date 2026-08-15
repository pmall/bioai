# Buffer — six months

This is the long-term memory of the field. It holds what would change
someone's reading of the whole field, not just this week: the events that
actually mattered, and the longer theses and hypotheses that are playing out
over months. It is the editorial line — when the short-term buffer says what's
happening, this file says what it means and where it's heading.

It is bounded, but by significance rather than age. An entry stays as long as
it carries weight and goes when it doesn't — a thesis that played out, an
impact that faded, a shift that got superseded by something more important.
New impactful developments are welcome to displace older, weaker ones. Keep
it to the dozen or two things that genuinely shape the field.

Every entry carries the exact source URL it came from, and a hypothesis
records the observation it grew out of.

## Impactful events

- **2024-05** — AlphaFold 3 released by DeepMind and Isomorphic Labs, dramatically improving structure prediction for proteins, nucleic acids, ligands, and their interactions. Nobel Prize for AlphaFold architects (Hassabis, Jumper) in Chemistry, 2024.

- **2025-04** — Xaira Therapeutics launches with $1B funding, employing a fresh Nobel laureate. Signals massive capital still flowing into AI drug discovery at the platform level. (Fortune, April 2025: https://fortune.com/2025/04/03/recursion-pharmaceuticals-ai-drug-discovery/)

- **2026-02** — Isomorphic Labs releases IsoDDE, demonstrating that the structural prediction → drug design gap is closing. More than doubles AF3 on generalization benchmarks, matches physics-based FEP on binding affinity. https://isomorphiclabs.com/articles/the-isomorphic-labs-drug-design-engine-unlocks-a-new-frontier

- **2026-05** — Isomorphic Labs $2.1B Series B. Largest-ever funding round for an AI drug discovery company. Signals that the field's capital structure is shifting toward long-term, deep-pocket backing. https://isomorphiclabs.com/articles/isomorphic-labs-announces-series-b-investment-round

- **2026-08** — Demis Hassabis steps down as DeepMind CEO to become Alphabet chief scientist, focusing on Isomorphic Labs. The clearest signal yet that Alphabet views drug discovery as the primary commercial application of its AI breakthroughs.

- **2026-08** — Recursion-Genentech: First AI-discovered neuroscience target validated and advanced into early discovery. Whole-genome CRISPR knockout map from 1T+ neurons. First concrete proof that an AI platform can discover novel biology, not just optimize known targets. https://www.globenewswire.com/news-release/2026/08/05/3339126/0/en/Recursion-Reports-Second-Quarter-Financial-Results-Genentech-Options-First-Neuroscience-Target-into-Early-Discovery-Program.html

- **2026-02** — Generate:Biomedicines $400M IPO on Nasdaq (GENB). Largest biotech IPO of 2026. Lead candidate GB-0895 (anti-TSLP) in Phase III for asthma. https://generatebiomedicines.com/

- **2026-06** — NewLimit $435M Series C for epigenetic reprogramming to treat aging. Total raised $650M. First program entering clinic. https://newlimit.com/

- **2026-03** — Earendil Labs raises $787M for AI antibody/biologics platform. Considering Hong Kong IPO. Sanofi collaboration worth up to $2.56B.

- **2025-2026** — Recursion merges with Exscientia (Sep 2024), builds BioHive-2 (NVIDIA), advances 7+ clinical programs. Phenomics-to-pipeline vertical integration model. https://www.recursion.com/

- **2025-2026** — Insilico Medicine advances ISM001-055 through Phase 2 (IPF) with positive but not statistically significant results. First wholly AI-discovered drug in patients. Now averaging one new development candidate per month (33 total since 2021). https://www.insilico.com/

## Theses and hypotheses

- **The generalization gap is the real bottleneck.** AlphaFold 3 was transformative for known structural families, but drug discovery lives in unexplored biological space. IsoDDE's step change on out-of-distribution benchmarks suggests the field's next frontier is not better predictions on familiar systems, but reliable predictions on novel ones. (Observation: IsoDDE benchmark performance, Feb 2026)

- **Pharma partnerships are the near-term proof mechanism.** Isomorphic Labs' collaborations with Novartis, Lilly, and J&J represent the first real tests of AI-designed drugs at scale. If these yield clinical candidates, it validates the platform-to-partnership model. If they don't, the technology may be ahead of its time. (Observation: Iso partnerships page)

- **The Eroom's Law counter-thesis.** AI-native companies claim 80-90% Phase 1 success vs. 40-65% industry average, but Phase 2 rates are comparable. The bottleneck may not be in early discovery (where AI clearly helps) but in clinical validation (where biology's complexity resists computational shortcuts). The real test is whether AI can break Eroom's Law over the next decade, not whether it can improve hit rates. (Observation: BCG data via Fortune, April 2025)

- **Three platform models are crystallizing.** (1) IsoDDE: structural biology → drug design (compute-heavy, pharma partnerships). (2) Recursion: phenomics data → full pipeline (massive wet lab + compute, own pipeline + partnerships). (3) Insilico: end-to-end AI-first (target ID → molecule → trial prediction, own pipeline). Each bets on a different bottleneck. (Observation: company websites and Fortune profile)

- **Open-source as competitive strategy is emerging.** Aureka's OpenDDE outperforms AlphaFold 3 on antibody-antigen tasks and is Apache 2.0 licensed. The moat is the Lab-in-the-Loop data flywheel — proprietary experimental data from live drug discovery programs — not the model weights. This "release the model, keep the data" pattern may become dominant in AI drug discovery, as proprietary biological data — not model architecture — is the durable advantage. (Observation: Aureka benchmarks and business model, Aug 2026)

- **AI agents are entering the clinical workflow layer.** Pathos AI's Foundry uses thousands of AI agents to design trials, match patients, and optimize dosing — not just discover molecules. Schrödinger's Bunsen makes computational chemistry accessible to non-specialists through natural language. The bottleneck is shifting from "find molecules" to "prove they work in the right patients." (Observation: Pathos AI, Schrödinger BMS deal, Aug 2026)

- **The infrastructure layer is consolidating.** Schrödinger (physics-based), Anthropic (workflow/integration), NVIDIA BioNeMo (ecosystem), and cloud providers (AWS/Novo Nordisk) are building the operating systems for AI drug discovery. BMS deploying Bunsen at scale signals big pharma is betting on physics-based computation augmented by AI, not just AI alone. (Observation: BMS-Schrödinger deal, Novo Nordisk-AWS, Claude Science, Aug 2026)

- **De novo protein design for small molecules crosses a threshold.** NISE achieves 83-100% success rates designing proteins that bind drug molecules from scratch, with picomolar affinities. This is no longer proof-of-concept — it's a working recipe with implications for drug delivery, biosensors, and therapeutic proteins. (Observation: Nature NISE paper, Jun 2026)

- **Experiment-guided protein structure prediction is maturing.** Two independent papers (Nature Biotechnology, Nature Methods) show how to steer AlphaFold3/AF2 to generate ensembles consistent with NMR, X-ray, and cryo-EM data. This addresses one of AlphaFold's key limitations — its bias toward static snapshots — and opens the door to dynamics-aware structural biology. (Observation: Nature Biotech Jun 2026, Nature Methods Apr 2026)
