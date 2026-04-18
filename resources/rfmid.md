# Retinal Fundus Multi-Disease Image Dataset

A large public fundus benchmark for multi-label retinal disease screening and recognition.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | Retinal Fundus Multi-Disease Image Dataset |
| Modality | Fundus |
| Submodality | Color Fundus |
| Tasks | Multi-label Classification |
| Disease Focus | Multi Disease |
| Input Signals | RGB Fundus Image |
| Label Types | Multilabel Disease Annotations |
| Sample Unit | Image |
| Split Unit | - |
| Access | Public |
| Release Year | 2021 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 3,200 color fundus images |
| Cohort | - |
| Sample Breakdown | Image-level release for multi-label retinal disease recognition |
| Label Space | Normal/abnormal screening plus 45 disease categories |
| Annotation Scope | Image-level multi-label disease annotations |
| Official / Recommended Split | Official train/validation/test split: 1,920 / 640 / 640 |
| Structural Notes | RIADD / ISBI 2021 style screening benchmark with multi-disease labels |

## Why It Matters

RFMiD is one of the clearest public options when you want many disease labels in a single fundus benchmark instead of a one-disease challenge set.

## Highlights

- One of the cleanest public baselines for multi-disease fundus classification.
- Useful when you want a single benchmark to cover many retinal conditions at once.

## Caveats

- Published results are not always directly comparable unless the same official split and label formulation are used.
- Some papers collapse the multi-label setting into simpler tasks, so check protocol details before comparing numbers.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [IEEE DataPort](https://ieee-dataport.org/open-access/retinal-fundus-multi-disease-image-dataset-rfmid) |
| Primary Paper | [Data 2021](https://doi.org/10.3390/data6020014) |

## Tags

`image_level`, `multilabel`, `screening`
