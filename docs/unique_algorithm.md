# Unique Prototype Algorithm

## Algorithm

**WuShiftAwareComputerVisionSelectEngine** (`P076-Wu-ComputerVision`)

## Professor Alignment

- Professor: Tianfu Wu
- Research area: Computer vision, deep learning, interpretable visual modeling
- Focus terms: Computer vision, interpretable visual modeling

## Core Mechanism

This prototype prioritizes distribution-shift failures with confidence-aware calibration penalties.

## Decision Rule

Rank seed cases by vision-specific priority score with Wu-aligned focus term 'Computer vision'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `vision` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Tianfu Wu's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
