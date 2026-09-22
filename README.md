# Task 1: ADR Identification Basics
## Case: Vancomycin-Induced Systemic Flaring (Drug Reaction with Eosinophilia and Systemic Symptoms — DRESS)

**Source:** Symes FLI, Bakthavatsalam K. *Vancomycin-Induced DRESS Syndrome with Nephritis, Pneumonitis, and Colitis in an HLA-A\*32:01-Positive Patient: A Case Report.* Archives of Medical Case Reports. 2026;8(1):5–10. (Open access, CC-BY)

---

## 1. Case Details

- **Patient:** Woman in her 60s
- **Past medical history:** Recurrent lower-limb cellulitis, chronic venous ulcers, seasonal asthma, sinusitis
- **Known drug allergy:** Penicillin (previous anaphylaxis)
- **Presenting complaint:** 2-day history of right lower-limb pain and swelling
- **Diagnosis on admission:** Cellulitis of the right lower limb with an infected venous ulcer, plus suspected septic arthritis of the right ankle. Wound swab grew MRSA; ankle aspirate later grew Group C Streptococcus.

## 2. Symptoms (of the Reaction)

- Widespread pruritic (itchy) morbilliform rash — began on the right lower limb and progressed to involve the entire body
- Fever
- Diarrhea (new onset), with elevated faecal calprotectin
- Ongoing dyspnea (shortness of breath)
- Laboratory/investigation findings supporting the reaction:
  - Rising eosinophil count (baseline 0.0 × 10⁹/L → peak 2.8 × 10⁹/L)
  - Rising creatinine (baseline 73 µmol/L → peak 302 µmol/L), with microalbuminuria and microscopic hematuria
  - Normal liver function tests throughout (notably *no* hepatic involvement, atypical for DRESS)
  - Raised inflammatory markers, neutrophilia, lymphocytosis
  - CT chest: ground-glass nodules and peribronchial thickening suggestive of pneumonitis
  - Skin biopsy: spongiosis, exocytosis, mixed lymphocyte/eosinophil/neutrophil infiltrate — consistent with a drug reaction
  - HLA-A\*32:01: **positive**

## 3. Medication History

| Medication | Start Day | Stop Day | Indication |
|---|---|---|---|
| Vancomycin (IV) | Day 0 | Day 28 (stopped when rash worsened) | Cellulitis / septic arthritis (MRSA, Group C Streptococcus) |
| Moxifloxacin | Day 17 | — | Suspected hospital-acquired pneumonia |
| Prednisolone (oral) | Day 21 | Ongoing, dose adjusted (increased Day 34–37, again Day 50) | Asthma exacerbation; later, treatment of DRESS itself |
| Clindamycin | Day 28 | — | Replacement antibiotic for septic arthritis after vancomycin stopped |
| Co-trimoxazole | ~Day 34–37 | Day 50 (stopped) | PJP prophylaxis while on high-dose steroids |
| Atovaquone | Day 50 | — | PJP prophylaxis (replaced co-trimoxazole) |
| Cyclosporine | Day 50 | — | Second-line agent for steroid-dependent DRESS relapse |

## 4. Clinical Timeline

| Day | Event |
|---|---|
| 0 | Admitted; IV vancomycin started for cellulitis and septic arthritis |
| 17 | Moxifloxacin added for suspected hospital-acquired pneumonia |
| 21 | Oral prednisolone started for an asthma flare; patient tested positive for metapneumovirus |
| 27 | Widespread itchy morbilliform rash and fever developed; dermatology's first impression was a moxifloxacin reaction, DRESS thought less likely |
| 28 | Vancomycin **stopped**; switched to clindamycin |
| 34–37 | Peak eosinophil count and creatinine; new diarrhea; skin biopsy and HLA typing performed; prednisolone dose increased |
| 41 | CT chest showed pneumonitis; biopsy findings consistent with a drug reaction; clinical improvement began |
| 49 | HLA-A\*32:01 test returned **positive** — a marker specifically linked to vancomycin-induced DRESS |
| 50 | Rash and eosinophilia **relapsed** during steroid tapering; steroid dose raised again and cyclosporine (a second-line agent) started |

### Why the timeline points to vancomycin, not the other concomitant drugs

