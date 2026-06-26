# AI × Psychology — Complete Research Catalog (2025–2026)

> **Final merged deliverable.** Assembled from three deep-research passes (fan-out web search →
> source fetch → 3-vote adversarial verification → synthesis). Date: 2026-06-26.
>
> **Legend:** ✅ = claim passed 3-vote adversarial verification against a primary source ·
> ⚠️ = caveat/limitation. Every ✅ entry carries a primary-source identifier (DOI / arXiv ID).
>
> **Provenance:** Pass 1 = Clinical + machine-psychology. Pass 2 = I/O, Educational, Health,
> Positive (recovered after a synthesis-step glitch; verification was intact: 25 claims, 0 killed).
> Mini-pass = Neuropsychology + Forensic/Cross-cultural (24 claims verified, 0 killed).

---

## Two directions of the field

- **Direction 1 — AI applied *to* psychology:** LLMs/ML used for therapy, assessment, tutoring,
  behavior change, cognitive testing.
- **Direction 2 — "Machine psychology" (psychology applied *to* AI):** psychometric and
  psychological methods used to measure and understand LLM cognition, personality, and bias.

---

## Direction 2 — Machine Psychology (best entry points; map many subfields at once)

- ✅ **Ye et al., "LLM Psychometrics" review** — arXiv **2505.08245** (13 May 2025, 400+ refs).
  Applies psychometric instruments/theory to evaluate and improve LLMs across **personality**
  (MBTI, Big Five/BFI-2, HEXACO), **cognitive** (theory of mind, reasoning), **affective**
  (emotional intelligence), **social/moral** (value alignment, bias/fairness), **cross-cultural**.
  Living bibliography: `github.com/ValueByte-AI/Awesome-LLM-Psychometrics` · `llm-psychometrics.com`.
- ✅ **"The Mind in the Machine" survey** — Columbia / Barnard / Cambridge, arXiv **2505.00003**
  (28 Mar 2025; *submitted* to COLM 2025, not confirmed accepted). Maps **six subfields**
  (cognitive, developmental, behavioral, social, personality, psycholinguistics) onto four LLM
  development stages (preprocessing → pre-training → post-training → evaluation).

---

## Direction 1 — AI applied to Psychology, by subfield

### 🟢 Clinical & Counseling Psychology *(deepest evidence base)*

**RCTs**
- ✅ **Therabot (Dartmouth)** — Heinz et al., *NEJM AI*, 27 Mar 2025, N=210. Significant symptom
  reductions for depression, anxiety, and high-risk eating disorders vs waitlist at 4 & 8 weeks;
  working alliance (WAI=3.59) near outpatient norms. DOI **10.1056/AIoa2400802**.
  ⚠️ Passive waitlist control inflates effect; no human-therapist arm.
- ✅ **CAS Institute of Psychology trial** — Zhao et al., *Applied Psychology: Health & Well-Being*,
  Oct 2025, N=865 (NCT06346496). Reduced depression at 2 wks; depression + anxiety at 4 wks.
- ✅ **Meta-analysis** — *JMIR*, 16 Dec 2025, 14 RCTs, N=6,314. Overall **ES=0.30 (P=.047)**.
  Social-oriented chatbots work; task-oriented ones essentially don't (SMD≈0.007, n.s.).

**Assessment / screening / phenotyping**
- ✅ **EmoScan + PsyInterview** — *Communications Medicine* (Nature), 5 Nov 2025. Beats GPT-4
  (F1 0.747 vs 0.590); ships a 1,157-dialogue synthetic interview dataset. arXiv **2501.08769**.
- ✅ **MAGI** — arXiv **2504.18260**, ACL 2025 Findings. Automates the gold-standard MINI interview
  via 4 coordinated LLM agents; N=1,002.
