# Chemical Compatibility Analyzer

> **Release status:** Pre-publication, binary-only Windows release candidate. This repository **does not yet contain the full source code** of the computational engine and should not be described as an open-source software repository.

Chemical Compatibility Analyzer is a reactive-group-based screening tool intended to support **preliminary assessment of potentially incompatible chemical contacts** in early-stage process development, raw-material substitution, chemical storage and segregation planning, and laboratory work.

## Download and use

Once a version is published, obtain the Windows 64-bit executable from **Releases → Assets**. The candidate release name is `Chemical_Compatibility_Analyzer_Windows_x64_v0.1.0.exe`. The executable is intended to be used without the separate CSS, JavaScript, and Go build files included in earlier development workflows; actual behavior and local/browser dependencies must be verified on Windows before public publication.

### Intended workflow

1. Enter chemical names or CAS identifiers, or import supported MOL files.
2. Review the proposed reactive-group assignments and correct assignments using appropriate chemical-specific references.
3. Generate pairwise compatibility screening matrices and inspect the contributing group pairs.
4. Export results where supported; retain the software version, inputs and relevant operating conditions in the assessment record.

## Limitations and safety scope

This tool produces **qualitative preliminary screening alerts only**, based on reactive-group assignments and group-compatibility rules. It does **not** predict reaction products, heat release, pressure rise, accident probability or safe mixing conditions. An apparently compatible result is not proof of safety. Users should consult chemical-specific SDS information, concentration/formulation data and professional process-safety review before operational decisions.

## Availability and licensing

- **Executable**: intended for public download and use with permission from the developing laboratory, subject to the final distribution terms approved by the rights holder.
- **Source**: the complete computational-engine source code is not included in this binary-only release.
- **License**: final redistribution/modification terms to be confirmed; please do not characterize the program as AGPL-, GPL- or MIT-licensed until appropriate permission and source-release steps are completed.
- **Third-party data**: data, matrices and chemical records that are not owned by the laboratory may have their own terms of reuse; third-party redistribution rights must be verified separately.

## Validation and citation

The software must be functionally tested on Windows before a formal release. See [`VALIDATION_PROTOCOL.md`](VALIDATION_PROTOCOL.md).

An archived release DOI should be added only after a verified Zenodo record is published. Current Windows candidate SHA-256:

`e99b46e9eea9dc994e4727666ba8752006b2f73d81141abaf581c568ebde1b0f`

Please cite the **specific version** used to generate results and keep corresponding inputs and outputs available wherever redistribution is permitted.
