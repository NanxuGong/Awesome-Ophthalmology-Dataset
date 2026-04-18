# IDRiD

A classic diabetic retinopathy benchmark that combines grading, lesion masks, and landmark annotations.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | IDRiD |
| Modality | Fundus |
| Submodality | Retinal Fundus |
| Tasks | Segmentation, Grading, Localization |
| Disease Focus | Diabetic Retinopathy |
| Input Signals | RGB Fundus Image, Clinical Data |
| Label Types | Segmentation Labels, Grading Labels, Localization Labels, Landmark Labels |
| Sample Unit | - |
| Split Unit | - |
| Access | Request or Project Page |
| Release Year | 2018 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Reported Scale | 516 color fundus images |
| Reported Cohort | - |
| Reported Breakdown | Grading/localization release: 413 train / 103 test; segmentation subset: 54 train / 27 test |
| Label Space | DR grade, DME grade, four lesion types, optic disc, and fovea center |
| Annotation Scope | Image-level grading, pixel-level lesion masks, and landmark localization |
| Official / Recommended Split | Official challenge-style partitions are widely reused in later work |
| Structural Notes | Single disease-family benchmark that spans grading, segmentation, and localization |

## Why It Matters

IDRiD remains a rare public fundus release that supports both disease-level evaluation and lesion-aware analysis within the same benchmark family.

## Highlights

- A rare public dataset that supports both grading and lesion-level evaluation in the same release.
- Often used as the anchor benchmark for diabetic retinopathy lesion segmentation.

## Official Links

| Resource | Link |
| --- | --- |
| Official Resource | [Grand Challenge](https://idrid.grand-challenge.org/Data/) |
| Implementation / Code | [GitHub](https://github.com/WeiQijie/retinal-lesions?tab=readme-ov-file) |
| Primary Paper | [Data 2018](https://doi.org/10.3390/data3030025) |

## Tags

`diabetic_retinopathy`, `fundus`, `grading`, `localization`, `segmentation`
