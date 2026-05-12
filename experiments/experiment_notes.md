# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.10452`
- Best artifact: `blend_may12_loop10_t029_all_adult_protection.csv`
- Best description: `may12_loop10_t029_all_adult_protection`

## May 12 Submission Batch

Ten submissions were completed on 2026-05-12 local time. The batch moved the public score from `0.09498` to `0.10452`.

| Description | Public score |
|---|---:|
| `may12_loop01_t029_4501_4462` | `0.09617` |
| `may12_loop02_t029_4501_3892` | `0.09617` |
| `may12_loop03_t029_4501_3941` | `0.09617` |
| `may12_loop04_t029_4501_3951` | `0.09617` |
| `may12_loop05_t029_4501_3901` | `0.09617` |
| `may12_loop06_t029_4501_all_prev_pos` | `0.10063` |
| `may12_loop07_t029_add_3891_4461` | `0.09732` |
| `may12_loop08_t029_add_4502_4503` | `0.09732` |
| `may12_loop09_t029_add_450c` | `0.09492` |
| `may12_loop10_t029_all_adult_protection` | `0.10452` |

## Findings

- The May 12 gain came from focused `test_029` adult-protection expansion on top of the May 11 best family.
- Single additions around `Art. 446 Abs. 2 ZGB`, `Art. 389 Abs. 2 ZGB`, `Art. 394 Abs. 1 ZGB`, `Art. 395 Abs. 1 ZGB`, and `Art. 390 Abs. 1 ZGB` each reached `0.09617`.
- Combining those prior positive additions reached `0.10063`.
- The broader adult-protection pack reached `0.10452`, the current best public score.
- `Art. 450c ZGB` alone was negative (`0.09492`) and should not be tested alone again.
- Raw aggregated corpus submissions remained weak on the public board, so the source is useful as a candidate generator rather than a final submission by itself.
- Global truncation experiments (`cap15`, `cap20`, `cap25`) were strongly negative, indicating that broad recall remains important for the current submission family.
- Several neighboring additions for `test_021` were negative and should remain excluded: `Art. 425 Abs. 1 OR`, `Art. 399 Abs. 1 OR`, `Art. 440 Abs. 1 OR`, `Art. 440 Abs. 2 OR`, and `Art. 457 OR`.

## Data Handling

Original competition datasets are not redistributed here. The repository contains submitted artifacts and compact diagnostics only.
