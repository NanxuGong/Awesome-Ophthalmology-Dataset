# PALM

A challenge-style fundus benchmark for pathological myopia with disease, lesion, and anatomy annotations.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | PALM |
| Modality | Fundus |
| Submodality | Color Fundus |
| Tasks | Classification, Segmentation |
| Disease Focus | Pathological Myopia |
| Input Signals | RGB Fundus Image |
| Label Types | Pathologic Myopia Label, Segmentation Annotations |
| Sample Unit | Image |
| Split Unit | Image |
| Access | Registration |
| Release Year | 2019 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | Grand Challenge Terms |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 1,200 color fundus images |
| Cohort | - |
| Sample Breakdown | Official challenge packaging: 400 train / 400 validation / 400 test |
| Label Space | Pathologic myopia recognition, optic disc, fovea, and lesion annotations |
| Annotation Scope | Classification, lesion segmentation, and localization |
| Official / Recommended Split | Challenge split is the de facto reference protocol |
| Structural Notes | Pathologic myopia challenge release with anatomy and lesion annotations |

## Why It Matters

PALM is a key public reference for pathological myopia because it supports both recognition and more interpretable lesion-aware evaluation.

## Highlights

- One of the most important public references for pathological myopia on fundus images.
- Useful when you need both disease recognition and interpretable lesion/anatomy targets.

## Caveats

- Challenge packaging can blur the line between classification and segmentation protocols if not documented carefully.
- Many studies reuse only part of the annotations, so label scope should be stated explicitly.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Grand Challenge](https://palm.grand-challenge.org/) |
| Primary Paper | [Scientific Data 2024](https://www.nature.com/articles/s41597-024-02911-2) |

## Tags

`myopia`, `challenge_dataset`, `image_level`
