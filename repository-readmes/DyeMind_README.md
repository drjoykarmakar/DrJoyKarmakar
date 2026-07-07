# DyeMind

> AI for fluorescent probe and fluorophore discovery.

[![Status](https://img.shields.io/badge/status-active-00D4FF.svg)](#roadmap)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Why this exists

Fluorescent probe discovery combines molecular design, photophysics, sensing, and biological context. DyeMind is the long-term AI workspace for probe and fluorophore design.

## What this repository should contain

- fluorescent probe data model
- molecular representation ideas
- prediction task definitions
- generative design roadmap
- links to BimaneDB and SensorGenome

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
git clone https://github.com/drjoykarmakar/DyeMind.git
cd DyeMind
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Reproducibility

Document data source, preprocessing, package versions, random seeds, train/test split, evaluation metrics, and known limitations.

## Roadmap

- [ ] Define data schema
- [ ] Collect public fluorophore examples
- [ ] Add prediction tasks
- [ ] Add generative design notes
- [ ] Connect to SensorGenome benchmarks

## Citation

Add a CITATION.cff file and cite related papers, datasets, or repositories.

## License

MIT unless otherwise specified.
