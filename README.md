# Awesome Ophthalmology Dataset

<p align="center"><strong>🔥 Awesome Ophthalmology Datasets 🔥</strong></p>

<p align="center">
  Multimodal · Multi-disease · Corneal · AMD · Glaucoma · DR · OCT · OCTA
</p>

<p align="center">
  <a href="#multimodal">Multimodal</a> · <a href="#multi_disease">Multi-disease</a> · <a href="#corneal">Corneal</a> · <a href="#amd">AMD</a> · <a href="#glaucoma">Glaucoma</a> · <a href="#diabetic_retinopathy">Diabetic Retinopathy</a> · <a href="#myopia">Myopia</a>
</p>

<p align="center">
  <a href="#segmentation_classification">Segmentation & Classification</a> · <a href="#ioct">iOCT</a> · <a href="#longitudinal">Longitudinal</a> · <a href="#registration">Registration</a> · <a href="#octa">OCTA</a> · <a href="#oct">OCT</a> · <a href="#additional_curated">Additional Curated</a>
</p>

<p align="center">
  <strong>Expanded for broad ophthalmology dataset coverage, fast scanning, and direct jump-to-profile browsing.</strong>
</p>

<p align="center">
  👁️ Public datasets · 📚 Profile pages in <code>resources/*.md</code> · 🚀 Built for quick comparison
</p>

> **Last updated:** 2026-04-18

## • Collection Pulse

| **77** | **14** | **77** | **2026-04-18** |
| --- | --- | --- | --- |
| Catalog entries | Top-level tracks | Profile pages | Current front page |

## • Track Map

| Track | Focus | Count | Jump |
| --- | --- | --- | --- |
| **Multimodal** | Datasets that combine multiple ophthalmic signals, image-text pairs, or paired modalities. | 3 | [Open](#multimodal) |
| **Multi-disease** | Collections built around broad retinal disease coverage rather than a single diagnosis family. | 3 | [Open](#multi_disease) |
| **Corneal** | Corneal and anterior-segment style microscopy or related ophthalmic imaging resources. | 1 | [Open](#corneal) |
| **AMD** | Datasets centered on age-related macular degeneration and adjacent retinal structure annotation. | 3 | [Open](#amd) |
| **Glaucoma** | Glaucoma detection, grading, segmentation, progression, and visual-field-oriented resources. | 10 | [Open](#glaucoma) |
| **Diabetic Retinopathy** | Datasets for diabetic retinopathy grading, lesion annotation, and screening. | 5 | [Open](#diabetic_retinopathy) |
| **Myopia** | Pathologic myopia and myopia-related ophthalmic imaging benchmarks. | 3 | [Open](#myopia) |
| **Segmentation & Classification** | General-purpose retinal imaging datasets used for segmentation, vessel analysis, and related classification tasks. | 26 | [Open](#segmentation_classification) |
| **iOCT** | Intraoperative OCT and closely related surgical OCT references. | 1 | [Open](#ioct) |
| **Longitudinal** | Datasets designed for sequential follow-up, progression analysis, or repeated-visit study. | 2 | [Open](#longitudinal) |
| **Registration** | Resources commonly used for retinal image registration and correspondence evaluation. | 3 | [Open](#registration) |
| **OCTA** | Optical coherence tomography angiography datasets and OCTA-specific quality or FAZ benchmarks. | 2 | [Open](#octa) |
| **OCT** | Retinal OCT datasets spanning classification, structural analysis, and lesion segmentation. | 12 | [Open](#oct) |
| **Additional Curated** | Additional public entries already curated in this repository beyond the imported reference list. | 3 | [Open](#additional_curated) |

## • Spotlight Tracks

- `Glaucoma` : [GRAPE](resources/grape.md), [Harvard glaucoma DP](resources/harvard_gdp.md), [PAPILA](resources/papila.md), [iChallenge-GAMMA](resources/ichallenge_gamma.md)
- `Diabetic Retinopathy` : [IDRiD](resources/idrid.md), [MAPLES-DR](resources/maples_dr.md), [MMRDR](resources/mmrdr.md), [DRSeg_TJDR](resources/drseg_tjdr.md)
- `Vessel and AV Analysis` : [FIVES](resources/fives.md), [ROSE](resources/rose.md), [Fundus_AV_WIDE](resources/fundus_av_wide.md), [LES-AV](resources/les_av.md)
- `Registration and Follow-up` : [FIRE](resources/fire.md), [FIMD](resources/fimd.md), [LongDRScreening_20150209](resources/longdrscreening_20150209.md), [SIGF-database](resources/sigf_database.md)

---

<a id="multimodal"></a>
## • Multimodal (3)

Datasets that combine multiple ophthalmic signals, image-text pairs, or paired modalities.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| FDDM TOPCON-MM | Fundus and OCT images in Guangdong Provincial Hospital of Integrated Traditional Chinese and Western Medicine using a Topcon Triton swept-source OCT featuring multimodal fundus imaging. | [Project Files](https://hkustconnect-my.sharepoint.com/personal/lwangdk_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Flwangdk%5Fconnect%5Fust%5Fhk%2FDocuments%2FMultieye%5Fresource%2Ftopconmm%5Fdata%2Ezip&parent=%2Fpersonal%2Flwangdk%5Fconnect%5Fust%5Fhk%2FDocuments%2FMultieye%5Fresource&ga=1) | [Open](resources/fddm_topcon_mm.md) |
| MM-Retinal | A multi-modal dataset that encompasses high-quality image-text pairs collected from professional fundus diagram books. | [Project Files](https://drive.google.com/drive/folders/177RCtDeA6n99gWqgBS_Sw3WT6qYbzVmy) | [Open](resources/mm_retinal.md) |
| OphNet | A Large-Scale Video Benchmark for Ophthalmic Surgical Workflow Understanding. | [Hugging Face](https://huggingface.co/datasets/xioamiyh/OphNet2024) | [Open](resources/ophnet.md) |

<a id="multi_disease"></a>
## • Multi-disease (3)

Collections built around broad retinal disease coverage rather than a single diagnosis family.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| Fundus_image | 26 files corresponding to 26 lesion types. | [GitHub](https://github.com/rymshasaeed/Automated-Eye-Cancer-Detection) | [Open](resources/fundus_image.md) |
| IRFUNDUSSET | Fundus image, a dataset that consolidates, harmonizes and curates several public datasets. | [Paper](https://arxiv.org/pdf/2402.11488.pdf) | [Open](resources/irfundusset.md) |
| RFMiD | Retinal Fundus Multi-Disease Image Dataset (RFMiD): A Dataset for Multi-Disease Detection Research. | [IEEE DataPort](https://ieee-dataport.org/open-access/retinal-fundus-multi-disease-image-dataset-rfmid) | [Open](resources/rfmid.md) |

<a id="corneal"></a>
## • Corneal (1)

Corneal and anterior-segment style microscopy or related ophthalmic imaging resources.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| ConfEndoMicr | 52 in-vivo confocal corneal microscopy images. | [Official Page](http://www.rodrep.com/confocal-corneal-endothelial-microscopy---description.html) | [Open](resources/confendomicr.md) |

<a id="amd"></a>
## • AMD (3)

Datasets centered on age-related macular degeneration and adjacent retinal structure annotation.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| 2011_IOVS_Chiu | Segment leision of AMD based on SDOCT. | [Official Page](https://people.duke.edu/~sf59/Chiu_IOVS_2011_dataset.htm) | [Open](resources/d_2011_iovs_chiu.md) |
| AMD_RPEDC | TR,RPEDC volumn,RPEDC abnormal,normal. | [Official Page](https://people.duke.edu/~sf59/RPEDC_Ophth_2013_dataset.htm) | [Open](resources/amd_rpedc.md) |
| iChallenge: AMD/Non_AMD and DF_Annotation(disc_fovea) | AMD:89, Non-AMD:311, DF:44. | [Baidu AI Studio](https://aistudio.baidu.com/aistudio/datasetdetail/88462) | [Open](resources/ichallenge_amd_non_amd_and_df_annotation_disc_fovea.md) |

<a id="glaucoma"></a>
## • Glaucoma (10)

Glaucoma detection, grading, segmentation, progression, and visual-field-oriented resources.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| BEH (Bangladesh Eye Hospital) Dataset | Normal:463;glaucoma:171. | [Official Page](https://www.researchgate.net/publication/357382043_Deep_Learning-Based_Glaucoma_Detection_With_Cropped_Optic_Cup_and_Disc_and_Blood_Vessel_Segmentation) | [Open](resources/beh_bangladesh_eye_hospital_dataset.md) |
| Fundus-doFE | Adopt the Domain Knowledge PoolMpoolto learn and memorizethe multi-source domain prior knowledge, enrich the image semantic featurehs. | [Paper](https://arxiv.org/pdf/2010.06208.pdf) | [Open](resources/fundus_dofe.md) |
| GRAPE | VFs,fundus,OCT,clinical information,follow-up records. | [Nature](https://www.nature.com/articles/s41597-023-02424-4) | [Open](resources/grape.md) |
| Harvard glaucoma | 3300 images. | [Official Page](https://ophai.hms.harvard.edu/datasets/harvard-gf3300/) | [Open](resources/harvard_glaucoma.md) |
| Harvard glaucoma DP | Detection and progression. | [Official Page](https://ophai.hms.harvard.edu/datasets/harvard-gdp1000) | [Open](resources/harvard_gdp.md) |
| Harvard-EF30k | 30k images,glaucoma,AMD,DR. | [Official Page](https://ophai.hms.harvard.edu/datasets/harvard-ef30k) | [Open](resources/harvard_ef30k.md) |
| HarvardFairSeg10k | Segmentation. | [Paper](https://arxiv.org/abs/2311.02189) | [Open](resources/harvardfairseg10k.md) |
| iChallenge-GAMMA | Grading glaucoma,Segmentation of optic disc and cup,Localization of fovea macula. | [Grand Challenge](https://gamma.grand-challenge.org/) | [Open](resources/ichallenge_gamma.md) |
| LongGlaucVF_20150216 | Visual field. | [Official Page](http://www.rodrep.com/longitudinal-glaucomatous-vf-data---description.html) | [Open](resources/longglaucvf_20150216.md) |
| PAPILA | Dataset with fundus images and clinical data of the same patient for glaucoma assessment. | [Nature](https://www.nature.com/articles/s41597-022-01388-1) | [Open](resources/papila.md) |

<a id="diabetic_retinopathy"></a>
## • Diabetic Retinopathy (5)

Datasets for diabetic retinopathy grading, lesion annotation, and screening.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| DRSeg_TJDR | High-Quality Diabetic Retinopathy Pixel-Level Annotation Dataset. | [Paper](https://arxiv.org/abs/2312.15389) | [Open](resources/drseg_tjdr.md) |
| IDRiD | Diabetic retinopathy lesions and normal retinal structures,disease severity level,international standards of clinical relevance. | [Grand Challenge](https://idrid.grand-challenge.org/Data/) | [Open](resources/idrid.md) |
| LongDRScreening_20150209 | Fundus image registration method. | [Paper](https://iovs.arvojournals.org/article.aspx?articleid=2212963) | [Open](resources/longdrscreening_20150209.md) |
| MAPLES-DR | New diagnoses for DR and ME. | [Paper](https://arxiv.org/abs/2402.04258) | [Open](resources/maples_dr.md) |
| MESSIDOR-2 | How does the prediction model performs on test dataset that is from a different source; Diabetic Retinopathy Classification from Fundus Images. | [Paper](https://ieeexplore.ieee.org/document/9918681) | [Open](resources/messidor_2.md) |

<a id="myopia"></a>
## • Myopia (3)

Pathologic myopia and myopia-related ophthalmic imaging benchmarks.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| Paddle | IChallenge dataset,Baidu. | [Baidu AI Studio](https://aistudio.baidu.com/aistudio/datasetdetail/23828) | [Open](resources/paddle.md) |
| PALM | Pathlogical myopia challenge;. | [IEEE DataPort](https://ieee-dataport.org/documents/palm-pathologic-myopia-challenge) | [Open](resources/palm.md) |
| PALM_zhang | Leision mask,PC,Disc,fovea localization. | [Nature](https://www.nature.com/articles/s41597-024-02911-2) | [Open](resources/palm_zhang.md) |

<a id="segmentation_classification"></a>
## • Segmentation & Classification (26)

General-purpose retinal imaging datasets used for segmentation, vessel analysis, and related classification tasks.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| 2013_BOE_Chiu | Photoreceptor segmentation. | [Official Page](https://people.duke.edu/~sf59/Chiu_BOE_2013_dataset.htm) | [Open](resources/d_2013_boe_chiu.md) |
| Chase-DB | A dataset for retinal vessel segmentation which contains 28 color retina images with the size of 999×960 pixels. Each image is annotated by two independent human experts. | [Paper](https://ieeexplore.ieee.org/document/6224174) | [Open](resources/chase_db.md) |
| Chiu_BOE_2012 | Automatic Segmentation of Closed Contour Features. | [Official Page](https://people.duke.edu/~sf59/Chiu_BOE_2012_dataset.htm) | [Open](resources/chiu_boe_2012.md) |
| DR-HAGIS | Segmentation algorithms; four subgroups. | [Paper](https://pubmed.ncbi.nlm.nih.gov/28217714/) | [Open](resources/dr_hagis.md) |
| DRIVE | Retinal vessel segmentation. | [Paper](https://ieeexplore.ieee.org/document/1282003) | [Open](resources/drive.md) |
| FIVES | 800 high-resolution multi-disease color fundus. | [Nature](https://www.nature.com/articles/s41597-022-01564-3) | [Open](resources/fives.md) |
| Fundus_AV_WIDE | This dataset consists of 30 wide-field of color images and their annotated features for artery-vein classification. | [Official Page](https://people.duke.edu/~sf59/Estrada_TMI_2015_dataset.htm) | [Open](resources/fundus_av_wide.md) |
| ganglion | Ganglion cell segmentation. | [Official Page](https://people.duke.edu/~sf59/Soltanian_Optica_2021.htm) | [Open](resources/ganglion.md) |
| HRF | Vessel segmentation of fundus image. | [Official Page](https://www5.cs.fau.de/research/data/fundus-images/) | [Open](resources/hrf.md) |
| ICPRVessels | Vessels-dataset. | [Paper](https://arxiv.org/abs/2012.09250) | [Open](resources/icprvessels.md) |
| ID | Retinal recognition. | [Mendeley Data](https://data.mendeley.com/datasets/tjw3zwntv6/2) | [Open](resources/id.md) |
| IOSTAR | Retinal vessel segmentation. | [Official Page](https://www.idiap.ch/software/bob/docs/bob/bob.db.iostar/stable/) | [Open](resources/iostar.md) |
| LES-AV | Vessel annotations and labels for arteries and veins. | [Paper](https://arxiv.org/abs/1805.10273) | [Open](resources/les_av.md) |
| Lesion | Retinal lesions segmentation. | [Paper](https://arxiv.org/abs/1912.11619) | [Open](resources/lesion.md) |
| mmRV-v1 | Fundus-OCTA. | [Paper](https://arxiv.org/abs/2203.03631) | [Open](resources/mmrv_v1.md) |
| Open_BUA_AV | Multi-scale interactive network with artery/vein discriminator for retinal vessel classification. | [GitHub](https://github.com/TwistedW/MIAV) | [Open](resources/open_bua_av.md) |
| RAVIR_AV_seg | - | [Official Page](https://ravirdataset.github.io/data/) | [Open](resources/ravir_av_seg.md) |
| retinal | Retinal vessel segmentation and vascular tree analysis. | [Official Page](https://reta-benchmark.org/) | [Open](resources/retinal.md) |
| Retinal Tortuosity | Retinal vessel tortuosity. | [Official Page](https://bioimlab.dei.unipd.it/Retinal%20Vessel%20Tortuosity.htm) | [Open](resources/retinal_tortuosity.md) |
| ROSE | Retinal OCTA SEgmentation. | [Paper](https://arxiv.org/abs/2007.05201) | [Open](resources/rose.md) |
| RVD_VIDEO | First video-based retinal dataset by employing handheld devices for data acquisition. | [Paper](https://arxiv.org/abs/2307.06577) | [Open](resources/rvd_video.md) |
| Seg_leakage | Segmentation of Fluorescein Leakage. | [Official Page](https://people.duke.edu/~sf59/Rabbani_IOVS_2014_dataset.htm) | [Open](resources/seg_leakage.md) |
| SNP_Segmentation | Segmentation of Neuronal Structures in Corneal Confocal Microscopy Images. | [Official Page](https://people.duke.edu/~sf59/Zemborain_SNP_Net.htm) | [Open](resources/snp_segmentation.md) |
| STARE | Retinal vessel segmentation; color fundus images. | [Paper](https://arxiv.org/abs/2009.12053) | [Open](resources/stare.md) |
| Tree_topology_PAMI_2015 | Segment vessel trees. | [Official Page](https://people.duke.edu/~sf59/Estrada_PAMI_2015_dataset.htm) | [Open](resources/tree_topology_pami_2015.md) |
| UT-FSOCTA | Generative adversarial networks to create vascular maps. | [Zenodo](https://zenodo.org/records/6476639) | [Open](resources/ut_fsocta.md) |

<a id="ioct"></a>
## • iOCT (1)

Intraoperative OCT and closely related surgical OCT references.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| iOCT | Vitreoretinal Diseases. | [Paper](https://pubmed.ncbi.nlm.nih.gov/26265908/) | [Open](resources/ioct.md) |

<a id="longitudinal"></a>
## • Longitudinal (2)

Datasets designed for sequential follow-up, progression analysis, or repeated-visit study.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| OLIVES | 99 eyes' data averaged over a period of at least two years with each eye treated for an average of 66 weeks and 7 injections. | [Paper](https://arxiv.org/abs/2209.11195) | [Open](resources/olives.md) |
| SIGF-database | Glaucoma Forecast Using the Sequential Fundus Images. | [Official Page](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_60) | [Open](resources/sigf_database.md) |

<a id="registration"></a>
## • Registration (3)

Resources commonly used for retinal image registration and correspondence evaluation.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| FIMD | Fundus image myopia control points pairs(70). | [IEEE DataPort](https://ieee-dataport.org/documents/fundus-image-myopia-development-fimd-dataset) | [Open](resources/fimd.md) |
| FIRE | Fundus images. | [Official Page](https://projects.ics.forth.gr/cvrl/fire/) | [Open](resources/fire.md) |
| VARPA_r2 | Retinal images. | [Official Page](http://www.varpa.es/research/biometrics.html) | [Open](resources/varpa_r2.md) |

<a id="octa"></a>
## • OCTA (2)

Optical coherence tomography angiography datasets and OCTA-specific quality or FAZ benchmarks.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| OCTA-500 | Retinal imaging modality that allows a micron-level resolution to present the three-dimensional structure of the retinal vascular. | [IEEE DataPort](https://ieee-dataport.org/open-access/octa-500) | [Open](resources/octa500.md) |
| quality_assessment | Quality assessment and FAZ segmantation. | [Official Page](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4073651) | [Open](resources/quality_assessment.md) |

<a id="oct"></a>
## • OCT (12)

Retinal OCT datasets spanning classification, structural analysis, and lesion segmentation.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| 2014_BOE_Srinivasan | - | [Paper](https://ieeexplore.ieee.org/document/9190742) | [Open](resources/d_2014_boe_srinivasan.md) |
| 2015_BOE_Chiu2 | Layer segmentation. | [Official Page](https://people.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm) | [Open](resources/d_2015_boe_chiu2.md) |
| 8kt969dhx6-1 | More than 16,000 retinal OCT B-scans from 441 cases (Normal: 120, Drusen: 160, CNV: 161). | [Mendeley Data](https://data.mendeley.com/datasets/8kt969dhx6/1) | [Open](resources/d_8kt969dhx6_1.md) |
| archive | Heiderlberg_OCT,Rabbani_2015,spie_OCT. | [Official Page](https://www.kaggle.com/datasets/kmader/eye-oct-datasets) | [Open](resources/archive.md) |
| Data on OCT and Fundus Images | 50 OCT and Fundus images  which included health and glaucomatous images. | [Mendeley Data](https://data.mendeley.com/datasets/2rnnz5nz74/2) | [Open](resources/data_on_oct_and_fundus_images.md) |
| OCT2017.tar | CNV, DME, DRUSEN, and NORMAL. | [Mendeley Data](https://data.mendeley.com/datasets/rscbjbr9sj/1) | [Open](resources/oct2017.md) |
| OCT_Manual_Delineations-2018_June_29 | 14 healthy controls (HC) and 21 patients with multiple sclerosis (MS). | [Official Page](https://iacl.ece.jhu.edu/index.php?title=Main_Page) | [Open](resources/oct_manual_delineations_2018_june_29.md) |
| OCTDL | 500 high-resolution images categorized into different pathological conditions. | [Paper](https://arxiv.org/abs/2312.08255) | [Open](resources/octdl.md) |
| OCTIRD | - | [Official Page](https://www.openicpsr.org/openicpsr/project/108503/version/V1/view?path=/openicpsr/108503/fcr:versions/V1&type=project) | [Open](resources/octird.md) |
| octlayerdataverse_files | Different retinal OCT images with different pathological conditions. | [Official Page](https://borealisdata.ca/dataverse/OCTID) | [Open](resources/octlayerdataverse_files.md) |
| THOCT1800 | 1800 preprocessed retinal SD-OCT B-scans (600 AMD, 600 DME, and 600 NOR). | [GitHub](https://github.com/SJD095/OCT-Segmentation) | [Open](resources/thoct1800.md) |
| ZhangLabData | Chest xray data, plus for optical coherence tomography (OCT) images. | [Paper](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5) | [Open](resources/zhanglabdata.md) |

<a id="additional_curated"></a>
## • Additional Curated (3)

Additional public entries already curated in this repository beyond the imported reference list.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| MMRDR | A recent multimodal diabetic retinopathy benchmark spanning CFP, OCT, and UWF imaging. | [Nature](https://www.nature.com/articles/s41597-026-07005-9) | [Open](resources/mmrdr.md) |
| MultiEYE | A multimodal benchmark that uses fundus and OCT jointly during training while targeting fundus recognition at inference. | [GitHub](https://github.com/xmed-lab/MultiEYE) | [Open](resources/multieye.md) |
| Open Ultrawidefield Fundus Dataset | A dedicated ultrawidefield fundus dataset with diagnosis labels, demographics, and image-quality assessment. | [Nature](https://www.nature.com/articles/s41597-024-04113-2) | [Open](resources/open_uwf_fundus.md) |

---

<a id="resources"></a>
## • Field Guide

Alphabetical jump list for the profile pages in `resources/`.

- [2011_IOVS_Chiu](resources/d_2011_iovs_chiu.md)
- [2013_BOE_Chiu](resources/d_2013_boe_chiu.md)
- [2014_BOE_Srinivasan](resources/d_2014_boe_srinivasan.md)
- [2015_BOE_Chiu2](resources/d_2015_boe_chiu2.md)
- [8kt969dhx6-1](resources/d_8kt969dhx6_1.md)
- [AMD_RPEDC](resources/amd_rpedc.md)
- [archive](resources/archive.md)
- [BEH (Bangladesh Eye Hospital) Dataset](resources/beh_bangladesh_eye_hospital_dataset.md)
- [Chase-DB](resources/chase_db.md)
- [Chiu_BOE_2012](resources/chiu_boe_2012.md)
- [ConfEndoMicr](resources/confendomicr.md)
- [Data on OCT and Fundus Images](resources/data_on_oct_and_fundus_images.md)
- [DR-HAGIS](resources/dr_hagis.md)
- [DRIVE](resources/drive.md)
- [DRSeg_TJDR](resources/drseg_tjdr.md)
- [FDDM TOPCON-MM](resources/fddm_topcon_mm.md)
- [FIMD](resources/fimd.md)
- [FIRE](resources/fire.md)
- [FIVES](resources/fives.md)
- [Fundus-doFE](resources/fundus_dofe.md)
- [Fundus_AV_WIDE](resources/fundus_av_wide.md)
- [Fundus_image](resources/fundus_image.md)
- [ganglion](resources/ganglion.md)
- [GRAPE](resources/grape.md)
- [Harvard glaucoma](resources/harvard_glaucoma.md)
- [Harvard glaucoma DP](resources/harvard_gdp.md)
- [Harvard-EF30k](resources/harvard_ef30k.md)
- [HarvardFairSeg10k](resources/harvardfairseg10k.md)
- [HRF](resources/hrf.md)
- [iChallenge-GAMMA](resources/ichallenge_gamma.md)
- [iChallenge: AMD/Non_AMD and DF_Annotation(disc_fovea)](resources/ichallenge_amd_non_amd_and_df_annotation_disc_fovea.md)
- [ICPRVessels](resources/icprvessels.md)
- [ID](resources/id.md)
- [IDRiD](resources/idrid.md)
- [iOCT](resources/ioct.md)
- [IOSTAR](resources/iostar.md)
- [IRFUNDUSSET](resources/irfundusset.md)
- [LES-AV](resources/les_av.md)
- [Lesion](resources/lesion.md)
- [LongDRScreening_20150209](resources/longdrscreening_20150209.md)
- [LongGlaucVF_20150216](resources/longglaucvf_20150216.md)
- [MAPLES-DR](resources/maples_dr.md)
- [MESSIDOR-2](resources/messidor_2.md)
- [MM-Retinal](resources/mm_retinal.md)
- [MMRDR](resources/mmrdr.md)
- [mmRV-v1](resources/mmrv_v1.md)
- [MultiEYE](resources/multieye.md)
- [OCT2017.tar](resources/oct2017.md)
- [OCT_Manual_Delineations-2018_June_29](resources/oct_manual_delineations_2018_june_29.md)
- [OCTA-500](resources/octa500.md)
- [OCTDL](resources/octdl.md)
- [OCTIRD](resources/octird.md)
- [octlayerdataverse_files](resources/octlayerdataverse_files.md)
- [OLIVES](resources/olives.md)
- [Open Ultrawidefield Fundus Dataset](resources/open_uwf_fundus.md)
- [Open_BUA_AV](resources/open_bua_av.md)
- [OphNet](resources/ophnet.md)
- [Paddle](resources/paddle.md)
- [PALM](resources/palm.md)
- [PALM_zhang](resources/palm_zhang.md)
- [PAPILA](resources/papila.md)
- [quality_assessment](resources/quality_assessment.md)
- [RAVIR_AV_seg](resources/ravir_av_seg.md)
- [retinal](resources/retinal.md)
- [Retinal Tortuosity](resources/retinal_tortuosity.md)
- [RFMiD](resources/rfmid.md)
- [ROSE](resources/rose.md)
- [RVD_VIDEO](resources/rvd_video.md)
- [Seg_leakage](resources/seg_leakage.md)
- [SIGF-database](resources/sigf_database.md)
- [SNP_Segmentation](resources/snp_segmentation.md)
- [STARE](resources/stare.md)
- [THOCT1800](resources/thoct1800.md)
- [Tree_topology_PAMI_2015](resources/tree_topology_pami_2015.md)
- [UT-FSOCTA](resources/ut_fsocta.md)
- [VARPA_r2](resources/varpa_r2.md)
- [ZhangLabData](resources/zhanglabdata.md)
