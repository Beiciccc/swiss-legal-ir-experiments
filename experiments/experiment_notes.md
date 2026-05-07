# Experiment Notes

This file summarizes public-score findings from the tracked submission archive.

## Current Best

- Best public score: `0.09108`
- Best artifact: `blend_may08_loop10_t029_add_zgb445_1.csv`

## Findings

- The strongest May 8 result came from a conservative code-matched blend using the aggregated court-citation source, followed by a focused adult-protection addition.
- Raw aggregated corpus submissions remained weak on the public board, so the source is useful as a candidate generator rather than a final submission by itself.
- Global truncation experiments (`cap15`, `cap20`, `cap25`) were strongly negative, indicating that broad recall remains important for the current submission family.
- `test_021` improvements around `Art. 449 OR` and `Art. 447 Abs. 1 OR` were positive relative to earlier baselines.
- Several neighboring additions for `test_021` were negative and should remain excluded: `Art. 425 Abs. 1 OR`, `Art. 399 Abs. 1 OR`, `Art. 440 Abs. 1 OR`, `Art. 440 Abs. 2 OR`, and `Art. 457 OR`.
- Additional single-query patches for `test_001`, `test_002`, `test_017`, `test_027`, `test_035`, `test_037`, and `test_039` did not improve the public score.
- Small edits on `test_012`, `test_034`, and `test_040` were mostly neutral in recent runs.

## Data Handling

Original competition datasets are not redistributed here. The repository contains submitted artifacts and compact diagnostics only.
