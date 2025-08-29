# BinKit Function-CVE Mapping

This repository contains mappings between [BinKit 2.0 dataset](https://github.com/SoftSec-KAIST/BinKit) functions and their associated CVEs. Mappings are extracted using binary-to-source debug information.

## Current Coverage

- **Architecture:** x86_64  
- **Compilers:**  
  - Clang 13.0  
  - GCC 11.2.0  

## Future Updates

Additional architectures and compiler versions will be added in subsequent releases.

## Citation

If you use this code, please cite the following paper:

```bibtex
@article{AMOUEI2026112603,
title = {{FIN: Boosting binary code embedding by normalizing function inlinings}},
journal = {Journal of Systems and Software},
volume = {231},
pages = {112603},
year = {2026},
issn = {0164-1212},
doi = {https://doi.org/10.1016/j.jss.2025.112603},
url = {https://www.sciencedirect.com/science/article/pii/S0164121225002729},
author = {Mohammadhossein Amouei and Benjamin C.M. Fung and Philippe Charland},
keywords = {Binary code, Similarity detection, Function inlining, Control flow graph, Random forest},
}
