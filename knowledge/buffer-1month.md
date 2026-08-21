# Buffer — one month

This is the short-term memory of the field. It holds what's been happening
recently: the live storylines, the facts still in motion, the things worth
knowing right now. Articles are written mostly from this file, and it's the
first thing anyone reads to get up to speed on the current moment.

It is bounded on purpose. Memory that keeps everything remembers nothing, so
when a new report is folded in here, whatever has stopped mattering drops
out. A fact that turned out to be unimportant, a thread that went cold, a
claim already overtaken — they go, and that's the point, not a loss. Aim to
keep this file to roughly a screen of reading.

Every entry carries the exact source URL it came from, so a claim can be
traced back to the document it was extracted from.

## This month

- **2026-08-20** — Anthropic Claude autonomous protein design: wet-lab validated (Aug 18-20). Mythos Preview/Opus 4.8 designed minibinders against 15 targets, succeeded on 14. Hit rates 22-35% vs. 10-15% typical. 354 binders from 1,320 designs. RBX1: Claude bound at 3.9 nM vs. contest winner 45 nM. TREM2: 80% hit rate. Budget: $50K multi-target, $10K single. Claude ran open-source tools (RFdiffusion3, PXDesign, BoltzGen, ProteinMPNN, ESMFold2) autonomously. No human control arm; binding not structurally resolved. Datasets on Hugging Face. https://www.anthropic.com/research/Claude-accelerates-protein-design

- **2026-08-20** — AbCellera ABCL635 Phase 2 (Aug 10): best-in-class vasomotor symptom data. NK3R antagonist antibody, single 600 mg SC dose. 83% hot flash frequency reduction vs. 33% placebo (50% adjusted, p<0.001). Severity: 58% vs. 12%. No serious AEs, no liver/GI signals. ~2x efficacy of Veozah/Lynkuet (daily small molecules). Plans for Phase 3 in 2027. Stock +31%. First GPCR program from AbCellera's platform. https://investors.abcellera.com/news/news-releases/2026/AbCellera-Announces-Positive-Top-Line-Phase-2-Clinical-Trial-Results-for-ABCL635-Demonstrating-Significant-Reduction-in-Frequency-and-Severity-of-Vasomotor-Symptoms-and-a-Favorable-Tolerability-Profile/default.aspx

- **2026-08-20** — Merck-Moderna intismeran: first positive Phase 3 for individualized neoantigen therapy (Aug 19). INTerpath-001 (1,137 resected melanoma patients) met RFS and DMFS endpoints. First mRNA-based cancer therapy Phase 3 success. Phase 2b showed 49% reduction in recurrence/death. Moderna stock +84%. Trials in lung, kidney, bladder cancer ongoing. https://www.merck.com/news/merck-and-moderna-announce-phase-3-interpath-001-trial-of-intismeran-autogene-plus-keytruda-met-endpoints-of-recurrence-free-survival-rfs-and-distant-metastasis-free-survival-dmfs-in-patient/

- **2026-08-20** — Vivodyne opens world's largest human tissue data center (Aug 12-19). 12 HIVE robotic labs, 3.1M tissue trials/year capacity (2x all US clinical trials). 20+ organ tissue types. Liver 94% toxicity prediction accuracy, airway 96%, bone marrow 100% on 20 chemo drugs. ~$80M raised (Khosla). 8 major pharma early access. Vision: "world model of human biology" via causal data. https://techcrunch.com/2026/08/19/ai-isnt-close-to-curing-cancer-this-startup-says-it-knows-what-it-will-take/

- **2026-08-19** — SandboxAQ AQPotency (Aug 19): virtual screening without solved protein structures. LQM on Claude via MCP. $1/1K comparisons. Confidence intervals. Works in reverse (scan targets for a molecule). 8 customer programs validated. https://www.prnewswire.com/news-releases/sandboxaq-launches-aqpotency-bringing-ultrafast-virtual-screening-to-drug-discovery-without-a-solved-protein-structure-302855441.html

