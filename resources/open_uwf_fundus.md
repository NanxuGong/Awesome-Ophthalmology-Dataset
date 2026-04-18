# Open Ultrawidefield Fundus Dataset

A dedicated ultrawidefield fundus dataset with diagnosis labels, demographics, and image-quality assessment.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | Open Ultrawidefield Fundus Dataset |
| Modality | UWF |
| Submodality | Ultrawidefield Fundus |
| Tasks | Classification, Quality Assessment |
| Disease Focus | Multi Disease |
| Input Signals | UWF Fundus Image |
| Label Types | Disease Label, Image Quality Label |
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
| Scale | 700 ultrawidefield fundus images |
| Cohort | 602 patients / 689 eyes |
| Sample Breakdown | Seven groups with 100 images each: six diseases plus healthy controls |
| Label Space | Disease diagnosis, demographics, and five image-quality dimensions |
| Annotation Scope | Diagnosis labels, demographic metadata, and image-quality assessment |
| Official / Recommended Split | No single canonical benchmark split is enforced by the paper |
| Structural Notes | 200-degree UWF images collected with Optos 200Tx |

## Why It Matters

This dataset matters because public UWF resources are still scarce, and it treats ultrawidefield imaging as a distinct modality rather than a wider fundus proxy.

## Highlights

- A rare public UWF release that includes both diagnosis and clinically grounded quality labels.
- Useful for research that treats UWF as its own modality rather than a wider version of standard fundus.

## Caveats

- UWF image geometry differs substantially from conventional fundus data.
- If you benchmark IQA and disease recognition together, report both tasks separately.

## Resource Links

| Resource | Link |
| --- | --- |
| Official Resource | [Nature](https://www.nature.com/articles/s41597-024-04113-2) |

## Tags

`uwf`, `screening`, `quality_assessment`