- ✅ **GPT-5.2 depression phenotyping** — medRxiv, Mar 2026. Inferred PHQ-9/HAM-D/CGI-S from 91,651
  notes; moderate agreement with patient PHQ-9 (κ=0.64), stronger with clinicians (κ≤0.79).
  ⚠️ Preprint; accuracy dropped for Black (r=0.48) and Hispanic (r=0.43) patients.

**Trends & policy**
- ✅ **Torous & Cipriani viewpoint** — *JMIR Mental Health*, 2025. ~10 studies (2018) → hundreds now;
  patients use general-purpose chatbots for unintended emotional support.
- ✅ **WHO** — 20 Mar 2026 (TU Delft Digital Ethics Centre workshop). Flags general-purpose
  generative AI for emotional support as a **public mental health concern**.

**⚠️ Tools/products (leads):** Ash (Slingshot AI), Limbic, Wysa, Woebot, Therabot.
**⚠️ Labs/people:** Dartmouth (Jacobson/Heinz); Stanford AI4MH Lab; CAS Institute of Psychology;
John Torous (Beth Israel Deaconess).

### 🟢 Industrial-Organizational (I/O) Psychology

- ✅ **Dutta (2026)**, "Transforming Recruitment & Selection… A Structuration Lens" — *Human Resource
  Management* (Wiley) 65(1):77–115, DOI **10.1002/hrm.70018**. Qualitative study, 43 HR/talent
  leaders; finds simultaneous human-AI collaboration *and* algorithmic management of humans.
- ✅ **"Mapping LLMs in hiring decisions: a scoping review"** — *Frontiers in AI*, 13 Mar 2026,
  DOI **10.3389/frai.2026.1798519** (PRISMA-ScR, Scopus 2020–2025). LLM hiring use concentrates in
  screening/interviewing and is **70–75% employer-facing**; **bias = 35–40% of risk mentions**, and
  **60–65% of mitigations are proposed, not empirically tested**.
- ✅ **SIOP** — "I-O Psychology at a Crossroads" + an emerging **"Psychometric AI"** framing
  (siop.org). Jan 2026 SIOP guidance on validating AI-based selection assessments.
- ✅ **HireVue** *(deployed product)* — AI Interviewer (enterprise launch Jun 2026), Virtual Job
  Tryout, Game-Based Assessments, AI Hiring Agent. Explicitly grounds products in I/O psychology
  (employs I/O psychologists; external bias audits by DCI Consulting / Landers Workforce Science).
- ✅ **Lin, "validity-guided workflow for robust LLM research in psychology"** — arXiv **2507.04491**
  (Jul 2025). ⚠️ Caution for AI-driven personality assessment: LLM personality scores **collapse
  under factor analysis**, moral prefs **reverse with punctuation changes**, ToM accuracy swings
  with trivial rephrasing. Proposes a 6-stage validity workflow.

### 🟢 Educational Psychology

- ✅ **Fütterer et al. (2026)**, GenAI for self-regulated learning — *Educational Psychology Review*,
  DOI **10.1007/s10648-026-10133-8**. School RCT (N=371, grades 7–9); utility-value prompts helped
  preserve perceived utility value vs a strategy condition. ⚠️ No significant gain over the
  standard-ChatGPT control. *(Note: lead author is Fütterer, mis-rendered "Fölterer" in raw data.)*
- ✅ **Huang et al. (2026)**, three-level meta-analysis of AI feedback on SRL in higher ed —
  *Educational Psychology Review*, DOI **10.1007/s10648-026-10166-z**. 85 articles, k=387, N=9,564;
  **medium effect g=0.509**.
- ✅ **Systematic review of 88 LLM-in-education studies** (Nov 2022–Mar 2025) — *Computers and
  Education: AI*, PII **S2666920X25001699**. Six categories (Chatbots, Content Generation, Automated
  Assessment/Feedback, Task Support, Learning Support, **Intelligent Tutoring Systems** — most prominent).
