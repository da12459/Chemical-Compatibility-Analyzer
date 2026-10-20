# Software Validation Protocol

## 1. General Information

**Software:** Chemical Compatibility Analyzer  
**Version:** 0.1.0  
**Platform:** Windows 64-bit

**Executable:** `Chemical_Compatibility_Analyzer_Windows_x64_v0.1.0.exe`

**SHA-256:** `e99b46e9eea9dc994e4727666ba8752006b2f73d81141abaf581c568ebde1b0f`

**GitHub Release:** https://github.com/da12459/Chemical-Compatibility-Analyzer/releases/tag/v0.1.0

**Zenodo DOI:** https://doi.org/10.5281/zenodo.23491523

## 2. Validation Objective

The objective is to document the functional performance of the Chemical Compatibility Analyzer, including chemical identification, MOL-file import, automated reactive-group assignment, manual category adjustment, compatibility calculations, bilingual interface operation, and report export.

The protocol distinguishes functional execution from independent scientific validation of chemical classification accuracy.

## 3. Functional Validation Checklist

The status "NOT RECORDED" indicates that verified test evidence has not yet been entered in this document. It does not necessarily mean that the function has never been used.

| Test Item | Expected Result | Status |
|---|---|---|
| Windows executable startup | Application starts without unexpected errors | NOT RECORDED |
| Chemical name lookup | Correct indexed chemical record is retrieved | NOT RECORDED |
| CAS number lookup | Corresponding indexed chemical information is displayed | NOT RECORDED |
| MOL-file import | Supported molecular structures are imported and processed | NOT RECORDED |
| Invalid MOL-file handling | Invalid or unsupported files produce appropriate feedback | NOT RECORDED |
| Automated reactive-group identification | Candidate reactive groups are generated from chemical information | NOT RECORDED |
| Manual reactive-group selection | Users can select or adjust reactive-group categories | NOT RECORDED |
| Multi-group compatibility calculation | Relevant combinations of assigned groups are evaluated | NOT RECORDED |
| Two-chemical assessment | Pairwise compatibility results are generated correctly | NOT RECORDED |
| Multiple-chemical assessment | Chemical pairs are evaluated without unintended omission | NOT RECORDED |
| Detailed result inspection | Underlying group-pair results can be inspected | NOT RECORDED |
| Chinese/English interface | Interface labels and assessment results use the selected language | NOT RECORDED |
| Excel export | Exported assessment matrices can be opened and inspected | NOT RECORDED |
| Offline operation | Supported functions operate without external Internet access | NOT RECORDED |
| Repeated calculation | Identical inputs produce consistent results under the same settings | NOT RECORDED |

For each completed test, replace "NOT RECORDED" with "PASS" or "FAIL" and retain the test inputs and supporting evidence.

## 4. Evaluation Using 90 Chemical-Contact Cases

The associated manuscript reports an evaluation using 90 chemical-contact cases compiled from publicly accessible reports and literature.

For each case, the integrated software workflow involves:

1. Input of chemical information.
2. Automated identification of reactive-group categories.
3. Compatibility analysis using the established 68-category reactive-group compatibility matrix.
4. Generation of chemical-pair compatibility alerts.
5. Inspection of the corresponding group-pair results.

The reported assessment results include:

- Total evaluated cases: 90
- Incompatible alerts: 81
- Caution Required alerts: 9

These results demonstrate the execution of the integrated software workflow for the reported cases.

Independent validation of automated reactive-group identification requires comparison with independently verified reference assignments. Agreement with chemical-specific experimental observations must be evaluated separately.

## 5. Recommended Case-Level Documentation

For each of the 90 cases, retain the following information:

- Case identifier.
- Chemical names and CAS numbers, where available.
- Literature or public-report source.
- Input method.
- Automatically identified reactive groups.
- Any manual changes and their justification.
- Relevant group-pair compatibility results.
- Final software-generated alert.
- Reference evidence and interpretation.
- Software version.

Cases involving manual modifications should be explicitly distinguished from cases evaluated without manual intervention.

## 6. Test Environment and Evidence

For each formal test session, record:

- Test date.
- Tester.
- Windows version and system architecture.
- Executable filename and SHA-256.
- Input files or chemical combinations.
- Expected outcome.
- Observed outcome.
- PASS/FAIL status.
- Screenshots or exported results.
- Details of any errors or limitations.

## 7. Safety and Interpretation

Successful software execution does not independently establish chemical safety or prediction accuracy.

Compatibility screening results depend on the assigned reactive-group categories, underlying compatibility rules, and chemical-specific conditions.

The software is intended to support preliminary hazard identification, not to replace professional process safety analysis or experimental verification.
