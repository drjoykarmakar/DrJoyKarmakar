# SensorGenome

> Open infrastructure for AI-driven molecular sensing.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

Molecular sensing experiments are often hard to compare because datasets omit conditions, controls, metadata, uncertainty, and machine-readable structure. SensorGenome is designed to make sensing data benchmark-ready.

## What this repository should contain

- dataset schemas for molecular sensing
- dataset card and benchmark card templates
- active-learning workflow examples
- baseline ML notebooks
- documentation standards for sensing experiments

## Recommended structure

```text
.
├── README.md
├── data/
├── notebooks/
├── src/
├── examples/
├── docs/
├── CITATION.cff
├── LICENSE
└── requirements.txt
```

## Quickstart

```bash
git clone https://github.com/drjoykarmakar/SensorGenome.git
cd SensorGenome
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Define SensorGenome schema v0.1
- [ ] Release example sensing dataset card
- [ ] Add baseline descriptor models
- [ ] Add active-learning tutorial
- [ ] Create first benchmark card

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
