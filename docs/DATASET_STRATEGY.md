# Dataset strategy

## Goal

Build datasets that are useful to both experimental chemists and machine-learning researchers.

## Dataset levels

### Level 1: Raw curated table

A clean table with source references, molecular identifiers, and measured outputs.

### Level 2: Machine-readable experimental record

Adds conditions, instruments, solvents, concentrations, controls, protocols, uncertainty, and metadata.

### Level 3: Benchmark-ready dataset

Adds standardized splits, tasks, metrics, baselines, and limitations.

## Priority dataset families

- molecular sensing datasets
- fluorescent probe datasets
- bimane fluorophore data
- spectroscopy datasets
- transporter inhibitor datasets
- xylazine/adulterant analytical data

## Required metadata

- molecule ID
- SMILES/InChI
- assay type
- target or analyte
- conditions
- concentration
- solvent/media
- instrument
- response variable
- units
- uncertainty or replicate information
- source citation
- license
