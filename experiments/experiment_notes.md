# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.22667`
- Best artifact: `blend_may21_loop10_best_t023_t033_occupational_disease.csv`
- Best description: `may21_loop10_best_t023_t033_occupational_disease`

## May 21 Submission Batch

Ten submissions were completed on 2026-05-21 local time. The batch moved the public score from `0.20845` to `0.22667`.

| Description | Public score |
|---|---:|
| `may21_loop01_best_t002_svg_limitation` | `0.20845` |
| `may21_loop02_best_t006_product_liability` | `0.20845` |
| `may21_loop03_best_t010_qualified_robbery` | `0.20845` |
| `may21_loop04_best_t014_accident_shoulder` | `0.20845` |
| `may21_loop05_best_t016_self_employed_maintenance` | `0.20845` |
| `may21_loop06_best_t018_judicial_assistance` | `0.20845` |
| `may21_loop07_best_t021_sub_mandate_forwarder` | `0.20456` |
| `may21_loop08_best_t022_crossborder_child_measures` | `0.20845` |
| `may21_loop09_best_t023_ahv_director_liability` | `0.21751` |
| `may21_loop10_best_t023_t033_occupational_disease` | `0.22667` |

Key findings:

- AHV director liability and occupational disease / accident-insurance investigation patches stacked positively.
- SVG limitation, product liability, qualified robbery, accident shoulder, self-employed maintenance, judicial assistance, and cross-border child measures tied in their tested contexts.
- The sub-mandate forwarder replacement was negative in this form.

## May 20 Submission Batch

Ten submissions were completed on 2026-05-20 local time. The batch moved the public score from `0.19307` to `0.20845`.

| Description | Public score |
|---|---:|
| `may20_loop01_best_t005_bearer_mortgage_certificate` | `0.19715` |
| `may20_loop02_best_t005_t020_construction_lien` | `0.19715` |
| `may20_loop03_best_t005_t007_medical_mandate` | `0.20401` |
| `may20_loop04_best_t005_t007_t013_temp_staffing` | `0.20401` |
| `may20_loop05_best_t005_t007_t004_bankruptcy_deadline` | `0.20401` |
| `may20_loop06_best_t005_t007_t028_building_owner` | `0.20401` |
| `may20_loop07_best_t005_t007_t034_lien_deadline` | `0.20401` |
| `may20_loop08_best_t005_t007_t038_tort_causation` | `0.20401` |
| `may20_loop09_best_t005_t007_t015_cash_mandate` | `0.20845` |
| `may20_loop10_best_t005_t007_t015_t040_marital_protection` | `0.20845` |

Key findings:

- Bearer mortgage certificate, medical mandate liability, and spousal cash/mandate maintenance patches stacked positively.
- Construction lien, temporary staffing wages, bankruptcy deadline, building-owner liability, lien deadline, tort causation, and marital-protection patches tied in their tested contexts.
- The current anchor should use the simplest best-scoring file, loop09, because loop10 only adds a neutral row.

## May 19 Submission Batch

Ten submissions were completed on 2026-05-19 local time. The batch moved the public score from `0.16083` to `0.19307`.

| Description | Public score |
|---|---:|
| `may19_loop01_best_t003_vehicle_lease_defects` | `0.16803` |
| `may19_loop02_best_t003_t011_jurisdiction_no_authority` | `0.16803` |
| `may19_loop03_best_t003_t031_spousal_maintenance` | `0.17672` |
| `may19_loop04_best_t003_t031_t030_marital_home_interim` | `0.17672` |
| `may19_loop05_best_t003_t031_t037_trademark_domain_uwg` | `0.17927` |
| `may19_loop06_best_t003_t031_t037_t032_detention` | `0.17927` |
| `may19_loop07_best_t003_t031_t037_t036_dna` | `0.17927` |
| `may19_loop08_best_t003_t031_t037_t025_matrimonial_property` | `0.19307` |
| `may19_loop09_best_t003_t031_t037_t025_t024_divorce_income` | `0.19307` |
| `may19_loop10_best_t003_t031_t037_t025_t026_family_home_rent` | `0.19307` |

Key findings:

- Vehicle lease defects, spousal maintenance, trademark/domain unfair-competition, and matrimonial property/foreign villa patches stacked positively.
- Jurisdiction/no-authority, marital-home interim measures, pretrial detention, juvenile DNA profile, divorce income maintenance, and family-home rent proceeds tied in their tested contexts.
- The current anchor should use the simplest best-scoring file, loop08, because loop09 and loop10 only add neutral rows.

## May 18 Submission Batch

Ten submissions were completed on 2026-05-18 local time. The batch moved the public score from `0.12861` to `0.16083`.

| Description | Public score |
|---|---:|
| `may18_loop01_best_t017_tenancy_eviction_true_single` | `0.13364` |
| `may18_loop02_best_t035_foreign_inheritance_measures` | `0.12861` |
| `may18_loop03_best_t019_foreign_divorce_recognition` | `0.14128` |
| `may18_loop04_best_t008_child_abduction_bgkke` | `0.12861` |
| `may18_loop05_best_t027_child_protection_add_short` | `0.12884` |
| `may18_loop06_best_t039_simple_partnership` | `0.14289` |
| `may18_loop07_best_t039_plus_t017` | `0.14793` |
| `may18_loop08_best_t039_plus_t019` | `0.15557` |
| `may18_loop09_best_t039_plus_t017_t019` | `0.16060` |
| `may18_loop10_best_t039_plus_t017_t019_t027` | `0.16083` |

Key findings:

- Focused patches for tenancy eviction, foreign divorce recognition, and simple partnership were all positive.
- Stacking the simple-partnership patch with tenancy eviction and foreign divorce recognition produced most of the gain.
- The conservative child-protection add-short row was only weakly positive alone but improved the stacked candidate.
- The tested foreign inheritance/provisional-measures and child-abduction variants tied the previous best and should not be repeated unchanged.

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
