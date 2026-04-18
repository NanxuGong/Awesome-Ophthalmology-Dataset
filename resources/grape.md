# GRAPE

A longitudinal multimodal glaucoma dataset that combines fundus images, visual fields, OCT measurements, and follow-up structure.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | GRAPE |
| Modality | OCT |
| Submodality | Retinal OCT |
| Tasks | Classification, Grading, Progression |
| Disease Focus | Glaucoma |
| Input Signals | RGB Fundus Image, OCT Image, Visual Field, Clinical Data |
| Label Types | Grading Labels, Classification Labels, Progression Targets |
| Sample Unit | - |
| Split Unit | - |
| Access | Public |
| Release Year | 2015 |
| Longitudinal | Yes |
| Multimodal | Yes |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Reported Scale | 1,115 longitudinal records |
| Reported Cohort | 144 glaucoma patients / 263 eyes |
| Reported Breakdown | Baseline and follow-up visits collected from 2015 to 2022 |
| Label Space | Visual field progression, fundus images, OCT measurements, and disc-related annotations |
| Annotation Scope | Longitudinal multimodal follow-up data |
| Official / Recommended Split | Eye-level longitudinal split is a strong default because all visits from the same eye should stay together |
| Structural Notes | Progression-oriented glaucoma dataset rather than a single-visit image benchmark |

## Why It Matters

GRAPE stands out because it supports progression-oriented glaucoma research instead of only one-visit detection or grading.

## Highlights

- A strong choice when progression prediction matters more than one-off classification.
- Combines fundus, visual field, and clinical follow-up structure in one public package.

## Official Links

| Resource | Link |
| --- | --- |
| Official Resource | [Nature](https://www.nature.com/articles/s41597-023-02424-4) |
| Implementation / Code | - |
| Primary Paper | [PMC / GRAPE paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10404253/) |

## Tags

`classification`, `glaucoma`, `grading`, `oct`, `progression`
