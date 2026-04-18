# PAPILA

A glaucoma-focused fundus dataset with bilateral eye pairing, optic nerve annotations, and clinical context.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | PAPILA |
| Modality | Fundus |
| Submodality | Retinal Fundus |
| Tasks | Segmentation, Classification |
| Disease Focus | Glaucoma |
| Input Signals | RGB Fundus Image, Clinical Data, Text |
| Label Types | Segmentation Labels, Classification Labels, Landmark Labels |
| Sample Unit | - |
| Split Unit | - |
| Access | Public |
| Release Year | 2022 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Reported Scale | 488 color fundus images |
| Reported Cohort | 244 patients / 488 eyes |
| Reported Breakdown | Both eyes are available for every patient, paired with clinical information |
| Label Space | Glaucoma label plus optic disc and optic cup segmentations |
| Annotation Scope | Classification labels, segmentation masks, and clinical metadata |
| Official / Recommended Split | Patient-level split is strongly preferred to avoid left/right eye leakage |
| Structural Notes | Bilateral glaucoma dataset with explicit pairing across eyes |

## Why It Matters

PAPILA is especially valuable when patient-level splitting matters, because both eyes are available and leakage can otherwise inflate results.

## Highlights

- A strong glaucoma benchmark when patient-level leakage matters.
- Useful for work that combines fundus appearance with optic nerve head segmentation.

## Official Links

| Resource | Link |
| --- | --- |
| Official Resource | [Nature](https://www.nature.com/articles/s41597-022-01388-1) |
| Implementation / Code | - |
| Primary Paper | - |

## Tags

`classification`, `fundus`, `glaucoma`, `segmentation`
