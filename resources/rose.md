# ROSE

A compact OCTA segmentation benchmark centered on retinal vessel analysis.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | ROSE |
| Modality | OCTA |
| Submodality | Retinal OCTA Projection |
| Tasks | Segmentation |
| Disease Focus | Vessel Segmentation, FAZ Segmentation |
| Input Signals | OCTA Projection Image |
| Label Types | Vessel Mask, FAZ Mask |
| Sample Unit | Image |
| Split Unit | Image |
| Access | Public |
| Release Year | 2024 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | Zenodo Terms |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 229 OCTA images |
| Cohort | - |
| Sample Breakdown | ROSE-1 and ROSE-2 subsets are commonly used together |
| Label Space | Retinal vessel segmentation targets; related OCTA studies often pair vessel and FAZ evaluation |
| Annotation Scope | Centerline-level or pixel-level vessel annotations depending on subset |
| Official / Recommended Split | - |
| Structural Notes | Dedicated OCTA segmentation benchmark with lighter scale than OCTA-500 |

## Why It Matters

ROSE is a practical starting point for OCTA method development when you want something lighter than OCTA-500 but still established in the literature.

## Highlights

- A compact OCTA benchmark that is easier to start with than OCTA-500.
- Often used to test vessel-focused OCTA segmentation methods.

## Caveats

- Subset conventions differ across papers, so always report whether ROSE-1, ROSE-2, or both were used.
- Small scale makes variance across splits and augmentations more noticeable.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Zenodo](https://zenodo.org/records/12775880) |
| Primary Paper | [arXiv 2020](https://arxiv.org/abs/2007.05201) |

## Tags

`octa`, `pixel_level`, `vessel_segmentation`, `faz_segmentation`