- ✅ **SRLAgent** — arXiv **2506.09968** (Jun 2025). Minecraft-based LLM system for SRL, grounded in
  **Zimmerman's three-phase model** (forethought/performance/reflection).
- ✅ **npj Science of Learning PRISMA review** — DOI **10.1038/s41539-025-00319-0** (May 2025).
  14 studies; AI can facilitate all three Zimmerman SRL phases.
- ✅ **LAK'26 GenAI-ITS SRL sequencing** — arXiv **2601.17000** (Gao et al.; *not* "McGill et al.").
  Two learner clusters by GenAI timing; students used GenAI mostly for *acquisition* not
  transformation, with no significant correlation to performance.

### 🟢 Health Psychology

- ✅ **"AI Chatbots for Health Behavior Change: Scoping Review"** — *JMIR*, 28 Jan 2026,
  DOI **10.2196/79677**. 43 studies (14 RCTs), published 2018–2024. Targets: physical activity
  (18/43, most common), stress management (16/43), diet, smoking cessation, sleep, weight.
  *(Distinct from clinical mental-health therapy chatbots.)*

### 🟢 Positive Psychology

- ✅ **"Flourish"** *(GenAI well-being app)* + multi-institutional RCT — arXiv **2601.11530** (Jan 2026,
  N=486 across 3 US institutions). PERMA-model AI coach ("Sunnie") delivering brief proactive
  well-being activities; gains in positive affect, resilience, belonging, mindfulness, flourishing;
  reduced loneliness. Targets thriving, **not** symptom reduction.

### 🟢 Neuropsychology / Cognitive Neuroscience

*Two threads: (1) brain–LLM alignment, (2) ML for cognitive/clinical assessment.*

- ✅ **NeuroCognition benchmark** (Haznitrama, Ardi, Oh) — arXiv **2603.02540** (Mar 2026). Adapts
  Raven's Progressive Matrices, Spatial Working Memory, and the Wisconsin Card Sorting Test to LLMs
  (factor analysis of 156 models). LLMs do well on text but **degrade on images and with complexity**;
  measures cognition *distinct* from standard benchmarks.
- ✅ **"From Language to Cognition"** (AlKhamissi et al., EPFL/MIT/Georgia Tech) — arXiv **2503.01830**,
  **EMNLP 2025** (2025.emnlp-main.1237). Brain alignment tracks **formal** linguistic competence far
  more than **functional** (W=0.0, p<0.002); alignment **peaks at ~2–8B tokens then saturates/declines**
  regardless of model size, even as task performance keeps rising. (34 checkpoints × 8 sizes, Pythia.)
- ✅ **"Do LLMs Think Like the Brain?"** (Lei et al.) — arXiv **2505.22563**, **AAAI 2026**.
  Higher-performing LLMs evolve toward brain-like representational hierarchies; strongest
  functional+anatomical correspondence at **higher semantic abstraction** (14 LLMs vs fMRI).
- ✅ **Goldstein, Ham, Schain et al.** — *Nature Communications*, 26 Nov 2025, DOI
  **10.1038/s41467-025-65518-0**. LLM layer hierarchy (GPT-2 XL; validated w/ Llama-2) maps onto the
  **temporal dynamics** of human language areas (ECoG); layer depth ↔ peak-encoding timing,
  **Pearson r=0.85, p<1e-13** in IFG/Broca's.
- ✅ **"Precision neuropsychology in the area of AI"** (Lundervold) — *Frontiers in Psychology* 16,
  14 May 2025, DOI **10.3389/fpsyg.2025.1537368**. ML on a digital Clock Drawing Test discriminates
  MCI subtypes (>80% acc, ⚠️ medium-confidence / underlying result is 2020); ML on linguistic markers
  detects prodromal Alzheimer's at **88% accuracy**.

### 🟢 Forensic & Cross-Cultural Psychology

