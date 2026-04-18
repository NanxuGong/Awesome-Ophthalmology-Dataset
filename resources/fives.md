# FIVES

A high-resolution fundus vessel segmentation dataset with quality labels and diverse disease background.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | FIVES |
| Modality | Fundus |
| Submodality | Color Fundus |
| Tasks | Segmentation |
| Disease Focus | Vessel Segmentation, Multi Disease Background |
| Input Signals | RGB Fundus Image |
| Label Types | Vessel Mask |
| Sample Unit | Image |
| Split Unit | Image |
| Access | Public |
| Release Year | 2022 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 800 high-resolution fundus images |
| Cohort | 573 subjects |
| Sample Breakdown | Recommended release split: 600 train / 200 test |
| Label Space | Retinal vessel masks with accompanying image-quality scores |
| Annotation Scope | Pixel-wise vessel segmentation and image-quality assessment |
| Official / Recommended Split | Official train/test organization released with the dataset |
| Structural Notes | Multi-disease background with quality-aware vessel segmentation |

## Why It Matters

FIVES is stronger than many older vessel datasets because it pairs detailed vessel masks with image-quality information and modern resolution.

## Highlights

- High-resolution images and provided quality scores make it richer than many older vessel datasets.
- Good fit for studying robustness across disease background and image quality.

## Caveats

- Focused on vessel masks rather than broad clinical label space.
- Many papers follow the provided split, so alternate splits should be reported clearly.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Nature](https://www.nature.com/articles/s41597-022-01564-3) |

## Tags

`pixel_level`, `vessel_segmentation`, `high_resolution`
