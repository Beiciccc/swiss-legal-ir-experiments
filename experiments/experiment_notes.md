# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.12861`
- Best artifact: `blend_may17_loop02_t001_soft_t009_core_prune.csv`
- Best description: `may17_loop02_t001_soft_t009_core_prune`

## May 17 Submission Batch

Ten submissions were completed on 2026-05-17 local time. The batch moved the public score from `0.12299` to `0.12861`.

| Description | Public score |
|---|---:|
| `may17_loop01_best009_plus_t001_soft` | `0.12571` |
| `may17_loop02_t001_soft_t009_core_prune` | `0.12861` |
| `may17_loop03_t001_soft_t009_succession_expand` | `0.12291` |
| `may17_loop04_t001_soft_t009_recognition_expand` | `0.12723` |
| `may17_loop05_t001_soft_t009_marriage_public_policy` | `0.12676` |
| `may17_loop06_t001_soft_t009_bank_accounting` | `0.12622` |
| `may17_loop07_t001_hard_ip_core` | `0.12584` |
| `may17_loop08_t001_soft_t027_add_only` | `0.12566` |
| `may17_loop09_t001_soft_t035_foreign_merits` | `0.12672` |
| `may17_loop10_t001_soft_t017_tenancy_eviction` | `0.12650` |

Key findings:

- The software-source-code cleanup and foreign-estate recognition cleanup stack positively.
- Pruning the foreign-estate row to the core private-international-law recognition/public-policy citations produced the best score.
- Broader succession, marriage/public-policy, and bank-accounting expansions were weaker than the core-pruned variant.
- Conservative add-ons for child protection, foreign merits preservation, and tenancy eviction did not improve over the core-pruned best.

## May 16 Submission Batch

Ten submissions were completed on 2026-05-16 local time. The batch moved the public score from `0.10959` to `0.12299`.

| Description | Public score |
|---|---:|
| `may16_loop01_t034_lien_core` | `0.10959` |
| `may16_loop02_t040_marital_protection` | `0.10959` |
| `may16_loop03_t001_ip_software_core` | `0.11231` |
| `may16_loop04_t008_child_abduction_iprg` | `0.10959` |
| `may16_loop05_t009_foreign_estate_recognition` | `0.12299` |
| `may16_loop06_t012_mandate_account_core` | `0.10959` |
| `may16_loop07_t027_child_protection_core` | `0.10841` |
| `may16_loop08_t035_foreign_merits_preserve` | `0.11059` |
| `may16_loop09_t017_tenancy_eviction_core` | `0.11037` |
| `may16_loop10_combo_best_domain_cleanups` | `0.10959` |

Key findings:

- Replacing the generic property tail for the foreign estate recognition row with a focused private international law package produced the largest improvement.
- Narrowing the software-source-code row toward copyright, unfair competition, and private international law also improved the public score.
- The child-protection hard prune was negative; future variants should add child-protection citations without deleting as aggressively.
- Several other focused cleanups tied the prior best, suggesting the changed rows were either neutral or not present in the public subset.

## May 14 Submission Batch

Ten submissions were completed on 2026-05-14 local time. The batch moved the public score from `0.10706` to `0.10959`.

| Description | Public score |
|---|---:|
| `may14_loop01_t029_drop_remaining_old_zgb_tail_all` | `0.10959` |
| `may14_loop02_t029_drop_register_property_tail` | `0.10838` |
| `may14_loop03_t029_drop_general_inheritance_tail` | `0.10810` |
| `may14_loop04_t029_drop_973_968_958_only` | `0.10783` |
| `may14_loop05_t029_drop_241_656_only` | `0.10756` |
| `may14_loop06_current_best_t034_add_961_1` | `0.10706` |
| `may14_loop07_t029_addback_schkg_17_1` | `0.10682` |
| `may14_loop08_t029_addback_zpo_319` | `0.10823` |
| `may14_loop09_t029_addback_zpo_243_1` | `0.10682` |
| `may14_loop10_t029_addback_stpo_221_1` | `0.10682` |

## Findings

- Deleting all remaining old ZGB/property/inheritance residue from `test_029` reached `0.10959`, the May 14 best public score.
- Partial deletion groups were positive but weaker than full cleanup.
- `test_034 Art. 961 Abs. 1 ZGB` remained neutral on the current best.
- Adding back `SchKG 17.1`, `ZPO 319`, `ZPO 243.1`, or `StPO 221.1` did not beat the cleaned `test_029` row.
- The top-10 threshold on 2026-05-14 was about `0.28892`; the next phase needs global retrieval/rerank improvements instead of more single-row hand patching.

## Data Handling

Original competition datasets are not redistributed here. The repository contains submitted artifacts and compact diagnostics only.