- ✅ **Violence-prediction ML systematic review** (Kozhevnikova, Yukhnenko, Scola, Fazel; Oxford) —
  arXiv **2511.23118** (Nov 2025). 38 studies / 40 ML models (9 databases through Sep 2025).
  AUCs 0.68–0.99, **but calibration rarely assessed (8 studies), external validation minimal (3)**;
  overall clinical utility judged **poor** (overfitting, small samples, weak generalisability).
- ✅ **COMPAS recidivism re-analysis** (Kienzle, Velarde, Gannon) — *AI & Ethics* (Springer), DOI
  **10.1007/s43681-026-01116-0** (2026). Confirms racial disparity (FP higher for Black defendants,
  FN higher for White); **bias-mitigation cannot fully remove embedded data bias**.
- ✅ **DeceptionX** — arXiv **2606.11385** (Jun 2026). Multimodal LLM for **explainable** video
  deception detection via an Observe-Think-Summarize chain-of-thought (DeceptChain dataset).
- ✅ **LieXBerta** — *Scientific Reports* (Nature), DOI **10.1038/s41598-025-17741-4** (2025).
  RoBERTa emotion features + facial/action features → XGBoost for interrogation lie detection;
  **87.50% acc / 87.13% F1** (~6.5% over baseline).
- ✅ **Culturally-Aware Conversations (CAC)** (Havaldar, Rai, Cho, Ungar; UPenn) — arXiv **2510.11563**,
  **ACL HCINLP 2025** (2025.hcinlp-1.18). Sociocultural-theory benchmark (48 conversations, 240
  responses, raters from 8 countries). LLMs adapt best to **Western** norms; accuracy highest for
  America (64.17%), lowest for India (49.17%).

### 🟡 Cross-cutting subfields (covered via Direction-2 surveys, not standalone applications)
- **Cognitive** — theory-of-mind & reasoning evaluation of LLMs (both surveys; NeuroCognition).
- **Developmental** — scaffolding / incremental-learning analogies (Columbia survey).
- **Social** — conformity, social identity, ToM, bias/fairness (both surveys).
- **Personality** — MBTI/Big Five/HEXACO administration to LLMs (Ye et al.; cf. Lin caution above).
- **Affective / Emotion** — emotional-intelligence testing of LLMs; EmoScan; LieXBerta emotion features.
- **Behavioral** — operant/reinforcement framing of RLHF (Columbia survey); no standalone 2025–2026
  clinical-behavioral application surfaced.
- **Psychometrics & Quantitative** — the organizing frame of Direction 2 (Ye et al.).

---

## Caveats
- **Preprints**: GPT-5.2 phenotyping, WHO item, and several arXiv entries (NeuroCognition,
  DeceptionX) are recent and/or not peer-reviewed — figures may shift. Where a preprint was later
  accepted to a venue (EMNLP/AAAI/ACL), that is noted.
- **Passive controls**: clinical RCTs used waitlist comparators; none are head-to-head vs human therapists.
- **Equity**: documented demographic disparities in LLM depression inference *and* in COMPAS-style
  recidivism tools.
- **Single-study findings**: many Neuro/Forensic entries rest on one primary source each.
- **Metadata slips in raw extraction** (corrected here): author "Fölterer"→**Fütterer**;
  "McGill et al."→**Gao et al.**

## Refuted claims (transparency)
- Pass 1: an overstated per-condition Therabot effect-size claim; a claim that the Columbia survey
  was *accepted* (vs only submitted) to COLM 2025. Pass 2 and the Neuro/Forensic mini-pass: **0 killed**.

## Method note
Three passes, all using the deep-research harness (Scope → Search → Fetch → 3-vote adversarial
Verify → Synthesize). The Neuro/Forensic subfields were recovered via a **verify-only mini-pass**:
their claims had already been extracted in Pass 2 but fell below that run's global top-25
verification cap (a subfield-blind ranking), so only the verification step was re-run on the
pre-extracted claims — 24/24 confirmed.
