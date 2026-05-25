<p align="center">
  <img src="../assets/logo.png" alt="Open Equine Intelligence Systems" width="140"/>
</p>

<h1 align="center">OE-GL-000 Definitions Framework</h1>
<h3 align="center">Intelligent and Biomimetic Systems in Equine Stable Environments</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Reference-OE--GL--000-green" alt="OE-GL-000"/>
  <img src="https://img.shields.io/badge/Status-Published-brightgreen" alt="Published"/>
  <img src="https://img.shields.io/badge/Version-1.2-blue" alt="Version 1.2"/>
  <img src="https://img.shields.io/badge/License-AGPLv3%20%2F%20CC--BY--SA%204.0-green.svg" alt="AGPLv3 / CC-BY-SA 4.0"/>
</p>

<p align="center">
  Open Equine Intelligence Systems &nbsp;|&nbsp; openequine.org &nbsp;|&nbsp; May 2026
</p>

---

## About This Document

This document establishes the foundational definitions for all categories of intelligent, autonomous, and biomimetic machines and systems addressed under the Open Equine Intelligence Systems guidelines framework.

Each category defined here has a dedicated guidelines document within this repository. **OE-GL-000 is the entry point for the entire framework.** All other documents reference back to it.

Classification of any device or system under this framework is determined by its functional characteristics and environmental interaction profile — not by its commercial designation, intended purpose, or the terminology used by its manufacturer.

## Scope of Definitions

The device categories and subcategories defined in this document represent the current known landscape of intelligent, autonomous, and biomimetic systems relevant to equine stable environments. These definitions are followed but not limited to. New device classifications, form factors, and system architectures will emerge as technology evolves. Any device or system not explicitly defined here is to be assessed against the existing category definitions for the closest applicable classification. Where no existing classification applies, the matter is to be logged as a contribution request for inclusion in a future release of this document.

## Applicability to Other Domestic Animals

The definitions, classifications, and guidelines contained in this framework are developed in the context of equine stable environments. However, the underlying principles — relating to the sensory response characteristics of domestic animals, the risk profile of confined environments, and the behavioural response to biomimetic and autonomous machines — are applicable across domestic animal environments broadly. Organisations and institutions developing safety guidelines for other domestic animals, including bovine, ovine, canine, and other livestock or companion animal environments, are encouraged to reference and adapt this framework. Where adaptations are made, attribution to Open Equine Intelligence Systems is required under the terms of the CC-BY-SA 4.0 Licence.

---

## Table of Contents

