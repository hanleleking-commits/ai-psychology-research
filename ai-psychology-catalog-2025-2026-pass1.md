# AI × Psychology — Latest Work Catalog (2025–2026)

> **Pass 1 of 2.** Generated via the deep-research harness (6 search angles → 29 sources → 134 claims → 25 adversarially verified → 23 confirmed → 10 synthesized findings). Date: 2026-06-26.
>
> Every ✅ finding rests on a primary source that passed 3-vote adversarial verification. ⚠️ = surfaced in fetched sources but not individually verified — treat as a lead.
>
> **Scope note:** Verified evidence clusters in Clinical/Counseling psychology and the cross-cutting "machine psychology" direction. Six subfields (I/O, Educational, Health, Neuropsychology, Forensic, Positive) returned no claim strong enough to pass verification — these are covered in **Pass 2**.

---

## Direction 2 — "Machine Psychology" (psychology applied to AI)

The two anchor surveys are the best entry points — each maps multiple psychology subfields onto AI work.

- **✅ Ye et al., "LLM Psychometrics" review** — arXiv 2505.08245 (13 May 2025, 400+ refs). Applies psychometric instruments/theory to evaluate and improve LLMs. Spans **personality** (MBTI, Big Five/BFI-2, HEXACO), **cognitive** (theory of mind, reasoning), **affective** (emotional intelligence), **social/moral** (value alignment, bias/fairness), **cross-cultural** dimensions.
  - Living bibliography: `github.com/ValueByte-AI/Awesome-LLM-Psychometrics` · `llm-psychometrics.com`
- **✅ "The Mind in the Machine" survey** — Columbia / Barnard / Cambridge, arXiv 2505.00003 (28 Mar 2025; *submitted* to COLM 2025, not confirmed accepted). Catalogs how **six subfields** — cognitive, developmental, behavioral, social, personality, psycholinguistics — are incorporated into LLMs across four development stages (preprocessing → pre-training → post-training → evaluation).

---

## Direction 1 — AI applied to Psychology, by subfield

### 🟢 Clinical & Counseling Psychology (richest area)

**Randomized controlled trials**
- **✅ Therabot (Dartmouth)** — Heinz et al., *NEJM AI*, 27 Mar 2025, N=210. Generative chatbot; significant symptom reductions for MDD, GAD, and high-risk eating disorders vs waitlist at 4 & 8 weeks. Working alliance WAI=3.59 (near outpatient norms); "similar to a real therapist" 4.9/7. *Caveat: passive waitlist control inflates effects; no human-therapist arm.* DOI: 10.1056/AIoa2400802
- **✅ CAS Institute of Psychology trial** — Zhao et al., *Applied Psychology: Health & Well-Being*, Oct 2025, N=865 (NCT06346496). LLM agent reduced depression at 2 weeks, depression + anxiety at 4 weeks vs waiting control. *Effect contingent on sufficient usage.*
- **✅ Meta-analysis** — *JMIR*, 16 Dec 2025, 14 RCTs, N=6,314. Overall **ES=0.30 (P=.047)** — small-to-moderate. **Social-oriented chatbots work; task-oriented essentially don't (SMD≈0.007, n.s.).** High heterogeneity.

**Clinical assessment / screening / phenotyping**
- **✅ EmoScan + PsyInterview** — *Communications Medicine* (Nature), 5 Nov 2025. LLM screener beats GPT-4 (F1 0.747 vs 0.590); ships a 1,157-dialogue synthetic clinical-interview dataset. arXiv 2501.08769
- **✅ MAGI** — arXiv 2504.18260, ACL 2025 Findings. First framework to automate the gold-standard MINI psychiatric interview via 4 coordinated LLM agents; evaluated on 1,002 participants.
- **✅ GPT-5.2 depression phenotyping** — medRxiv, Mar 2026. Inferred PHQ-9/HAM-D/CGI-S from 91,651 notes (8,287 patients). Moderate agreement with patient PHQ-9 (κ=0.64), stronger with clinician review (κ up to 0.79). **⚠️ Equity flag: accuracy dropped for Black (r=0.48) and Hispanic (r=0.43) patients.** *Preprint.*

**Field trends & policy**
- **✅ Torous & Cipriani viewpoint** — *JMIR Mental Health*, 2025. Literature grew from ~10 studies (2018) to hundreds; patients increasingly use general-purpose chatbots for unintended emotional support.
- **✅ WHO** — 20 Mar 2026 (from 29 Jan 2026 TU Delft Digital Ethics Centre workshop). Flags general-purpose generative AI for emotional support as a **public mental health concern**; young people vulnerable to emotional dependence.

**⚠️ Tools & products** (leads, unverified): **Ash** (Slingshot AI, STAT News Jul 2025), **Limbic** (limbic.ai), **Wysa**, **Woebot**, **Therabot** (research).
**⚠️ Labs / people:** Dartmouth (Nick Jacobson / Michael Heinz); **Stanford AI4MH Lab**; **CAS Institute of Psychology**; John Torous (Beth Israel Deaconess).

### 🟡 Cross-cutting coverage (via Direction 2 surveys)
- **Cognitive** — theory-of-mind & reasoning evaluation of LLMs (both surveys).
- **Developmental** — scaffolding / incremental-learning analogies (Columbia survey).
- **Social** — conformity, social identity, ToM, bias/fairness (both surveys).
- **Personality** — MBTI/Big Five/HEXACO administration to LLMs (Ye et al.).
- **Affective / Emotion** — emotional-intelligence testing of LLMs + EmoScan.
- **Psychometrics & Quantitative** — the organizing frame of Ye et al. Well covered.

### 🔴 Coverage gaps (no verified finding — see Pass 2)
Industrial-Organizational, Educational, Health psychology, Neuropsychology / Cognitive neuroscience, Forensic, Behavioral (standalone), Cultural/Cross-cultural (only briefly touched), Positive psychology.

---

## Refuted claims (transparency)
- An overstated per-condition effect-size claim about Therabot (killed 1–2).
- A claim that the Columbia survey was *accepted* at COLM 2025 — it's only submitted (killed 1–2).

## Key caveats
- **Preprints**: GPT-5.2 phenotyping and the WHO item are recent/non-peer-reviewed.
- **Passive controls**: all verified RCTs used waitlist comparators; none benchmarked head-to-head vs human therapists.
- **Equity**: documented demographic accuracy disparities in LLM depression inference.

## Primary sources
- arXiv 2505.08245 · arXiv 2505.00003 · JMIR 2025/1/e78238 · JMIR Mental Health 2025/1/e82369
- NEJM AI 10.1056/AIoa2400802 · Applied Psych H&WB 10.1111/aphw.70067 (NCT06346496)
- Nature Comms Medicine s43856-025-01158-1 · arXiv 2501.08769 · arXiv 2504.18260 (ACL 2025 Findings)
- medRxiv 2026.03.11.26348066 · WHO news 20-03-2026
