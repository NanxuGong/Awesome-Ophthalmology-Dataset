# MMRDR

A recent multimodal diabetic retinopathy benchmark spanning CFP, OCT, and UWF imaging.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | MMRDR |
| Modality | Multimodal |
| Submodality | CFP / OCT / UWF |
| Tasks | Classification |
| Disease Focus | Diabetic Retinopathy |
| Input Signals | Color Fundus Image, OCT Image, UWF Image |
| Label Types | DR-related Label |
| Sample Unit | Case |
| Split Unit | - |
| Access | Public |
| Release Year | 2025 |
| Longitudinal | No |
| Multimodal | Yes |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Scale | Three modality-specific DR subsets |
| Cohort | - |
| Sample Breakdown | Separate CFP, OCT, and UWF subsets released with train/test partitions |
| Label Space | DR severity labels for all modalities, lesion multi-labels for CFP/UWF, and DME grades for OCT |
| Annotation Scope | JPEG images with CSV annotations |
| Official / Recommended Split | Train/test partitions are included in the public Figshare release |
| Structural Notes | Multimodal diabetic retinopathy benchmark that spans CFP, OCT, and UWF |

## Why It Matters

MMRDR is one of the few public diabetic retinopathy resources that brings three retinal imaging modalities into one benchmark family, making it attractive for fusion and cross-modality comparison.

## Highlights

- One of the newest public multimodal DR resources with a strong emphasis on evaluation realism.
- More useful than many older multimodal sets if you need all three retinal imaging modalities in one benchmark.

## Caveats

- The public release is recent, so benchmark conventions are still forming.
- Different modalities carry different label granularity, so fusion experiments need explicit protocol choices.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Nature](https://www.nature.com/articles/s41597-026-07005-9) |

## Tags

`diabetic_retinopathy`, `multimodal`, `cfp_oct_uwf`
