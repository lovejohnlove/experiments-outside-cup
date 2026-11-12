# Experiment 004b — M/M/1/K Queue Regime-Change Prediction

**Status:** EXECUTED, INSPECTED — PASSED with two recorded evidence gaps  
**Reproducibility:** SINGLE RUN — not REPRODUCED  
**Date:** 2026-11-11

## Quick summary

An analytically derived M/M/1/K model predicted the throughput saturation and rejection-rate growth of a bounded-queue simulation across ρ = 1. All visible rows passed ±0.02 tolerance (worst deviation 0.0030). Two evidence gaps remain (truncated λ=0.30 row and missing MeanQ/MaxQ/Status columns from PDF capture). Two fabricated tables were caught and rejected on physics grounds before the real run.

Full report: [EXPERIMENT_004b_REPORT.md](../EXPERIMENT_004b_REPORT.md)

## Gaps still open
1. λ=0.30 row not visible in capture
2. MaxQ gate and Obs.MeanQ columns truncated

## Next
- Close gaps with full-width text capture (same seed)
- Second independent run for REPRODUCED status
- Experiment 004c: surrogate-model prediction of an unknown transition
