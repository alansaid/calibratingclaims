# Calibrating Reproduced Claims in Recommender Systems

This repository contains the supplementary material for:

> Alan Said. *Calibrating Reproduced Claims in Recommender Systems.*  
> FRAME'26: Methodology First - Rethinking Research Assessment in RecSys Workshop, co-located with the 20th ACM Conference on Recommender Systems, 2026.

The paper introduces **claim calibration** as the process of stating the strongest claim supported by a follow-up study, together with the conditions under which it holds and the parts of the original claim that remain unresolved.

## Supplementary material

The file [`calibrated-claims.xlsx`](calibrated-claims.xlsx) contains the coding records for the five original--follow-up paper pairs analyzed in the paper.

Each row contains the two papers and the seven fields of the Claim Evidence Profile:

| Field | Description |
|---|---|
| Original claim | The conclusion stated or implied by the original study |
| Scope | The task, data, models, baselines, protocol, metrics, and other conditions attached to the claim |
| Study relationship | How the follow-up study relates to the original setup and artifacts |
| Reproduction target | The result, comparison, or conclusion tested by the follow-up study |
| Reported results | The results reported by the follow-up study that bear on the claim |
| Calibrated claim | The strongest conclusion supported by the reported results, taking their stated limitations into account |
| Unresolved scope | Parts of the original claim and conditions that were not tested |

The spreadsheet also includes source locations so that the coding can be traced back to the corresponding papers.

## Coding rules

Explicit claims were preferred over implied claims. Results that could not be compared directly were treated as **not comparable**, while parts of a claim not examined by the follow-up study were treated as **not tested**. When results differed across datasets, metrics, implementations, or other conditions, these differences were retained in the calibrated claim rather than collapsed into a single outcome.

## Citation

```bibtex
@inproceedings{said2026calibrating,
  author    = {Alan Said},
  title     = {Calibrating Reproduced Claims in Recommender Systems},
  booktitle = {FRAME'26: Methodology First - Rethinking Research Assessment in RecSys Workshop},
  year      = {2026}
}
