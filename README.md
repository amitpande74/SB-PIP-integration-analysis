# Sleeping Beauty Transposon Integration Site Analysis

[![DOI](https://zenodo.org/badge/DOI/XX.XXXX/zenodo.XXXXXXX.svg)](https://doi.org/XX.XXXX/zenodo.XXXXXXX)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Analysis scripts for studying Sleeping Beauty (SB) transposon integration patterns and their association with non-B DNA structures.

## Citation
If you use this code, please cite:
```
Pande A, Narayanavari S, et al. (2025). Sleeping Beauty transposition is shaped by DNA repair dynamics and replication stress. Molecular Cell [In Press]
```

## Overview
This repository contains computational tools for:
- Detecting palindromic sequences (perfect and imperfect)
- Identifying G-quadruplex (G4Q) motifs
- Predicting triplex-forming regions
- Analyzing integration site enrichment
- Statistical comparison of SB integration vs random controls

## Requirements
- Python 3.7+
- BioPython
- pandas
- numpy
- scipy
- bedtools (command-line)

## Installation
```bash
git clone https://github.com/amitpande74/SB-PIP-integration-analysis.git
cd SB-PIP-integration-analysis
pip install -r requirements.txt
```

## Quick Start
[Add usage examples here]

## Key Findings
- 60% of SB integration sites are flanked by palindromes vs 18% at random TA sites (3.3× enrichment, p<0.0001)
- SB shows preferential integration near microsatellites, G4Qs, and triplex structures
- PIP box mutations shift integration from perfect to imperfect palindromes

## License
MIT License

## Contact
Amit Pande - [your email]
Max Delbrück Center for Molecular Medicine, Berlin