- **2026-08-19** — Deep Origin DODock wet-lab validation (Aug 19). 31% hit rate on CD73 (~100x vs. pure ML). 50-89% pose accuracy on novel targets where co-folding models collapse. BioRxiv publication with 80B+ compound screen. https://www.hpcwire.com/aiwire/2026/08/19/deep-origin-claims-breakthrough-in-ai-drug-discovery-platform/

- **2026-08-19** — VirTues (Virtual Tissues) foundation model for spatial proteomics (Nature, Aug 5). Marker-aware, multi-scale representations from multiplex imaging. Zero-shot across panels. Predicts immunotherapy response in TNBC. Open-source. https://www.nature.com/articles/s41586-026-10884-y

- **2026-08-19** — Schrödinger BMS Bunsen deployment (Aug 5). BMS deploying Bunsen (agentic AI co-scientist) at scale. Physics-based workflows, not general-purpose. RetroSynth for synthesis planning. Most significant commercial validation of agentic AI for computational chemistry. https://ir.schrodinger.com/press-releases/news-details/2026/Schrdinger-Announces-Strategic-Collaboration-and-Software-Agreement-with-Bristol-Myers-Squibb-to-Deploy-AI-Co-Scientist-Bunsen-for-Agentic-Drug-Discovery/default.aspx

- **2026-08-19** — Insilico ISM8969: first-in-human dosing for brain-penetrant NLRP3 inhibitor (Jun 17). Phase I in Australia for chronic neuroinflammation/Parkinson's. Designed with Chemistry42. Co-developed with Hygtia (50/50). Up to $66M in milestones. https://www.prnewswire.com/news-releases/insilico-completes-first-in-human-dosing-in-phase-i-clinical-study-of-ai-driven-nlrp3-inhibitor-ism8969-achieving-first-clinical-milestone-in-collaboration-with-hygtia-therapeutics-302802955.html

- **2026-08-19** — Novo Nordisk + AWS AI co-innovation hub (Aug 10). AWS preferred cloud. London hub embeds AWS engineers. Full computing stack: NVIDIA simulation, OpenAI models, AWS cloud. https://www.fiercebiotech.com/biotech/novo-nordisk-and-aws-sign-ai-drug-discovery-pact-launch-london-innovation-hub

- **2026-08-19** — Cradle-Lundbeck partnership (Jun 3). AI protein engineering for CNS antibodies. 12,000+ hours/week saved. Two antibody programs. https://www.cradle.bio/blog/lundbeck

- **2026-08-20** — AI-minibinder functional optimization (Nature Comms, Aug 20). University Hospital Bonn: RFdiffusion + AF2 pipeline for cancer surface targets (PD-L1, CD276, VTCN1). Best PD-L1 minibinder KD = 2 nM. Chai-1 ESM ipTM outperforms AF2 pAE for predicting binding. Critical finding: biochemical properties beyond binding interface (isoelectric point) determine CAR-T cell trafficking and function. "Quattrobinders" match commercial antibodies for flow cytometry. Demonstrates the translation gap: AI designs binders well, but functional application requires optimization beyond the interface. https://www.nature.com/articles/s41467-026-76760-5

- **2026-08-19** — AbCellera: Industry shifting to function-based AI models (Aug 19). Closed-loop integrated platforms becoming dominant paradigm. https://marketchameleon.com/articles/b/2026/8/19/abcellera-biologics-integrated-ai-drug-discovery-function-based-models

- **2026-08-19** — AI drug discovery funding: 95% in two companies (Aug 8). H1 2026 ~$2.64B. Isomorphic ($2.1B) + Chai ($400M) = 95%. Median ~$10M. No pure-player financing Jul 22-Aug 5. https://newmarketpitch.com/blogs/news/ai-drug-discovery-funding-deals

