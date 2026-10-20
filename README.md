# Chemical Compatibility Analyzer

**Version:** 0.1.0  
**Platform:** Windows 64-bit  
**Software DOI:** https://doi.org/10.5281/zenodo.23491523

## Overview

Chemical Compatibility Analyzer is a locally deployable chemical safety screening tool developed to support preliminary compatibility assessments during new chemical process development, raw-material substitution, chemical storage planning, and laboratory operations.

The software integrates chemical identification, automated reactive-group assignment, and compatibility evaluation based on an established 68-category reactive-group compatibility matrix.

## Main Features

- Chemical lookup using names and CAS Registry Numbers.
- MOL-file import and structure-assisted reactive-group identification.
- Manual selection, addition, and removal of reactive-group categories.
- Pairwise compatibility analysis for 2–20 chemicals.
- Traceable reactive-group compatibility results.
- Chinese and English user interfaces.
- Excel export of chemical compatibility assessment matrices.
- Offline-capable operation using locally available data.

## Download and Installation

**Latest release:** [Chemical Compatibility Analyzer v0.1.0](https://github.com/da12459/Chemical-Compatibility-Analyzer/releases/tag/v0.1.0)

Download the Windows executable from the **Assets** section of the release page. The distributed version is intended to run without separately installing the original CSS, JavaScript, or Go source files.

## Basic Usage

Enter chemical names or CAS Registry Numbers, or import supported MOL files. Review the automatically identified reactive-group categories and make manual adjustments when necessary.

After selecting the chemicals, perform compatibility analysis and examine the resulting chemical compatibility assessment matrix. Detailed group-pair results can be inspected, and the assessment matrix can be exported to Excel.

## Scope and Limitations

This software provides qualitative preliminary compatibility screening. Results are based on reactive-group assignments and established group compatibility relationships.

A "Compatible" result does not guarantee safe mixing or storage. The software does not quantitatively predict reaction products, heat release, pressure buildup, or accident severity.

Users should consider chemical-specific safety data sheets, concentrations, physical forms, operating conditions, and professional safety assessments before making operational decisions.

## Software Availability and Citation

The Windows executable is publicly available through GitHub and archived on Zenodo.

**Zenodo DOI:** https://doi.org/10.5281/zenodo.23491523

Please cite the archived software version when using this tool in academic publications.

## License and Copyright

The software is distributed under the [Chemical Compatibility Analyzer Freeware License](LICENSE.txt).

Copyright © 2026 Xiangjuan Qi. All rights reserved.

The executable may be downloaded and used free of charge under the stated license terms. The complete computational-engine source code is not included in this release. Modification and redistribution require permission as specified in the license.

This is a publicly available executable software release, not a complete open-source code distribution.