0. [Veterinary Authority](#veterinary-authority)
1. [Humanoid Machine](#1-humanoid-machine)
2. [Biomimetic Robotic System (BRS)](#2-biomimetic-robotic-system-brs)
3. [Aerial Systems](#3-aerial-systems)
4. [Ground Autonomous Machines](#4-ground-autonomous-machines)
5. [Wearable and Attached Sensor Systems](#5-wearable-and-attached-sensor-systems)
6. [Stationary Intelligent Systems](#6-stationary-intelligent-systems)
7. [Algorithmic and Software Systems](#7-algorithmic-and-software-systems)
8. [Repository Map](#8-repository-map)
9. [Governance](#9-governance)

---


## Veterinary Authority

Veterinary professionals hold exclusive authority over all health, medication, and emergency decisions within the equine stable environment. No AI tool, robotic system, biomimetic machine, or algorithmic output constitutes a veterinary decision. All outputs from any system defined in this framework that relate to horse health, medication, or emergency response must be reviewed and approved by a qualified veterinary professional before any action is taken. This authority is non-delegable and cannot be overridden by any technology system defined within this framework.

---

## 1. Humanoid Machine

### Definition

A machine whose physical form and/or locomotion recognisably resembles human anatomy in any part or in whole. Achieves locomotion on two legs. Capable of general-purpose physical task execution across unstructured environments.

Classification as a Humanoid is determined by physical form and locomotion pattern. Accessories, attachments, tools, or add-on modules carried or worn by a Humanoid machine do not alter its classification. A Humanoid carrying a tool is a Humanoid. A Humanoid fitted with additional sensors or limb extensions is a Humanoid.

### Scope Note

> A Humanoid machine is also classified as a Biomimetic Robotic System under Section 2 of this document. It is additionally classified independently here due to the specific and elevated risk profile that its human-form silhouette presents in equine environments. Both classifications apply simultaneously.

### Examples Currently in Deployment or Active Development

Boston Dynamics Atlas, Figure 02, Tesla Optimus, Agility Robotics Digit, Unitree H1, Apptronik Apollo, Sanctuary AI Phoenix.

### Dedicated Guidelines Document

[OE-GL-001 — Safety Guidelines for Humanoid Machines in Equine Stables](../guidelines/OE-GL-001_Humanoid-Machines.md)

---

## 2. Biomimetic Robotic System (BRS)

### Definition

Any autonomous or semi-autonomous machine whose physical form, locomotion pattern, or movement profile replicates or approximates that of a living biological organism.

Classification as a BRS is determined by biological resemblance and movement characteristics, not by intended function or commercial designation.

- A wheeled cleaning unit is **not** a BRS
- A robotic dog **is** a BRS
- A humanoid machine **is** a BRS

### Subcategories

#### BRS-H — Humanoid Biomimetic Systems
Machines replicating human anatomical form and bipedal locomotion. Classified independently under Section 1. All BRS guidelines apply in addition to Humanoid-specific guidelines.

#### BRS-Q — Quadrupedal Biomimetic Systems
Machines replicating four-limbed animal locomotion. Includes robotic dogs, robotic horses, and any quadrupedal machine regardless of the biological organism its form or movement is derived from or resembles.

> **Critical Note:** A robotic horse deployed in an active stable environment presents a specific and serious safety concern. Horses in proximity to a machine replicating equine form and movement may exhibit unpredictable responses within the enclosed space. No robotic horse or equine-form BRS is to be deployed in an active horse-occupied stable zone under any circumstances.

**Examples:** Boston Dynamics Spot, Unitree Go2, ANYbotics ANYmal.

#### BRS-B — Bipedal Non-Humanoid Biomimetic Systems
Machines with two-limbed locomotion whose form replicates a biological organism other than a human. Includes any bipedal machine whose biological template is a bird, primate, or other two-limbed animal.

#### BRS-A — Avian and Small Biomimetic Systems
Machines replicating the form or movement of birds, insects, or small animals. Includes robotic birds, insect-scale drones with biological movement profiles, and any small autonomous system whose movement approximates that of a living creature a horse would encounter in its natural environment.

### Dedicated Guidelines Document

[OE-GL-002 — Safety Guidelines for Biomimetic Robotic Systems in Equine Stables](../guidelines/OE-GL-002_Biomimetic-Robotic-Systems.md) *(In Development)*

---

## 3. Aerial Systems

### Definition

Any autonomous or remotely operated machine capable of sustained flight within or proximate to a stable environment. Includes fixed-wing UAVs, rotary-wing drones, and hybrid aerial platforms.

Aerial systems whose form or flight pattern replicates a biological organism are additionally classified as BRS-A under Section 2.

### Subcategories

#### AS-S — Surveillance and Monitoring
Aerial systems deployed for observation, data collection, and environmental monitoring within or proximate to stable environments.

#### AS-D — Delivery and Transport
Aerial systems deployed for physical payload delivery within or proximate to stable environments.

#### AS-A — Autonomous Free-Flight
Aerial systems operating without continuous human remote control input. Subject to the highest level of restriction within this category.

### Dedicated Guidelines Document

[OE-GL-003 — Safety Guidelines for Aerial Systems in Equine Stables](../guidelines/OE-GL-003_Aerial-Systems.md) *(In Development)*

---

## 4. Ground Autonomous Machines

### Definition

Autonomous or semi-autonomous wheeled, tracked, or legged machines that do not replicate biological form. Designed for specific task execution in defined operational zones within stable environments.

### Subcategories

#### GAM-F — Fixed Task Machines
Stationary or near-stationary machines executing a single defined function. Includes automated feeders, water management systems, and waste processing units.

#### GAM-M — Mobile Task Machines
Machines with autonomous navigation capability operating on defined paths or within defined zones. Includes stall cleaning robots, equipment transport units, and inspection vehicles.

#### GAM-I — Integrated Machines
Mobile or fixed machines connected to stable management software, AI monitoring systems, or external networks. Subject to algorithmic system guidelines in addition to ground machine guidelines.

### Dedicated Guidelines Document

[OE-GL-004 — Safety Guidelines for Ground Autonomous Machines in Equine Stables](../guidelines/OE-GL-004_Ground-Autonomous-Machines.md) *(In Development)*

---

## 5. Wearable and Attached Sensor Systems

### Definition

Devices physically attached to horses, handlers, or stable infrastructure for data collection, monitoring, or communication purposes. Have no autonomous locomotion.

### Subcategories

#### WSS-E — Equine Attached
Devices attached directly to horses. Includes GPS trackers, biometric monitors, gait analysis sensors, and health monitoring devices.

#### WSS-H — Handler Attached
Devices worn or carried by stable personnel during active stable operations.

#### WSS-I — Infrastructure Attached
Sensor systems fixed to stable structures, gates, stall walls, or equipment.

### Dedicated Guidelines Document

[OE-GL-005 — Safety Guidelines for Wearable and Attached Sensor Systems in Equine Stables](../guidelines/OE-GL-005_Wearable-Attached-Sensor-Systems.md) *(In Development)*

---

## 6. Stationary Intelligent Systems

### Definition

Fixed machines or devices incorporating AI processing capability with no autonomous locomotion. Operate from a fixed position within the stable environment.

Includes AI-powered cameras, environmental monitoring systems, automated feeding systems with AI integration, and any fixed device capable of autonomous decision output.

### Dedicated Guidelines Document

[OE-GL-006 — Safety Guidelines for Stationary Intelligent Systems in Equine Stables](../guidelines/OE-GL-006_Stationary-Intelligent-Systems.md) *(In Development)*

---

## 7. Algorithmic and Software Systems

### Definition

Software-only systems with no physical machine presence. Operate on data inputs to produce outputs that inform or influence stable management decisions.

Includes health monitoring platforms, feed optimisation systems, training analytics tools, predictive diagnostics, stable management software with AI integration, and any software system whose outputs are used as inputs to stable management decisions.

Algorithmic systems carry no physical risk. Their risk profile is within the domain of decision influence — the degree to which their outputs affect decisions made by human stable management.

### Dedicated Guidelines Document

[OE-GL-007 — Safety Guidelines for Algorithmic and Software Systems in Equine Stables](../guidelines/OE-GL-007_Algorithmic-Software-Systems.md) *(In Development)*

---

## 8. Repository Map

All Open Equine Intelligence Systems guidelines documents are held at [openequine.org](https://openequine.org) and in this repository. Each document carries its OE-GL reference number. This definitions document is the entry point. All other documents reference back to it.

| Reference | Category | Status |
|---|---|---|
| **OE-GL-000** | **Definitions Framework** | ✅ **Published** |
| OE-GL-001 | Humanoid Machines | ✅ Published |
| OE-GL-002 | Biomimetic Robotic Systems | 🔄 In Development |
| OE-GL-003 | Aerial Systems | 🔄 In Development |
| OE-GL-004 | Ground Autonomous Machines | 🔄 In Development |
| OE-GL-005 | Wearable and Attached Sensor Systems | 🔄 In Development |
| OE-GL-006 | Stationary Intelligent Systems | 🔄 In Development |
| OE-GL-007 | Algorithmic and Software Systems | 🔄 In Development |

---

## 9. Governance

| | |
|---|---|
| **Issuing Body** | Open Equine Intelligence Systems |
| **Reference** | OE-GL-000 |
| **Version** | 1.2 — May 2026 |
| **Release** | Public domain. Free of cost. Attribution required on adoption or adaptation. |
| **Liability** | Remains with stable management at all times. |
| **Review Cycle** | This is a living framework. Release cycle and review phases are announced on openequine.org. |
| **Contributions** | [openequine.org](https://openequine.org) |
| **Licence** | Code: AGPLv3 \| Documents: CC-BY-SA 4.0 |

---

<p align="center">
  <img src="../assets/logo.png" alt="Open Equine Intelligence Systems" width="80"/>
  <br/>
  <strong>Open Equine Intelligence Systems</strong><br/>
  openequine.org &nbsp;|&nbsp; OE-GL-000 &nbsp;|&nbsp; Version 1.2 &nbsp;|&nbsp; May 2026<br/>
  <em>Technology serves the stable. It does not govern it.</em>
</p>
