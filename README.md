# Chemical Compatibility Analyzer

**Version:** 0.1.0  
**Platform:** Windows 64-bit  
**Software DOI:** https://doi.org/10.5281/zenodo.23491523

## Overview

Chemical Compatibility Analyzer is a locally deployable chemical safety screening tool developed for preliminary compatibility assessment during chemical process development, raw-material substitution, chemical storage planning, and laboratory operations.

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

**Latest Release:** [Chemical Compatibility Analyzer v0.1.0](https://github.com/da12459/Chemical-Compatibility-Analyzer/releases/tag/v0.1.0)

Download the Windows 64-bit executable from the Assets section of the release page.

The distributed executable contains the packaged software components and does not require the original CSS, JavaScript, or Go development files to be placed alongside it.

## Basic Usage

1. Enter chemical names or CAS Registry Numbers, or import supported MOL files.
2. Review the automatically identified reactive-group categories.
3. Manually select, add, or remove categories when necessary.
4. Perform compatibility analysis for the selected chemicals.
5. Examine the chemical compatibility assessment matrix and the underlying group-pair results.
6. Export the assessment matrix to Excel when needed.

## Assessment Method

The software uses an established 68-category reactive-group compatibility matrix as the basis for qualitative compatibility screening.

For each chemical pair, all assigned reactive-group combinations are evaluated, and the resulting compatibility alerts are summarized in a chemical compatibility assessment matrix.

The system supports automated reactive-group identification and optional manual adjustment.

## Evaluation

The associated research reports 90 chemical-contact cases compiled from publicly accessible reports and literature.

The software automatically identified reactive-group categories and performed compatibility screening, generating 81 "Incompatible" and 9 "Caution Required" alerts.

These cases demonstrate the integrated software workflow but do not independently establish automated identification accuracy or quantitative predictions of real-world reaction consequences.

## Scope and Limitations

The software is intended for qualitative preliminary compatibility screening.

A "Compatible" result does not guarantee that chemical mixing, processing, or storage is safe.

The software does not quantitatively predict reaction products, heat release, pressure buildup, accident probability, or accident severity.

Users should consider chemical-specific safety data sheets, concentration, physical form, operating conditions, and professional safety assessments before making operational decisions.

## Software Availability and Citation

**GitHub Repository:**  
https://github.com/da12459/Chemical-Compatibility-Analyzer

**GitHub Release:**  
https://github.com/da12459/Chemical-Compatibility-Analyzer/releases/tag/v0.1.0

**Zenodo DOI:**  
https://doi.org/10.5281/zenodo.23491523

Researchers using this software should cite the corresponding Zenodo software record.

## License and Copyright

The software is distributed under the [Chemical Compatibility Analyzer Freeware License](LICENSE.txt).

Copyright © 2026 Xiangjuan Qi. All rights reserved.

The software executable may be downloaded and used free of charge under the stated license terms.

The complete computational-engine source code is not included in this release. Modification and redistribution require permission as specified in the license.

This is a publicly available executable software release, not a complete open-source code distribution.