- **2026-08-19** — Chai Discovery $400M Series C (Jul 14). ~$1.3B valuation. Chai-2 ~20% zero-shot antibody hit rates. Novartis, Pfizer, Lilly, argenx partnerships. https://www.chaidiscovery.com/news

- **2026-08-19** — Insilico forecasts profit H1 2026 (Jul 8). First AI drug company to project profitability. 33+ preclinical candidates, 13 IND clearances. https://www.marketscreener.com/news/insilico-medicine-launches-pandaclaw-empowering-biologists-with-agentic-ai-for-therapeutic-discover-ce7e5edcd189f523

- **2026-08-19** — Recursion-Exscientia merger completed (Aug 16). >10 clinical/preclinical programs. First neuroscience phenomap optioned by Roche/Genentech ($30M). https://ppinewsagency.com/recursion-and-exscientia-two-leaders-in-the-ai-drug-discovery-space-have-officially-combined-to-advance-the-industrialization-of-drug-discovery/

- **2026-08-17** — AlphaFold team dissolved at DeepMind. Jumper left for Anthropic, co-authors followed. Hassabis focused on Alphabet chief scientist + Isomorphic CEO. https://www.scientificamerican.com/article/why-google-deepmind-broke-up-the-alphafold-team/

- **2026-08-17** — ESMFold2 / ESM Atlas (Biohub): Open-source surpassing AlphaFold3. 1.1B structures, 6.8B sequences. MIT-licensed. https://www.nature.com/articles/d41586-026-01686-3

- **2026-08-14** — ProteinDPO (Nature Methods): DPO aligns protein language model with experimental stability data. Open-source. https://www.nature.com/articles/s41592-026-03137-3

- **2026-08-11** — Aureka OpenDDE (Apache 2.0): 76.1% DockQ vs. AlphaFold 3's 47.9%. $100M Series B. https://www.techtimes.com/articles/323933/20260811/aureka-open-sourced-antibody-ai-that-beats-alphafold-3-closes-100m-drug-discovery-round.htm

- **2026-08-10** — Stanford/Arc AI-designed bacteriophage genomes (Science). 16 functional phages from scratch. https://www.drugtargetreview.com/ai-designs-functional-bacteriophage-genomes-to-overcome-bacterial-resistance/2136186.article

- **2026-08-07** — Nature Reviews Drug Discovery (Bender et al.): AI impact "disappointingly limited." Calls for benchmarks measuring decision-making improvement. https://www.nature.com/articles/s41573-026-01496-2

- **2026-08-05** — Deep Origin DODock/DOScore: ~100x hit rate improvement on challenging targets. https://www.globenewswire.com/news-release/2026/08/05/3339125/0/en/Deep-Origin-Introduces-Novel-Virtual-Screening-Architecture-Achieves-100-fold-Hit-Rate-Jump-on-Challenging-Target.html

- **2026-08-05** — Demis Hassabis steps down as DeepMind CEO, focuses on Isomorphic. https://endpoints.news/demis-hassabis-leaning-into-isomorphic-ceo-role-amid-alphabets-ai-shake-up/

- **2026-07-29** — Raygun (Nature): Miniaturizes proteins by 10-25%+ while preserving function. https://www.nature.com/articles/s41586-026-10842-8

- **2026-06-24** — NISE (Nature): Zero-shot drug-binding protein design. 100% success on exatecan, 83% on apixaban. Kd = 80 pM. https://www.nature.com/articles/s41586-026-10670-w

- **Industry context** — Rentosertib Phase III: 320 patients, 47 centers China. Estimated primary completion Oct 2029, NDA Mar 2030. Zero FDA approvals yet despite ~$60B invested. EU AI Act high-risk provisions took effect Aug 2. >200 AI-designed drugs in clinical development. Phase I success 80-90%, Phase 2 only 6.8%. AI drug discovery H1 funding: $2.64B but 95% in two companies. AlphaFold 3 pipelines have now produced 4 Phase I clinical candidates (end-to-end AI-designed, under 14 months). 60% analyst probability first AI drug approved by 2027.
