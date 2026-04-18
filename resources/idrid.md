# Indian Diabetic Retinopathy Image Dataset

A classic diabetic retinopathy benchmark that combines grading, lesion masks, and landmark annotations.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | Indian Diabetic Retinopathy Image Dataset |
| Modality | Fundus |
| Submodality | Color Fundus |
| Tasks | Grading, Segmentation |
| Disease Focus | Diabetic Retinopathy, DME |
| Input Signals | RGB Fundus Image |
| Label Types | DR Grade, DME Grade, Lesion Masks, Optic Disc Mask, Fovea Center |
| Sample Unit | Image |
| Split Unit | Image |
| Access | Registration |
| Release Year | 2018 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | Grand Challenge Terms |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 516 color fundus images |
| Cohort | - |
| Sample Breakdown | Grading/localization release: 413 train / 103 test; segmentation subset: 54 train / 27 test |
| Label Space | DR grade, DME grade, four lesion types, optic disc, and fovea center |
| Annotation Scope | Image-level grading, pixel-level lesion masks, and landmark localization |
| Official / Recommended Split | Official challenge-style partitions are widely reused in later work |
| Structural Notes | Single disease-family benchmark that spans grading, segmentation, and localization |

## Why It Matters

IDRiD remains a rare public fundus release that supports both disease-level evaluation and lesion-aware analysis within the same benchmark family.

## Highlights

- A rare public dataset that supports both grading and lesion-level evaluation in the same release.
- Often used as the anchor benchmark for diabetic retinopathy lesion segmentation.

## Caveats

- The lesion segmentation subset is much smaller than the grading release.
- If you mix tasks, keep the grading and lesion protocols clearly separated.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Grand Challenge](https://idrid.grand-challenge.org/) |
| Primary Paper | [Data 2018](https://doi.org/10.3390/data3030025) |

## Tags

`image_level`, `pixel_level`, `grading`, `lesion_segmentation`
