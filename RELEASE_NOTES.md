# Release Notes — Chemical Compatibility Analyzer v0.1.0

**Release Date:** October 20, 2026  
**Release Status:** Public Release  
**Platform:** Microsoft Windows (64-bit)

## Overview

Chemical Compatibility Analyzer v0.1.0 is a locally deployable software application developed for preliminary chemical compatibility screening during chemical process development, raw-material substitution, chemical storage planning, and laboratory operations.

The software integrates chemical identification, automated reactive-group assignment, manual category adjustment, and matrix-based compatibility assessment.

## Main Features

- Chemical identification using names and CAS Registry Numbers.
- MOL-file import and structure-assisted reactive-group identification.
- Manual selection, addition, and removal of reactive-group categories.
- Compatibility assessment based on an established 68-category reactive-group compatibility matrix.
- Pairwise compatibility assessment for 2–20 chemicals.
- Traceable group-pair compatibility results.
- Chinese and English user interfaces.
- Excel export of chemical compatibility assessment matrices.
- Offline-capable operation using locally available data.

## Software Distribution

**Executable:** `Chemical_Compatibility_Analyzer_Windows_x64_v0.1.0.exe`

**GitHub Release:** https://github.com/da12459/Chemical-Compatibility-Analyzer/releases/tag/v0.1.0

**Zenodo DOI:** https://doi.org/10.5281/zenodo.23491523

**SHA-256:** `e99b46e9eea9dc994e4727666ba8752006b2f73d81141abaf581c568ebde1b0f`

The current release provides the Windows executable. The complete computational-engine source code is not included.

## License and Copyright

The software is distributed under the Chemical Compatibility Analyzer Freeware License.

Copyright © 2026 Xiangjuan Qi. All rights reserved.

Public download and free use are permitted under the terms specified in `LICENSE.txt`.

## Validation and Limitations

The software supports qualitative preliminary chemical compatibility assessment. Its results are based on reactive-group assignments and established compatibility relationships.

The associated research describes the application of automated reactive-group identification and compatibility analysis to 90 chemical-contact cases. These cases illustrate the integrated analysis workflow but do not independently establish the accuracy of all reactive-group assignments or predict actual reaction consequences.

Detailed software functionality checks should be documented in `VALIDATION_PROTOCOL.md`.

The software does not replace chemical-specific experimental verification, safety data sheet review, or professional process safety assessment.
