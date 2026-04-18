# OCTDL

A newer OCT dataset with broader disease coverage and richer pathology metadata than older four-class baselines.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | OCTDL |
| Modality | OCT |
| Submodality | Retinal OCT |
| Tasks | Classification |
| Disease Focus | AMD, DME, ERM, RAO, RVO, VID |
| Input Signals | OCT Image |
| Label Types | Disease Class |
| Sample Unit | Image |
| Split Unit | - |
| Access | Public |
| Release Year | 2024 |
| Longitudinal | No |
| Multimodal | No |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Scale | 2,064 OCT images |
| Cohort | 821 patients |
| Sample Breakdown | Folder-based JPG release with accompanying pathology CSV |
| Label Space | Six disease groups with extra pathology-level metadata |
| Annotation Scope | Image-level disease labels plus pathology annotations |
| Official / Recommended Split | - |
| Structural Notes | Macular raster scans organized by disease label on Mendeley |

## Why It Matters

OCTDL is useful when OCT2017 feels too narrow and you want a more recent classification benchmark with more clinically varied categories.

## Highlights

- A more recent and clinically broader alternative to the classic four-class OCT baselines.
- The additional pathology CSV gives you more room than a single coarse disease label.

## Caveats

- There is no single dominant public split protocol yet.
- If you compare against OCT2017-style baselines, document how categories are aligned.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Mendeley Data](https://data.mendeley.com/datasets/sncdhf53xc/1) |
| Primary Paper | [Scientific Data 2024](https://www.nature.com/articles/s41597-024-03182-7) |

## Tags

`oct_classification`, `multi_class`, `recent_dataset`
