# Awesome Ophthalmology Dataset

<p align="center"><strong>Awesome Ophthalmology Datasets</strong></p>

<p align="center">
  Fundus · OCT · OCTA · UWF · Multimodal
</p>

<p align="center">
  <a href="#fundus">Fundus</a> ·
  <a href="#oct">OCT</a> ·
  <a href="#octa">OCTA</a> ·
  <a href="#uwf">UWF</a> ·
  <a href="#multimodal">Multimodal</a> ·
  <a href="#field-guide">Field Guide</a>
</p>

This repository is built for fast browsing: start from a modality, scan the shortlist, then jump into `resources/*.md` for dataset information, statistics, highlights, and caveats.

> **Last updated:** 2026-04-18

## • Collection Pulse

| **14** | **5** | **14** | **2026-04-18** |
| --- | --- | --- | --- |
| Total datasets | Modality lanes | Resource pages | Current front page |

## • Browse Lanes

| Lane | Focus | Count | Jump |
| --- | --- | --- | --- |
| **Fundus** | Color fundus datasets for screening, grading, anatomy, and disease recognition. | 5 | [Open](#fundus) |
| **OCT** | Retinal OCT benchmarks focused on structural classification tasks. | 2 | [Open](#oct) |
| **OCTA** | OCTA datasets with vessel, FAZ, and layer-aware annotation signals. | 2 | [Open](#octa) |
| **UWF** | Ultra-widefield resources with their own geometry and quality considerations. | 1 | [Open](#uwf) |
| **Multimodal** | Datasets that combine fundus, OCT, UWF, clinical signals, or longitudinal follow-up. | 4 | [Open](#multimodal) |

## • Spotlight Tracks

- `Glaucoma` : [PAPILA](resources/papila.md), [GRAPE](resources/grape.md), [Harvard-GDP](resources/harvard_gdp.md)
- `Diabetic Retinopathy` : [Indian Diabetic Retinopathy Image Dataset](resources/idrid.md), [MMRDR](resources/mmrdr.md), [Open Ultrawidefield Fundus Dataset](resources/open_uwf_fundus.md)
- `Vessel + FAZ Segmentation` : [FIVES](resources/fives.md), [ROSE](resources/rose.md), [OCTA-500](resources/octa500.md)
- `Multimodal Retina` : [MultiEYE](resources/multieye.md), [GRAPE](resources/grape.md), [MMRDR](resources/mmrdr.md)

---

<a id="fundus"></a>
## • Fundus

Color fundus datasets for screening, grading, anatomy, and disease recognition.

| Dataset | Snapshot | Best for | Year | Official | Profile |
| --- | --- | --- | --- | --- | --- |
| FIVES | A high-resolution fundus vessel segmentation dataset with quality labels and diverse disease background. | Segmentation \| Vessel Segmentation, Multi Disease Background | 2022 | [Scientific Data](https://www.nature.com/articles/s41597-022-01564-3) | [Open](resources/fives.md) |
| Indian Diabetic Retinopathy Image Dataset | A key diabetic retinopathy benchmark that spans both grading labels and lesion/anatomy annotations. | Grading, Segmentation \| Diabetic Retinopathy, DME | 2018 | [Grand Challenge](https://idrid.grand-challenge.org/) | [Open](resources/idrid.md) |
| PALM | A challenge-style pathological myopia benchmark spanning both disease labels and segmentation annotations. | Classification, Segmentation \| Pathological Myopia | 2019 | [Grand Challenge](https://palm.grand-challenge.org/) | [Open](resources/palm.md) |
| PAPILA | A glaucoma-focused fundus dataset with bilateral eye relationships and paired clinical information. | Classification, Segmentation \| Glaucoma | 2021 | [Scientific Data](https://www.nature.com/articles/s41597-022-01388-1) | [Open](resources/papila.md) |
| Retinal Fundus Multi-Disease Image Dataset | A large public fundus benchmark for multi-label retinal disease screening and recognition. | Multi-label Classification \| Multi Disease | 2021 | [IEEE DataPort](https://ieee-dataport.org/open-access/retinal-fundus-multi-disease-image-dataset-rfmid) | [Open](resources/rfmid.md) |

<a id="oct"></a>
## • OCT

Retinal OCT benchmarks focused on structural classification tasks.

| Dataset | Snapshot | Best for | Year | Official | Profile |
| --- | --- | --- | --- | --- | --- |
| OCT2017 | A classic retinal OCT baseline with a widely used four-class classification setup. | Classification \| CNV, DME, Drusen, Normal | 2018 | [Mendeley Data](https://data.mendeley.com/datasets/rscbjbr9sj/1) | [Open](resources/oct2017.md) |
| OCTDL | A newer OCT classification entry with broader disease coverage than OCT2017. | Classification \| AMD, DME, ERM, RAO, RVO, VID | 2024 | [Mendeley Data](https://data.mendeley.com/datasets/sncdhf53xc/1) | [Open](resources/octdl.md) |

<a id="octa"></a>
## • OCTA

OCTA datasets with vessel, FAZ, and layer-aware annotation signals.

| Dataset | Snapshot | Best for | Year | Official | Profile |
| --- | --- | --- | --- | --- | --- |
| OCTA-500 | A large paired OCT and OCTA resource with volumes, projection maps, disease metadata, and segmentation labels. | Segmentation, Classification \| Multi Disease | 2020 | [IEEE DataPort](https://ieee-dataport.org/open-access/octa-500) | [Open](resources/octa500.md) |
| ROSE | A compact public OCTA segmentation dataset useful for vessel and FAZ evaluation. | Segmentation \| Vessel Segmentation, FAZ Segmentation | 2024 | [Zenodo](https://zenodo.org/records/12775880) | [Open](resources/rose.md) |

<a id="uwf"></a>
## • UWF

Ultra-widefield imaging resources with their own image geometry and quality considerations.

| Dataset | Snapshot | Best for | Year | Official | Profile |
| --- | --- | --- | --- | --- | --- |
| Open Ultrawidefield Fundus Dataset | A dedicated ultrawidefield entry kept separate from standard fundus datasets because the image geometry and distribution shift matter. | Classification, Quality Assessment \| Multi Disease | 2024 | [Scientific Data](https://www.nature.com/articles/s41597-024-04113-2) | [Open](resources/open_uwf_fundus.md) |

<a id="multimodal"></a>
## • Multimodal

Datasets that combine fundus, OCT, UWF, clinical signals, or longitudinal follow-up.

| Dataset | Snapshot | Best for | Year | Official | Profile |
| --- | --- | --- | --- | --- | --- |
| GRAPE | A longitudinal multimodal glaucoma dataset that combines fundus images, visual fields, OCT measurements, and follow-up structure. | Progression, Segmentation \| Glaucoma | 2023 | [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC10404253/) | [Open](resources/grape.md) |
| Harvard-GDP | A longitudinal multimodal glaucoma dataset centered on OCT for detection and progression studies. | Classification, Progression \| Glaucoma | 2024 | [Project Page](https://ophai.hms.harvard.edu/code/harvard-gdp/) | [Open](resources/harvard_gdp.md) |
| MMRDR | A recent multimodal diabetic retinopathy benchmark spanning CFP, OCT, and UWF imaging. | Classification \| Diabetic Retinopathy | 2025 | [Scientific Data](https://www.nature.com/articles/s41597-026-07005-9) | [Open](resources/mmrdr.md) |
| MultiEYE | A multimodal benchmark that uses fundus and OCT jointly during training while targeting fundus recognition at inference. | Classification \| Multi Disease | 2024 | [GitHub](https://github.com/xmed-lab/MultiEYE) | [Open](resources/multieye.md) |

---

<a id="field-guide"></a>
## • Field Guide

Alphabetical jump list for the dataset profiles in `resources/`.

- [FIVES](resources/fives.md)
- [GRAPE](resources/grape.md)
- [Harvard-GDP](resources/harvard_gdp.md)
- [Indian Diabetic Retinopathy Image Dataset](resources/idrid.md)
- [MMRDR](resources/mmrdr.md)
- [MultiEYE](resources/multieye.md)
- [OCT2017](resources/oct2017.md)
- [OCTA-500](resources/octa500.md)
- [OCTDL](resources/octdl.md)
- [Open Ultrawidefield Fundus Dataset](resources/open_uwf_fundus.md)
- [PALM](resources/palm.md)
- [PAPILA](resources/papila.md)
- [Retinal Fundus Multi-Disease Image Dataset](resources/rfmid.md)
- [ROSE](resources/rose.md)
