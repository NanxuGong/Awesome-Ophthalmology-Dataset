# PAPILA

A glaucoma-focused fundus dataset with bilateral eye pairing, optic nerve annotations, and clinical context.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | PAPILA |
| Modality | Fundus |
| Submodality | Color Fundus |
| Tasks | Classification, Segmentation |
| Disease Focus | Glaucoma |
| Input Signals | RGB Fundus Image, Clinical Data |
| Label Types | Glaucoma Label, Optic Disc Mask, Optic Cup Mask |
| Sample Unit | Eye |
| Split Unit | Patient |
| Access | Public |
| Release Year | 2021 |
| Longitudinal | No |
| Multimodal | Yes |
| License / Terms | Figshare Terms |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 488 color fundus images |
| Cohort | 244 patients / 488 eyes |
| Sample Breakdown | Both eyes are available for every patient, paired with clinical information |
| Label Space | Glaucoma label plus optic disc and optic cup segmentations |
| Annotation Scope | Classification labels, segmentation masks, and clinical metadata |
| Official / Recommended Split | Patient-level split is strongly preferred to avoid left/right eye leakage |
| Structural Notes | Bilateral glaucoma dataset with explicit pairing across eyes |

## Why It Matters

PAPILA is especially valuable when patient-level splitting matters, because both eyes are available and leakage can otherwise inflate results.

## Highlights

- A strong glaucoma benchmark when patient-level leakage matters.
- Useful for work that combines fundus appearance with optic nerve head segmentation.

## Caveats

- A naive image-level split can leak patient identity because both eyes are included.
- The dataset is single-center, so external generalization should not be assumed.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Nature](https://www.nature.com/articles/s41597-022-01388-1) |

## Tags

`eye_level`, `pixel_level`, `glaucoma`, `paired_clinical`
