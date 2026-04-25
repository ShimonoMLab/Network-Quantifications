# Network-Quantifications

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxxx)

## Network Quantification Code for Cortical Microconnectome Analysis

This repository provides MATLAB code for reproducing network quantification analyses and figures associated with:

**Kajiwara, M., Nomura, R., Goetze, F., Kawabata, M., Isomura, Y., Akutsu, T., & Shimono, M. (2021). _Inhibitory neurons exhibit high controlling ability in the cortical microconnectome_. PLOS Computational Biology, 17(4), e1008846. https://doi.org/10.1371/journal.pcbi.1008846**

## Overview

These scripts reproduce figure-level analyses and network quantifications used to evaluate cortical microconnectome properties, including excitatory/inhibitory cell categories, k-core centrality, feedback vertex set-related analyses, degree distributions, firing-rate distributions, and connectivity-strength distributions.

## Requirements

- MATLAB
- Statistics and Machine Learning Toolbox
- Signal Processing Toolbox

## How to Run

1. Save all files in one directory.
2. Open MATLAB in that directory.
3. Add all subfolders to the MATLAB path:

```matlab
addpath(genpath('./'));
```

4. Run the relevant figure script:

```matlab
fig*
```

## Example Script Functions

- `fig5b.m`: degree histograms / number of connections
- `fig5ce.m`: firing-rate histograms and connectivity-strength histograms for excitatory and inhibitory neurons
- `fig5d.m`: total numbers and relative ratios of excitatory and inhibitory neurons
- `fig6ab.m`: k-core analyses for excitatory and inhibitory neurons across cortical layers
- `fig7ab.m`: feedback vertex set-related analyses for excitatory and inhibitory neurons
- `fig7c.m`: dataset preparation for comparing high k-core nodes and feedback vertex set nodes

## Citation

If you use this repository in any way that contributes to a publication, preprint, thesis, presentation, software tool, benchmark comparison, dataset analysis, or derivative codebase, please cite the peer-reviewed article below.

Please cite the paper if you:

- use the original MATLAB code
- modify or extend the code
- reuse part of the figure reproduction or network quantification workflow
- use the network metrics, k-core, FVS, or E/I comparison procedure
- use the dataset structure or preprocessing procedure
- build upon the idea of quantifying controlling ability in cortical microconnectome networks

### Peer-reviewed article

For the scientific method, results, and interpretation, please cite:

**Kajiwara, M., Nomura, R., Goetze, F., Kawabata, M., Isomura, Y., Akutsu, T., & Shimono, M. (2021). _Inhibitory neurons exhibit high controlling ability in the cortical microconnectome_. PLOS Computational Biology, 17(4), e1008846. https://doi.org/10.1371/journal.pcbi.1008846**

### Archived software release

The GitHub repository has been archived on Zenodo:

**Shimono, M. (2026). _Network-Quantifications: Network quantification code for cortical microconnectome analysis_. Zenodo. https://doi.org/10.5281/zenodo.xxxxxxxx**

Please cite the peer-reviewed article for the scientific method, results, and interpretation, and cite the Zenodo DOI when referring specifically to this archived software release.

## Suggested Citation Sentence

This repository provides MATLAB code for reproducing network quantification and figure-level analyses of cortical microconnectome organization and excitatory/inhibitory controlling ability.
