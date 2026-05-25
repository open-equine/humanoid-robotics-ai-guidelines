
<p align="center">
  <img src="https://raw.githubusercontent.com/open-equine/humanoid-robotics-ai-equine-safety-guidelines/main/assets/logo.png" alt="Open Equine Intelligence Systems" width="180"/>
</p>

<h1 align="center">Content Quality Test Artifacts</h1>
<h2 align="center">Definition of Devices — OE-GL-000 Update OE-GL-000_DOD-Framework</h2>
<h3 align="center">Open Equine Intelligence Systems — Horse AI</h3>
<h4 align="center">Open Equine — A TechXZone Pvt Ltd Initiative</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Reference-OE--GL--000--DOD--CQ-navy" alt="OE-GL-000-DOD-CQ"/>
  <img src="https://img.shields.io/badge/Status-Published-brightgreen" alt="Published"/>
  <img src="https://img.shields.io/badge/Version-0.12-blue" alt="Version 0.12"/>
  <img src="https://img.shields.io/badge/Test%20Runs-2-teal" alt="2 Test Runs"/>
  <img src="https://img.shields.io/badge/Defects%20at%20Release-0-brightgreen" alt="0 Defects"/>
  <a href="https://creativecommons.org/licenses/by-sa/4.0/"><img src="https://img.shields.io/badge/Documents-CC--BY--SA%204.0-green.svg" alt="CC-BY-SA 4.0"/></a>
</p>

---

## About This Folder

This folder contains the Content Quality test execution artifacts for the Definition of Devices document — **OE-GL-000-DOD-Framework-v1.2.md**.

Open Equine Intelligence Systems publishes its quality control artifacts alongside every document release. This folder is the evidence that OE-GL-000 was tested rigorously before public release, that defects were logged and resolved, and that the document passed full verification prior to publication.

---

## Test Execution Summary

| | |
|---|---|
| **Document Tested** | OE-GL-000-DOD-Framework-v1.2.md |
| **Test Suite** | OE-GL-000-DOD-ContentQuality-v0_12.xlsx |
| **Total Test Cases** | 30 |
| **Test Runs Conducted** | 2 |
| **Defects at Release** | 0 |
| **Executed By** | Open Equine |
| **Version** | 1.1 → 1.2 |

---

## Test Run History

| Run | Document Version | Pass | Fail | Not Applicable | Defects Fixed |
|---|---|---|---|---|---|
| Run 1 | OE-GL-000 v1.1 | 14 | 1 | 15 | — |
| Run 2 | OE-GL-000 v1.2 | 15 | 0 | 15 | TC-CQ-025 |

**Defect resolved between Run 1 and Run 2:**
TC-CQ-025 — Veterinary authority specifications absent from OE-GL-000. Resolved by adding the Veterinary Authority section in v1.2.

---

## Files in This Folder

| File | Description |
|---|---|
| OE-GL-000-DOD-ContentQuality-v0_12.xlsx | Complete test execution file — 6 tabs |

---

## About the Test Execution File

The test execution file contains six tabs:

| Tab | Description |
|---|---|
| Cover | Document identity, purpose, column guide, valid values, contribution information |
| Test Summary Report | Executed results — Run 1 and Run 2, fail log, not applicable log, test run history |
| OEGL-00-DOD-CQ Test Execution | All 30 test cases with full execution results |
| OEGL-00-DOD-CQ Test Cases | Blank test cases for external contributors to execute |
| Test Summary Report Template | Blank summary report template for external contributors |
| Change Log | Version and change history |

---


## Understanding the Test Cases File — A Guide for Equestrian Professionals

This section explains what the test cases file is and what it does — in plain language, without assuming any technology background.

### What is a Test Case?

A test case is a written question or check applied to a document to verify whether it meets a defined standard. Think of it as an inspection checklist. Before a horse competes, a vet checks its health against a checklist. Before a stable installs new equipment, it checks whether it meets safety standards. A test case does the same thing for a written guidelines document — it checks whether the document says what it is supposed to say, says it accurately, and says it completely.

