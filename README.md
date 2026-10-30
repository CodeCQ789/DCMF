# Disease-Centered Multimodal Fusion with Observation-Selective Grounding Distillation for Chest X-ray Report Generation

## Overview

This is the official repository for our **Radiology Report Generation (RRG)** method, which aims to improve disease-related visual grounding and multimodal evidence fusion for chest X-ray report generation.

Our framework consists of three main components:

- **Disease-Conditioned Visual Evidence (DCVE):** Learns disease-specific visual representations using Observation-Selective Grounding Distillation (OSGD) to selectively transfer spatial knowledge from a pretrained BioViL-T teacher.
- **Grounded Fusion Planner (GFP):** Adaptively integrates disease-related visual evidence into the language generation process through controlled evidence injection.
- **Discrepancy-Guided Evidence Augmentation (DGEA):** Identifies potential omissions and inconsistencies in generated reports and retrieves relevant supporting evidence for report refinement.

## Datasets

We conduct experiments on the following publicly available research datasets:

- **MIMIC-CXR:** Radiology report generation.
- **IU X-Ray:** Zero-shot report generation.
- **MS-CXR:** Disease-related spatial grounding evaluation.

Please refer to the official dataset repositories for access instructions and usage requirements.

## Code Release

The code is currently being organized and will be made available here soon.
