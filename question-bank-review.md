# S1 Surgery CBT — source extraction and review notes

## Current bank status

- **67 playable MCQs** are currently included in `questions.json`.
- The original 24 starter questions have been retained.
- 43 additional questions have been added from the four supplied compilations, after removing clear repeats of existing questions.
- **17 theory/essay prompts** are listed separately in `theory.json` and displayed in the app's Theory section.
- No question is labelled as a verbatim original unless the wording is preserved. Most playable MCQs are labelled **Adapted** because incomplete stems/options were clarified or converted into a complete single-best-answer question.
- Items labelled **Supplementary** are useful clarifications or additional questions based on a source topic, not a verbatim past question.

## Source handling

1. `S1 COMPILATION (FIRST ROTATION).docx` — 62 numbered entries. Several are incomplete, repeated, or contain missing options.
2. `S1 compiled PQ 2021-1.doc` — 13-page fragmentary compilation. Many items are unnumbered and options/wording are incomplete.
3. `S1 R2 2025.pdf` — MCQs, theory questions and transcript-derived questions. The extracted layout interleaves two columns in places.
4. `S1_1st Rotation Question Compilation MBBS'25.pdf` — 6 essay questions and approximately 45 MCQ entries; several stems/options are incomplete.

## Items intentionally not made playable

These source items need the original question paper, a clearer image, or lecturer confirmation before a defensible key can be assigned:

- **2023 first-rotation Word file:** Q10 (fluid/electrolyte figures corrupted); Q13 (haemorrhoids, options D/E missing); Q14 (fracture outcome stem incomplete); Q18 and Q20 (risk-factor scenario corrupted/duplicated); Q19 (bladder trauma stem incomplete); Q21 (choledochal cyst options incomplete); Q22 (fluid-balance vignette incomplete); Q28/Q32 (same post-thyroidectomy haematoma scenario; one has no options); Q30 (ulcer stem incomplete); Q33 (impalpable testis options missing); Q34 (benign breast disease stem/options corrupted); Q36 (infection options incomplete); Q38 (cryptorchidism options incomplete); Q41 (preoperative assessment options corrupted); Q42 (post-prostatectomy symptoms; stem and options incomplete); Q43 (cholestatic jaundice options missing); Q47 (dysphagia options missing); Q53–55 (acute scrotal pain sequence incomplete); Q56 (non-healing duodenal ulcer options incomplete); Q58 (perioperative fluid regimen vignette truncated); Q61 (bladder exstrophy fragment); Q62 (postoperative metabolic response vignette truncated).
- **2021 PQ Word file:** multiple unnumbered fragments have incomplete stems/options (e.g. chest tube insertion, fluid balance, cephalosporin mechanism, obstructive jaundice, wound healing, primary hyperaldosteronism, breast cancer staging, SSI, amoebic liver abscess, neonatal prune-belly prognosis, urinary stones, TBI, bladder injury, ulcer disease, testicular descent and post-thyroidectomy haematoma). These remain source notes or theory prompts unless a complete question can be recovered.
- **MBBS '25 PDF:** Q5 (mutagen wording), Q6 (clean-surgery infection options), Q12–13 (trauma vignette and procedure options), Q16–17 (postoperative fever/fluid overload options), Q18 (orthopaedic imaging options), Q22 (mastitis treatment options), Q28 (fluid choice options), Q35 (fluid-balance option set), Q36 (oesophageal dysphagia vignette), Q40 (UPJ obstruction fragment), Q41–44 (appendicectomy/laparoscopy preparation fragments) and Q45 (thoracic trauma fragment) are incomplete or too ambiguous for reliable single-best-answer scoring.
- **R2 2025 PDF:** Q7 (carotid repair scenario uncertain), Q17–18 (instrument question text/options corrupted), Q23 (missing options), Q34–37 (circumcision scenario repeated and incomplete), Q38 (GCS pain response wording incomplete), Q43 (haemangioma options D/E missing), Q48 (gastroschisis/omphalocele option set imperfect), Q49 (polyuria definition/options imprecise), Q50 (burn assessment options incomplete), Q51 (staging pair options imperfect), Q53 (prostatectomy approach question may be recoverable but option wording/layout needs checking), and Q54 (physical examination options may be incomplete). Several questions are repeated in the same source: catheterisation (Q25/Q39), anorectal colostomy scenario (Q41/Q44), circumcision (Q34/Q35/Q37), and undescended testis (Q24/Q33).

## Answer-key policy

- Keys in the playable bank are based on standard surgical teaching and the clinical meaning of the source item, not on an unverified answer key embedded in the compilation.
- Ambiguous, incomplete or disputed source items are excluded from scoring rather than assigned a guessed answer.
- A few questions are explicitly clarified where the source terminology was imprecise (for example, “phosphate stones” is clarified as struvite only where the urease-organism association is intended).
- The app shows the source and source question number beside each playable question.


## Immediate seniors' R2 2025 extraction (v6)

The 81 MCQ entries (54 main-paper slots and 27 transcript questions) are now individually structured in `questions.json` with source references. Six associated theory questions are in `theory.json`. Of the 81 MCQs, 38 have independently added practice keys and 43 remain unkeyed due to incomplete/ambiguous source text. See `S1-R2-2025-extraction-notes.md`.
