# MultiEYE

A multimodal benchmark that uses fundus and OCT jointly during training while targeting fundus recognition at inference.

## Dataset Information

| Field | Value |
| --- | --- |
| Official Name | MultiEYE |
| Modality | OCT |
| Submodality | Retinal OCT |
| Tasks | Classification, Recognition |
| Disease Focus | - |
| Input Signals | RGB Fundus Image, OCT Image, Clinical Data |
| Label Types | Classification Labels |
| Sample Unit | - |
| Split Unit | - |
| Access | Public |
| Release Year | 2024 |
| Longitudinal | No |
| Multimodal | Yes |
| License / Terms | - |

## Statistics

| Field | Value |
| --- | --- |
| Reported Scale | Large assembled multimodal classification release |
| Reported Cohort | - |
| Reported Breakdown | Built from 12 public fundus datasets, 4 OCT datasets, and private hospital data |
| Label Space | Nine disease classes in the released training code |
| Annotation Scope | Classification labels with unpaired fundus and OCT training support |
| Official / Recommended Split | Train with multimodal data, evaluate on fundus-only recognition in the paper setting |
| Structural Notes | Designed for OCT-enhanced recognition from fundus images rather than fully paired multimodal testing |

## Why It Matters

MultiEYE is interesting because it matches a realistic deployment story: OCT can help model development even when only fundus images are available at test time.

## Highlights

- Conceptually interesting because it targets fundus-only testing while still learning from OCT during training.
- Useful if you care about realistic clinical deployment where OCT may not be available at inference time.

## Official Links

| Resource | Link |
| --- | --- |
| Official Resource | [GitHub](https://github.com/xmed-lab/MultiEYE) |
| Implementation / Code | - |
| Primary Paper | [arXiv / TMI 2024](https://arxiv.org/abs/2412.09402) |

## Tags

`additional_curated`, `classification`, `oct`, `recognition`
