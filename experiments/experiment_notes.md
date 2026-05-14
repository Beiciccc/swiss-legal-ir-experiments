# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.10959`
- Best artifact: `blend_may14_loop01_t029_drop_remaining_old_zgb_tail_all.csv`
- Best description: `may14_loop01_t029_drop_remaining_old_zgb_tail_all`

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

- Deleting all remaining old ZGB/property/inheritance residue from `test_029` reached `0.10959`, the current best public score.
- Partial deletion groups were positive but weaker than full cleanup.
- `test_034 Art. 961 Abs. 1 ZGB` remained neutral on the current best.
- Adding back `SchKG 17.1`, `ZPO 319`, `ZPO 243.1`, or `StPO 221.1` did not beat the cleaned `test_029` row.
- The top-10 threshold on 2026-05-14 was about `0.28892`; the next phase needs global retrieval/rerank improvements instead of more single-row hand patching.

## Data Handling

Original competition datasets are not redistributed here. The repository contains submitted artifacts and compact diagnostics only.
