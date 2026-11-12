# M2 — Range Finder Module Optimization

**Milestone:** M2 — Optimize  
**Package type:** Planning/demo assets and evidence organization starter.

This repository is organized around the six M2 assessment criteria for optimizing the Range Finder Module detector on edge devices.

## M2 criteria
1. `01_export_to_onnx/` — ONNX export script and export record artifact.
2. `02_convert_and_run_live/` — Live edge runtime check (ONNX Runtime / TensorRT / TFLite) and live verification records.
3. `03_accuracy_check/` — Accuracy comparison (mAP@0.5, precision, recall) before vs. after optimization on the same test set.
4. `04_fair_benchmark/` — Fair benchmarking protocol (20 warm-up runs, 100+ timed runs at batch 1; median & p95 latency, FPS, model size, CPU/accelerator load, temperature).
5. `05_cpu_vs_accelerator_stack/` — CPU vs. accelerator comparison table and end-to-end edge inference software stack diagram.
6. `06_target_and_tradeoff/` — Target vs. actual results scorecard and trade-off analysis for edge deployment.

## Important evidence status
- Visuals in this starter package provide reference layouts and illustrative templates.
- Fill all `TODO` and `TBD` fields in the markdown and CSV reports with genuine measured metrics from your device run before final submission.

## Project terminology
The optimization target is the Range Finder Module detector (trained in M1). Sealed/opened box detection remains a separate workstream.
