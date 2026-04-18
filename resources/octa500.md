# OCTA-500

A large paired OCT and OCTA resource with volumes, projection maps, disease metadata, and segmentation labels.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | OCTA-500 |
| Modality | OCTA |
| Submodality | Retinal OCTA |
| Tasks | Segmentation, Classification |
| Disease Focus | Multi Disease |
| Input Signals | OCT Volume, OCTA Volume, Projection Image |
| Label Types | Disease Metadata, FAZ Annotation, Vessel Annotation, Artery Vein Annotation, Retinal Layer Annotation |
| Sample Unit | Eye |
| Split Unit | Subject |
| Access | Terms Based |
| Release Year | 2020 |
| Longitudinal | No |
| Multimodal | Yes |
| License / Terms | Project-specific Terms |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 500 OCTA subjects |
| Cohort | 500 subjects |
| Sample Breakdown | 300 scans with 6 mm field of view and 200 scans with 3 mm field of view |
| Label Space | Age, gender, eye, disease, and seven segmentation label families |
| Annotation Scope | OCT volumes, OCTA volumes, projection maps, and segmentation labels |
| Official / Recommended Split | No single canonical train/test split; subject-level splits are the safest choice |
| Structural Notes | Paired OCT and OCTA release with 3 mm and 6 mm acquisitions |

## Why It Matters

OCTA-500 is one of the most information-dense public OCTA datasets, which makes it a cornerstone benchmark for segmentation, representation learning, and multimodal retinal analysis.

## Highlights

- One of the most information-dense public OCTA resources because it combines volumes, projections, and multiple annotation types.
- Useful for both segmentation and representation-learning style multimodal OCT/OCTA work.

## Caveats

- Studies vary widely in how they subset 3 mm and 6 mm scans, so protocols must be documented clearly.
- The release supports several reasonable experimental setups, so papers should state exactly which assets and labels are used.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [IEEE DataPort](https://ieee-dataport.org/open-access/octa-500) |
| Primary Paper | [arXiv 2020](https://arxiv.org/abs/2012.07261) |

## Tags

`octa`, `pixel_level`, `subject_split`