### What does OE-GL-000-DOD-ContentQuality-v0_12.xlsx check?

This file contains 30 test cases applied to the Definition of Devices document — OE-GL-000. The test cases are organised into five quality modules:

**Module 1 — Completeness**
Checks that every type of technology relevant to equine stables is defined in the document. This includes humanoid machines, robotic dogs, drones, autonomous ground vehicles, sensor systems, and AI software. It also checks that all prohibited uses and human oversight requirements are present.

**Module 2 — Relevance and Accuracy**
Checks that everything written about horse behaviour is factually correct, that all technical claims about machines are verified against manufacturer specifications, and that all named manufacturers and their machines are real and accurately described.

**Module 3 — Use Case Coverage**
Checks that the document addresses real stable scenarios — a humanoid introduced to a stable for the first time, a robot near a distressed horse, a robot near a foal, a veterinary procedure in progress, an AI tool failure, and a robotic system operating without a human present.

**Module 4 — Audience Appropriateness**
Checks that the document is readable and useful for all audiences — equestrian professionals without a technology background, engineers without an equestrian background, veterinary professionals, and regulatory authorities. Specifically checks that no section talks down to any reader or assumes knowledge that excludes them.

**Module 5 — Gaps and Future Coverage**
Checks that wherever the document does not yet cover a topic, it says so clearly. No gaps are hidden. No section creates a false impression that everything has been addressed when it has not.

### What do the results mean?

Each test case returns one of three results:

**Pass** — The document meets the standard for this check.

**Fail** — The document does not meet the standard. A defect is logged and must be fixed before the document can be released.

**Not Applicable** — This check cannot be applied to this document because the content it is looking for belongs in a different document. It will be checked against that document when it is published.

### What happened in the two test runs?

**Run 1** tested version 1.1 of the document. 14 test cases passed. 1 failed — the veterinary authority chain was referenced but not fully defined. 15 were not applicable because their content belongs in future guidelines documents.

**Run 2** tested version 1.2. The veterinary authority section was added and the defect was resolved. All 15 previously passing test cases passed again. The defect passed. Zero failures at release.

### Why is this published?

Any stable, breeding operation, equestrian organisation, or veterinary body that wants to develop their own safety guidelines for humanoids, robotics, and AI can use these same test cases to check their own work. If your guidelines pass all 30 test cases, it confirms they meet the Open Equine Intelligence Systems content quality standard for this domain.

You do not need a technology background to read the test cases. The questions are written in plain language. You do need a willingness to read your own guidelines carefully and answer each question honestly.

---
## How to Use These Test Cases

The blank test cases tab — **OEGL-00-DOD-CQ Test Cases** — is a public instrument. Any stable, equestrian organisation, veterinary authority, or technology developer can download this file and execute the test cases against their own framework or guidelines document.

If all test cases pass against your framework, it confirms that your framework meets the content quality standard established by Open Equine Intelligence Systems for the Definition of Devices.

Submit completed results to [contact@openequine.org](mailto:contact@openequine.org).

---

## Governance

| | |
|---|---|
| **Document Reference** | OE-GL-000-DOD-CQ |
| **Issuing Body** | Open Equine Intelligence Systems — Horse AI |
| **Organisation** | A TechXZone Pvt Ltd Initiative |
| **Version** | 0.12 — May 2026 |
| **Release** | Public domain. Free of cost. Attribution required on adoption or adaptation. |
| **Contact** | [contact@openequine.org](mailto:contact@openequine.org) |
| **Document Licence** | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode) |

---

*Open Equine   |   Open Equine Intelligence Systems — Horse AI   |   A TechXZone Pvt Ltd Initiative   |   openequine.org   |   contact@openequine.org   |   May 2026*
