# Software release validation — record actual results before publication

**Status: not yet executed.** Please record tested date, Windows version, CPU architecture, app filename, SHA-256, tester, input/output screenshots and PASS/FAIL for each check.

| Check | Input / procedure | Expected observation | PASS / FAIL / N/A | Evidence link |
| --- | --- | --- | --- | --- |
| Executable startup | Double-click on clean Windows 10/11 x64 | Application starts without unexpected errors | PENDING | |
| Actual UI dependency | Inspect whether browser, local server or runtime is launched | Document actual mechanism and dependencies | PENDING | |
| English / Chinese | Change interface language | Controls and outputs match selected language | PENDING | |
| Identifier lookup | Known name / CAS from paper | Correct chemical record displayed | PENDING | |
| MOL import | Known valid MOL and invalid MOL | Valid input handled; invalid input reported | PENDING | |
| Reactive group correction | Change a group assignment with a justified case | Matrix recomputes as expected | PENDING | |
| 2-chemical matrix | Documented test substances | Matrix and group-pair trace available | PENDING | |
| 3+ chemical matrix | Documented multi-chemical test set | Distinct pairs evaluated without omission | PENDING | |
| XLSX export | Export matrix | Spreadsheet opens and agrees with UI | PENDING | |
| Offline use | Disconnect internet, rerun core workflow | Offline-supported operations still work | PENDING | |
| Version reproducibility | Same EXE + input on second PC | Equivalent matrix alerts recorded | PENDING | |
| Security/permission | Antivirus and third-party asset review | Outstanding issues explained or resolved | PENDING | |

## Publication-level evidence

Provide input chemical identities, structure records or verified group assignments, original evidence references, expected matrix statuses, observed software outputs, version and any discrepancies for the **90 cases actually reported in the manuscript**. Matrix execution against preassigned groups does not establish the accuracy of molecular recognition or empirical accident-risk prediction.

Do not mark tests as passed without performing them.
