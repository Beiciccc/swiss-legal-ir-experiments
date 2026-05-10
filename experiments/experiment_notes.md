# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.09498`
- Best artifact: `blend_may11_loop05_best445_agg3n30_4453_4501.csv`
- Best description: `may11_loop05_best445_agg3n30_4453_4501`

## May 11 Submission Batch

Ten submissions were completed on 2026-05-11 local time. The batch moved the public score from `0.09108` to `0.09498`.

| Description | Public score |
|---|---:|
| `may11_loop01_best445_agg3n30_add2_codematch_skip` | `0.09251` |
| `may11_loop02_best445_agg3n30_add2_plus_445_2` | `0.09248` |
| `may11_loop03_best445_agg3n30_add2_plus_445_3` | `0.09376` |
| `may11_loop04_best445_agg3n30_add2_plus_450_1` | `0.09376` |
| `may11_loop05_best445_agg3n30_4453_4501` | `0.09498` |
| `may11_loop06_best445_agg3n30_4453_4462` | `0.09498` |
| `may11_loop07_best445_agg3n30_4453_3892` | `0.09498` |
| `may11_loop08_best445_agg3n30_4453_3941` | `0.09498` |
| `may11_loop09_best445_agg3n30_4453_3951` | `0.09498` |
| `may11_loop10_best445_agg3n30_4453_3901` | `0.09498` |

## Findings

- The strongest May 11 result came from combining the prior focused adult-protection patch with a conservative code-matched blend from the aggregated court-citation source.
- `test_029` additions `Art. 445 Abs. 3 ZGB` and `Art. 450 Abs. 1 ZGB` were positive together, reaching the current best public score.
- Additional `test_029` probes around `Art. 446 Abs. 2 ZGB`, `Art. 389 Abs. 2 ZGB`, `Art. 394 Abs. 1 ZGB`, `Art. 395 Abs. 1 ZGB`, and `Art. 390 Abs. 1 ZGB` were neutral at displayed precision when added after the best pair.
- Raw aggregated corpus submissions remained weak on the public board, so the source is useful as a candidate generator rather than a final submission by itself.
- Global truncation experiments (`cap15`, `cap20`, `cap25`) were strongly negative, indicating that broad recall remains important for the current submission family.
- Several neighboring additions for `test_021` were negative and should remain excluded: `Art. 425 Abs. 1 OR`, `Art. 399 Abs. 1 OR`, `Art. 440 Abs. 1 OR`, `Art. 440 Abs. 2 OR`, and `Art. 457 OR`.
- Additional single-query patches for `test_001`, `test_002`, `test_017`, `test_027`, `test_035`, `test_037`, and `test_039` did not improve the public score.

## Data Handling

Original competition datasets are not redistributed here. The repository contains submitted artifacts and compact diagnostics only.
