# GRAPE

A longitudinal multimodal glaucoma dataset that combines fundus images, visual fields, OCT measurements, and follow-up structure.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | GRAPE |
| Modality | Multimodal |
| Submodality | Fundus / VF / Clinical Follow-up |
| Tasks | Progression, Segmentation |
| Disease Focus | Glaucoma |
| Input Signals | Fundus Image, Visual Field, Clinical Information, Follow-up Record |
| Label Types | Visual Field Progression, Disc-related Annotations, Follow-up Metadata |
| Sample Unit | Visit |
| Split Unit | Eye |
| Access | Public |
| Release Year | 2023 |
| Longitudinal | Yes |
| Multimodal | Yes |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 1,115 longitudinal records |
| Cohort | 144 glaucoma patients / 263 eyes |
| Sample Breakdown | Baseline and follow-up visits collected from 2015 to 2022 |
| Label Space | Visual field progression, fundus images, OCT measurements, and disc-related annotations |
| Annotation Scope | Longitudinal multimodal follow-up data |
| Official / Recommended Split | Eye-level longitudinal split is a strong default because all visits from the same eye should stay together |
| Structural Notes | Progression-oriented glaucoma dataset rather than a single-visit image benchmark |

## Why It Matters

GRAPE stands out because it supports progression-oriented glaucoma research instead of only one-visit detection or grading.

## Highlights

- A strong choice when progression prediction matters more than one-off classification.
- Combines fundus, visual field, and clinical follow-up structure in one public package.

## Caveats

- Temporal leakage is easy to introduce if visits are split incorrectly.
- Evaluation protocols should state the prediction horizon and whether baseline-only or full-history inputs are used.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Springer Nature Figshare](https://springernature.figshare.com/collections/GRAPE_A_multi-modal_glaucoma_dataset_of_follow-up_visual_field_and_fundus_images_for_glaucoma_management/6406319) |
| Primary Paper | [PMC / GRAPE paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10404253/) |

## Tags

`longitudinal`, `glaucoma`, `visit_level`, `paired_multimodal`, `vf_estimation`
