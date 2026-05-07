# Blind_Artifacts

Artifacts and reproduction package for the blind benchmark experiments.

## Contents

| Directory | Description |
|---|---|
| `RQ1_Benchmark/` | Known-technique vs. proactive probe detection rates across 6 analysis environments |
| `RQ2_Benchmark/` | Root-cause family classification with per-environment detection reports |
| `RQ3_Benchmark/` | B0–B4 knowledge-ablation Pin hardening study using a 46-sample blind benchmark |
| `scripts/` | Build and validation reproduction scripts |

## Getting Started

See [`REPRODUCTION_GUIDE.md`](REPRODUCTION_GUIDE.md) for step-by-step reproduction instructions.

## Requirements

- Windows 11
- MSVC 2022
- Python 3.10+
- x64dbg
- ScyllaHide 1.4
- Intel Pin 4.2
- HyperDbg 0.18.1 *(optional)*

See [`INSTALL.md`](INSTALL.md) for detailed installation instructions.
