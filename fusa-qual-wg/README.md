# LLVM Qualification Working Group

This directory contains documentation and working materials for the LLVM Qualification Working Group.

For more information about the group, see the [LLVM Qualification Working Group page](https://llvm.org/docs/QualGroup.html).

## Target Audience

This document is for current and prospective participants in the LLVM Qualification Working Group, as well as LLVM contributors and downstream users who want to understand the group’s activities and working materials.

## Motivation

Automotive developers use compilers to create code for electronic systems. If this code, especially for control systems, is faulty, the results can be dangerous. To prevent this, ISO 26262 Part 8, Clause 11 requires that tools like compilers used in component development must be qualified.

### Kick-off talk

- **Video:** [2025 AsiaLLVM - LLVM in the Automotive Industry: Bringing Functional Safety to Open Source](https://www.youtube.com/watch?v=wAQ1XBjXfog)
- **Presentation Materials:** [urribarri-automotive.pdf](https://llvm.org/devmtg/2025-06/slides/technical-talk/urribarri-automotive.pdf)

### Presentations

TODO: We need to add materials that help others understand our activities.

### Papers

TODO: We need to add materials that help others understand our activities.

## Activities & Initiatives

### 1. Confidence in the use of software tools process

This process ensures any software tool used during the development of a safety-critical system does not introduce errors or fail to detect errors in a way that could compromise the safety of the final product. The process establishes a systematic way to evaluate, classify, and qualify these tools based on the potential impact of their failure on the final system's safety.

TODO: We need to add more detail 

### 2. Software Library Qualification Process

TODO: Petter to provide a brief description

- [Draft RFC] libc++ Conformance Test Traceability - LLVM Qualification WG

## Projects and Safety Standard Mapping

TODO

## Repository Structure

This directory is organized into the following areas. 

```
fusa-qual-wg/
├── README.md                    # this file
├── meetings/                    # meeting materials, agendas, and minutes
│   ├── materials/               # meeting slide content
│   ├── minutes/                 # published agendas and minutes
│   └── img/                     # images referenced by the materials
├── tools/                       # confidence in the use of software tools
│   ├── templates/               # process step templates
│   └── workflows/               # qualification workflows
├── quality/                     # LLVM quality
│   ├── defects-reports.md       # defect reports
│   ├── process/
│   │   ├── assessment/          # assessment of the development process
│   │   └── defects-prediction/  # defects prediction
│   └── status-reports/          # status reports
├── libs/                        # libraries qualification
└── safety-model/                # LLVM functional safety model
```
