# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.10706`
- Best artifact: `blend_may13_loop09_best_clean_t029_drop_zgb_register_head.csv`
- Best description: `may13_loop09_best_clean_t029_drop_zgb_register_head`

## May 13 Submission Batch

Ten submissions were completed on 2026-05-13 local time. The batch moved the public score from `0.10452` to `0.10706`.

| Description | Public score |
|---|---:|
| `may13_loop01_t029_drop_stpo_zpo_schkg` | `0.10404` |
| `may13_loop02_t029_drop_bgg` | `0.10486` |
| `may13_loop03_t029_drop_iprg` | `0.10486` |
| `may13_loop04_t029_drop_or_tail` | `0.10539` |
| `may13_loop05_t029_drop_all_crossdomain_tail` | `0.10571` |
| `may13_loop06_t029_add_3902_3911_3912` | `0.10513` |
| `may13_loop07_t029_add_448_449b_450b_450d` | `0.10390` |
| `may13_loop08_t029_add_392_393_396_398` | `0.10390` |
| `may13_loop09_best_clean_t029_drop_zgb_register_head` | `0.10706` |
| `may13_loop10_best_clean_t034_add_961_1` | `0.10571` |

## Findings

- The May 13 gain came from cleaning `test_029` after the adult-protection expansion had been established.
- Dropping broad cross-domain residue from `test_029` reached `0.10571`.
- Dropping an old ZGB register-head group from that cleaned base reached `0.10706`, the current best public score.
- Procedure/appeal additions and alternative-guardianship additions on `test_029` were negative as packs.
- `test_034 Art. 961 Abs. 1 ZGB` was neutral on the cleaned base.
- Keep the adult-protection core pack unless explicitly testing removals.
- Avoid global truncation, raw aggregated corpus submissions, and known negative `test_021` OR additions.

## Data Handling

Original competition datasets are not redistributed here. The repository contains submitted artifacts and compact diagnostics only.