- **Latency fits vancomycin, not moxifloxacin:** DRESS typically has a 2–8 week latency period. The rash appeared on day 27 — 27 days after vancomycin was started, squarely inside that window. Moxifloxacin had only been given for ~10 days at that point, which is short for a DRESS-type reaction, even though dermatology's *first* impression (based on recency alone) was a moxifloxacin exanthem.
- **Positive dechallenge with vancomycin:** Symptoms and inflammatory/eosinophil markers began improving only after vancomycin was withdrawn on day 28 (alongside steroids) — clindamycin was substituted for the same infection without recurrence of the rash, showing the antibiotic *class switch away from vancomycin* was tolerated.
- **Prednisolone and co-trimoxazole as unlikely culprits:** Prednisolone is a treatment for allergic/inflammatory reactions, not a typical trigger of them, and was already on board before the worst of the reaction — if anything it would be expected to dampen a reaction, not cause one. Co-trimoxazole was only introduced around day 34–37, after the rash had already begun (day 27), so it cannot explain the *onset* of the reaction, though the paper notes it as a possible (unconfirmed) contributor to the later relapse.
- **Genetic evidence is vancomycin-specific:** The positive HLA-A\*32:01 result is a pharmacogenetic marker with a specific, well-documented association to vancomycin-induced DRESS — not to moxifloxacin, prednisolone, or co-trimoxazole.
- **Alternative (non-drug) causes excluded:** Infectious workup (including herpesviruses) and autoimmune/vasculitis workup were negative; rheumatology considered and ruled out eosinophilic granulomatosis with polyangiitis (EGPA).

## 5. Causality Assessment

### WHO-UMC Causality Scale

The WHO-UMC scale categorizes reactions as Certain, Probable/Likely, Possible, Unlikely, Conditional, or Unassessable.

| WHO-UMC criterion | Met? |
|---|---|
| Reasonable time relationship to drug administration | ✅ Yes (~27 days, within DRESS latency) |
| Reaction cannot be reasonably explained by disease or other drugs | ✅ Yes (infectious/autoimmune causes excluded; other drugs poorly fit the timeline) |
| Response to withdrawal (dechallenge) clinically reasonable | ✅ Yes (improved after stopping vancomycin + steroids) |
| Rechallenge satisfactory, if necessary | ❌ **Not performed** |

Under WHO-UMC, "**Certain**" specifically requires a *plausible rechallenge* — reintroducing the drug and seeing the reaction recur. Since **no rechallenge was carried out** in this case (understandably, given how severe the reaction was), the case cannot be labelled "Certain" no matter how strong the other evidence is. With a reasonable time relationship, exclusion of other causes, and a positive dechallenge, but no rechallenge, this case fits the WHO-UMC category of **"Probable/Likely."**

### Naranjo Adverse Drug Reaction Probability Scale

| # | Question | Answer | Score |
|---|---|---|---|
| 1 | Are there previous conclusive reports on this reaction? | Yes | +1 |
| 2 | Did the adverse event appear after the suspected drug was given? | Yes | +2 |
| 3 | Did the reaction improve when the drug was discontinued or a specific antagonist given? | Yes | +1 |
| 4 | Did the reaction reappear when the drug was re-administered? | **Not done (no rechallenge)** | 0 |
| 5 | Are there alternative causes that could have caused the reaction on their own? | No reasonable alternative found | +2 |
| 6 | Did the reaction reappear when a placebo was given? | Not done | 0 |
| 7 | Was the drug detected in blood/body fluids in toxic concentration? | Not reported | 0 |
| 8 | Was the reaction more severe when the dose was increased, or less severe when decreased? | Not clearly assessed | 0 |
| 9 | Did the patient have a similar reaction to the same or similar drug in a previous exposure? | No (prior 1-week course was tolerated) | 0 |
| 10 | Was the adverse event confirmed by objective evidence? | Yes (HLA-A\*32:01, biopsy, eosinophilia) | +1 |

**Total Naranjo score: 7 → "Probable" category** (Probable = 5–8; Definite = ≥9, which requires a positive rechallenge — question 4 — to reach)

### Why "Probable," not "Definite"

Both WHO-UMC and Naranjo converge on **Probable**, not Definite/Certain, for the same reason: **no rechallenge was performed.** A rechallenge (re-exposing the patient to vancomycin and observing whether the reaction recurs) is the one piece of evidence that would upgrade the causality rating to "Certain" (WHO-UMC) or "Definite" (Naranjo, where a positive rechallenge is required to score ≥9). Since there was **no alternative cause identified** (infectious and autoimmune causes were actively excluded) and every other criterion is satisfied, the case sits at the ceiling of what's achievable without a rechallenge — i.e., **Probable.**

*(Note: the original case report itself used a different, DRESS-specific tool — the RegiSCAR score — and reported a score of 7, which that tool's own scale labels "Definite." RegiSCAR does not require a rechallenge to reach its top category, which is why its conclusion differs from the general-purpose WHO-UMC/Naranjo assessment above.)*

## 6. Suspected Drug

**Vancomycin**

---
*Prepared as part of Task 1 — ADR Identification Basics, using a real, publicly available case report as the source scenario.*
