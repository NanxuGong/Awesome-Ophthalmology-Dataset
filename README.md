# Awesome Ophthalmology Dataset

<p align="center"><strong>✦ A curated browsing hub for ophthalmology datasets ✦</strong></p>

<p align="center">
  Fundus · OCT · OCTA · Multimodal · Corneal · Longitudinal · Registration
</p>

<p align="center">
  <a href="tags/README.md">Tag Search</a> · <a href="resources/README.md">Profile Directory</a> · <a href="#starting-paths">Starting Paths</a> · <a href="#track-atlas">Track Atlas</a> · <a href="#track-shelves">Track Shelves</a>
</p>

Display-first collection for browsing ophthalmology datasets through two parallel views:
curated track groups for fast scanning, and tag-based indices for precise lookup.  
Detailed dataset pages live in [resources/](resources/README.md), while faceted browsing lives in [tags/](tags/README.md).

> **Last updated:** 2026-04-20

## Collection Snapshot

| **77** | **77** | **14** | **6** |
| --- | --- | --- | --- |
| Catalog entries | Profile pages | Track groups | Tag categories |

## Browse Playbook

| Route | Best for | Open |
| --- | --- | --- |
| Start with tags | Best when you already know the slice you want, such as fundus, segmentation, glaucoma, or multimodal | [tags/README.md](tags/README.md) |
| Start with tracks | Best when you want a curator-style overview across benchmark families | [Track Atlas](#track-atlas) |
| Start with profiles | Best when you want the full alphabetical dataset directory | [resources/README.md](resources/README.md) |
| Start with modality | Best when your search begins from imaging type rather than task | [tags/modality.md](tags/modality.md) |
| Start with task | Best when your search begins from evaluation setup | [tags/task.md](tags/task.md) |
| Start with disease target | Best when your search begins from a clinical problem | [tags/disease_target.md](tags/disease_target.md) |

## Tag Lenses

| Lens | Sub-tags | What it gives you |
| --- | ---: | --- |
| [Modality](tags/modality.md) | 7 | Imaging-first browsing across fundus, OCT, OCTA, corneal microscopy, multimodal, and related groups |
| [Task](tags/task.md) | 14 | Evaluation-first browsing for classification, segmentation, grading, localization, registration, progression, and more |
| [Disease / Target](tags/disease_target.md) | 8 | Clinical-target browsing for glaucoma, diabetic retinopathy, AMD, myopia, retinal vessel analysis, and similar themes |
| [Input Signal](tags/input_signal.md) | 7 | Signal-level browsing for image, video, visual field, and multimodal input setups |
| [Label Form](tags/label_form.md) | 11 | Annotation-type browsing across masks, grades, landmarks, registration pairs, and other label structures |
| [Property](tags/property.md) | 2 | Dataset properties such as longitudinal or multimodal organization |

## Navigation Notes

- `Track` pages are best for broad scanning and getting a feel for the catalog.
- `Tag` pages are best for focused lookup across modality, task, disease target, input signal, label form, and dataset property.
- `Resource` pages are where the detailed dataset information, statistics, and official links live.

<a id="starting-paths"></a>
## Starting Paths

- **Glaucoma and progression:** [GRAPE](resources/grape.md), [Harvard glaucoma DP](resources/harvard_gdp.md), [PAPILA](resources/papila.md), [iChallenge-GAMMA](resources/ichallenge_gamma.md)
- **Diabetic retinopathy and lesions:** [IDRiD](resources/idrid.md), [MAPLES-DR](resources/maples_dr.md), [MMRDR](resources/mmrdr.md), [DRSeg_TJDR](resources/drseg_tjdr.md)
- **Vessel and artery-vein analysis:** [FIVES](resources/fives.md), [ROSE](resources/rose.md), [Fundus_AV_WIDE](resources/fundus_av_wide.md), [LES-AV](resources/les_av.md)
- **OCT and OCTA baselines:** [OCT2017.tar](resources/oct2017.md), [OCTDL](resources/octdl.md), [OCTA-500](resources/octa500.md), [ROSE](resources/rose.md)
- **Multimodal and paired signals:** [MultiEYE](resources/multieye.md), [MM-Retinal](resources/mm_retinal.md), [FDDM TOPCON-MM](resources/fddm_topcon_mm.md), [OphNet](resources/ophnet.md)

<a id="track-atlas"></a>
## Track Atlas

| Track | Count | Focus | Jump |
| --- | ---: | --- | --- |
| **Multimodal** | 3 | Image-text pairs, paired modality settings, and multimodal surgical video data | [Open](#multimodal) |
| **Multi-disease** | 3 | Broad retinal disease coverage rather than one-disease-only benchmarking | [Open](#multi_disease) |
| **Corneal** | 1 | Corneal microscopy and anterior-segment style resources | [Open](#corneal) |
| **AMD** | 3 | AMD structure and disease-oriented datasets | [Open](#amd) |
| **Glaucoma** | 10 | Detection, grading, segmentation, progression, and visual field resources | [Open](#glaucoma) |
| **Diabetic Retinopathy** | 5 | DR grading, lesion annotation, and screening datasets | [Open](#diabetic_retinopathy) |
| **Myopia** | 3 | Pathologic myopia and myopia-related fundus resources | [Open](#myopia) |
| **Segmentation & Classification** | 26 | General retinal segmentation, vessel analysis, and classic benchmarks | [Open](#segmentation_classification) |
| **iOCT** | 1 | Intraoperative OCT references | [Open](#ioct) |
| **Longitudinal** | 2 | Follow-up, repeated-visit, and progression-style datasets | [Open](#longitudinal) |
| **Registration** | 3 | Retinal registration and correspondence datasets | [Open](#registration) |
| **OCTA** | 2 | OCTA-specific vascular and quality benchmarks | [Open](#octa) |
| **OCT** | 12 | OCT classification, structural analysis, and lesion segmentation resources | [Open](#oct) |
| **Additional Curated** | 3 | Extra public entries added beyond the imported reference list | [Open](#additional_curated) |

<a id="track-shelves"></a>
## Track Shelves

Expandable catalog shelves for all 14 track groups. Open a shelf to scan the datasets in that lane, then jump into the linked profile page for details.

---

<a id="multimodal"></a>
<details>
<summary><strong>Multimodal</strong> · 3 datasets · image-text pairs, paired modalities, and multimodal surgical video data</summary>

Datasets that combine multiple ophthalmic signals, image-text pairs, or paired modalities.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| FDDM TOPCON-MM | Topcon multimodal fundus and OCT collection. | [Project Files](https://hkustconnect-my.sharepoint.com/personal/lwangdk_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Flwangdk%5Fconnect%5Fust%5Fhk%2FDocuments%2FMultieye%5Fresource%2Ftopconmm%5Fdata%2Ezip&parent=%2Fpersonal%2Flwangdk%5Fconnect%5Fust%5Fhk%2FDocuments%2FMultieye%5Fresource&ga=1) | [Open](resources/fddm_topcon_mm.md) |
| MM-Retinal | Fundus image-text benchmark built from professional retinal diagrams. | [Project Files](https://drive.google.com/drive/folders/177RCtDeA6n99gWqgBS_Sw3WT6qYbzVmy) | [Open](resources/mm_retinal.md) |
| OphNet | Large-scale ophthalmic surgical workflow video benchmark. | [Hugging Face](https://huggingface.co/datasets/xioamiyh/OphNet2024) | [Open](resources/ophnet.md) |

</details>

<a id="multi_disease"></a>
<details>
<summary><strong>Multi-disease</strong> · 3 datasets · broad retinal disease coverage beyond one-disease-only benchmarking</summary>

Collections built around broad retinal disease coverage rather than a single diagnosis family.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| Fundus_image | Lesion-oriented fundus set spanning 26 categories. | [GitHub](https://github.com/rymshasaeed/Automated-Eye-Cancer-Detection) | [Open](resources/fundus_image.md) |
| IRFUNDUSSET | Curated fundus benchmark assembled from multiple public datasets. | [Paper](https://arxiv.org/pdf/2402.11488.pdf) | [Open](resources/irfundusset.md) |
| RFMiD | Multi-disease fundus benchmark for retinal condition recognition. | [IEEE DataPort](https://ieee-dataport.org/open-access/retinal-fundus-multi-disease-image-dataset-rfmid) | [Open](resources/rfmid.md) |

</details>

<a id="corneal"></a>
<details>
<summary><strong>Corneal</strong> · 1 dataset · corneal microscopy and anterior-segment style resources</summary>

Corneal and anterior-segment style microscopy or related ophthalmic imaging resources.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| ConfEndoMicr | In-vivo confocal corneal microscopy benchmark. | [Official Page](http://www.rodrep.com/confocal-corneal-endothelial-microscopy---description.html) | [Open](resources/confendomicr.md) |

</details>

<a id="amd"></a>
<details>
<summary><strong>AMD</strong> · 3 datasets · AMD structure and disease-oriented collections</summary>

Datasets centered on age-related macular degeneration and adjacent retinal structure annotation.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| 2011_IOVS_Chiu | SD-OCT benchmark for AMD lesion segmentation. | [Official Page](https://people.duke.edu/~sf59/Chiu_IOVS_2011_dataset.htm) | [Open](resources/d_2011_iovs_chiu.md) |
| AMD_RPEDC | AMD OCT set for RPEDC and related structure analysis. | [Official Page](https://people.duke.edu/~sf59/RPEDC_Ophth_2013_dataset.htm) | [Open](resources/amd_rpedc.md) |
| iChallenge: AMD/Non_AMD and DF_Annotation(disc_fovea) | AMD screening and disc-fovea localization challenge subset. | [Baidu AI Studio](https://aistudio.baidu.com/aistudio/datasetdetail/88462) | [Open](resources/ichallenge_amd_non_amd_and_df_annotation_disc_fovea.md) |

</details>

<a id="glaucoma"></a>
<details>
<summary><strong>Glaucoma</strong> · 10 datasets · detection, grading, segmentation, progression, and visual field resources</summary>

Glaucoma detection, grading, segmentation, progression, and visual-field-oriented resources.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| BEH (Bangladesh Eye Hospital) Dataset | Fundus glaucoma set with normal and glaucoma classes. | [Official Page](https://www.researchgate.net/publication/357382043_Deep_Learning-Based_Glaucoma_Detection_With_Cropped_Optic_Cup_and_Disc_and_Blood_Vessel_Segmentation) | [Open](resources/beh_bangladesh_eye_hospital_dataset.md) |
| Fundus-doFE | Fundus benchmark used in glaucoma domain generalization studies. | [Paper](https://arxiv.org/pdf/2010.06208.pdf) | [Open](resources/fundus_dofe.md) |
| GRAPE | Longitudinal glaucoma benchmark with VF, fundus, OCT, and clinical records. | [Nature](https://www.nature.com/articles/s41597-023-02424-4) | [Open](resources/grape.md) |
| Harvard glaucoma | Large-scale Harvard fundus glaucoma benchmark. | [Official Page](https://ophai.hms.harvard.edu/datasets/harvard-gf3300/) | [Open](resources/harvard_glaucoma.md) |
| Harvard glaucoma DP | Harvard dataset for glaucoma detection and progression. | [Official Page](https://ophai.hms.harvard.edu/datasets/harvard-gdp1000) | [Open](resources/harvard_gdp.md) |
| Harvard-EF30k | Large Harvard fundus set covering glaucoma, AMD, and DR. | [Official Page](https://ophai.hms.harvard.edu/datasets/harvard-ef30k) | [Open](resources/harvard_ef30k.md) |
| HarvardFairSeg10k | Fairness-oriented fundus segmentation benchmark from Harvard. | [Paper](https://arxiv.org/abs/2311.02189) | [Open](resources/harvardfairseg10k.md) |
| iChallenge-GAMMA | Glaucoma grading, disc-cup segmentation, and fovea localization challenge. | [Grand Challenge](https://gamma.grand-challenge.org/) | [Open](resources/ichallenge_gamma.md) |
| LongGlaucVF_20150216 | Longitudinal visual field dataset for glaucoma analysis. | [Official Page](http://www.rodrep.com/longitudinal-glaucomatous-vf-data---description.html) | [Open](resources/longglaucvf_20150216.md) |
| PAPILA | Paired fundus and clinical glaucoma benchmark. | [Nature](https://www.nature.com/articles/s41597-022-01388-1) | [Open](resources/papila.md) |

</details>

<a id="diabetic_retinopathy"></a>
<details>
<summary><strong>Diabetic Retinopathy</strong> · 5 datasets · grading, lesion annotation, and screening resources</summary>

Datasets for diabetic retinopathy grading, lesion annotation, and screening.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| DRSeg_TJDR | Pixel-level DR lesion annotation benchmark. | [Paper](https://arxiv.org/abs/2312.15389) | [Open](resources/drseg_tjdr.md) |
| IDRiD | DR grading, lesion segmentation, and landmark benchmark. | [Grand Challenge](https://idrid.grand-challenge.org/Data/) | [Open](resources/idrid.md) |
| LongDRScreening_20150209 | Registration-focused follow-up DR screening dataset. | [Paper](https://iovs.arvojournals.org/article.aspx?articleid=2212963) | [Open](resources/longdrscreening_20150209.md) |
| MAPLES-DR | DR and macular edema relabeling benchmark. | [Paper](https://arxiv.org/abs/2402.04258) | [Open](resources/maples_dr.md) |
| MESSIDOR-2 | Cross-source fundus benchmark for DR classification. | [Paper](https://ieeexplore.ieee.org/document/9918681) | [Open](resources/messidor_2.md) |

</details>

<a id="myopia"></a>
<details>
<summary><strong>Myopia</strong> · 3 datasets · pathologic myopia and related fundus resources</summary>

Pathologic myopia and myopia-related ophthalmic imaging benchmarks.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| Paddle | Baidu AI Studio release of iChallenge myopia data. | [Baidu AI Studio](https://aistudio.baidu.com/aistudio/datasetdetail/23828) | [Open](resources/paddle.md) |
| PALM | Pathologic myopia challenge benchmark. | [IEEE DataPort](https://ieee-dataport.org/documents/palm-pathologic-myopia-challenge) | [Open](resources/palm.md) |
| PALM_zhang | Pathologic myopia set with lesion masks and anatomy landmarks. | [Nature](https://www.nature.com/articles/s41597-024-02911-2) | [Open](resources/palm_zhang.md) |

</details>

<a id="segmentation_classification"></a>
<details>
<summary><strong>Segmentation &amp; Classification</strong> · 26 datasets · classic retinal benchmarks, vessel analysis, and general segmentation resources</summary>

General-purpose retinal imaging datasets used for segmentation, vessel analysis, and related classification tasks.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| 2013_BOE_Chiu | OCT photoreceptor segmentation benchmark. | [Official Page](https://people.duke.edu/~sf59/Chiu_BOE_2013_dataset.htm) | [Open](resources/d_2013_boe_chiu.md) |
| Chase-DB | Classic fundus vessel segmentation dataset with dual annotations. | [Paper](https://ieeexplore.ieee.org/document/6224174) | [Open](resources/chase_db.md) |
| Chiu_BOE_2012 | OCT closed-contour structure segmentation benchmark. | [Official Page](https://people.duke.edu/~sf59/Chiu_BOE_2012_dataset.htm) | [Open](resources/chiu_boe_2012.md) |
| DR-HAGIS | Retinal segmentation benchmark with four evaluation subgroups. | [Paper](https://pubmed.ncbi.nlm.nih.gov/28217714/) | [Open](resources/dr_hagis.md) |
| DRIVE | Classic retinal vessel segmentation benchmark. | [Paper](https://ieeexplore.ieee.org/document/1282003) | [Open](resources/drive.md) |
| FIVES | High-resolution fundus vessel dataset with multi-disease background. | [Nature](https://www.nature.com/articles/s41597-022-01564-3) | [Open](resources/fives.md) |
| Fundus_AV_WIDE | Wide-field artery-vein classification benchmark. | [Official Page](https://people.duke.edu/~sf59/Estrada_TMI_2015_dataset.htm) | [Open](resources/fundus_av_wide.md) |
| ganglion | OCT ganglion cell segmentation benchmark. | [Official Page](https://people.duke.edu/~sf59/Soltanian_Optica_2021.htm) | [Open](resources/ganglion.md) |
| HRF | High-resolution fundus vessel segmentation dataset. | [Official Page](https://www5.cs.fau.de/research/data/fundus-images/) | [Open](resources/hrf.md) |
| ICPRVessels | Retinal vessel benchmark released with ICPRVessels. | [Paper](https://arxiv.org/abs/2012.09250) | [Open](resources/icprvessels.md) |
| ID | Retinal image recognition dataset on Mendeley. | [Mendeley Data](https://data.mendeley.com/datasets/tjw3zwntv6/2) | [Open](resources/id.md) |
| IOSTAR | Stereo fundus vessel segmentation benchmark. | [Official Page](https://www.idiap.ch/software/bob/docs/bob/bob.db.iostar/stable/) | [Open](resources/iostar.md) |
| LES-AV | Retinal artery-vein annotation benchmark. | [Paper](https://arxiv.org/abs/1805.10273) | [Open](resources/les_av.md) |
| Lesion | Fundus retinal lesion segmentation dataset. | [Paper](https://arxiv.org/abs/1912.11619) | [Open](resources/lesion.md) |
| mmRV-v1 | Fundus-OCTA vessel correspondence benchmark. | [Paper](https://arxiv.org/abs/2203.03631) | [Open](resources/mmrv_v1.md) |
| Open_BUA_AV | Open artery-vein classification resource. | [GitHub](https://github.com/TwistedW/MIAV) | [Open](resources/open_bua_av.md) |
| RAVIR_AV_seg | Retinal artery-vein segmentation benchmark. | [Official Page](https://ravirdataset.github.io/data/) | [Open](resources/ravir_av_seg.md) |
| retinal | Retinal vessel segmentation and tree analysis benchmark. | [Official Page](https://reta-benchmark.org/) | [Open](resources/retinal.md) |
| Retinal Tortuosity | Retinal vessel tortuosity analysis dataset. | [Official Page](https://bioimlab.dei.unipd.it/Retinal%20Vessel%20Tortuosity.htm) | [Open](resources/retinal_tortuosity.md) |
| ROSE | Compact OCTA vessel segmentation benchmark. | [Paper](https://arxiv.org/abs/2007.05201) | [Open](resources/rose.md) |
| RVD_VIDEO | Video-based retinal dataset from handheld acquisition. | [Paper](https://arxiv.org/abs/2307.06577) | [Open](resources/rvd_video.md) |
| Seg_leakage | Fluorescein leakage segmentation dataset. | [Official Page](https://people.duke.edu/~sf59/Rabbani_IOVS_2014_dataset.htm) | [Open](resources/seg_leakage.md) |
| SNP_Segmentation | Corneal nerve structure segmentation benchmark. | [Official Page](https://people.duke.edu/~sf59/Zemborain_SNP_Net.htm) | [Open](resources/snp_segmentation.md) |
| STARE | Classic color fundus vessel segmentation benchmark. | [Paper](https://arxiv.org/abs/2009.12053) | [Open](resources/stare.md) |
| Tree_topology_PAMI_2015 | Retinal vessel tree topology benchmark. | [Official Page](https://people.duke.edu/~sf59/Estrada_PAMI_2015_dataset.htm) | [Open](resources/tree_topology_pami_2015.md) |
| UT-FSOCTA | FS-OCTA benchmark for vascular map generation. | [Zenodo](https://zenodo.org/records/6476639) | [Open](resources/ut_fsocta.md) |

</details>

<a id="ioct"></a>
<details>
<summary><strong>iOCT</strong> · 1 dataset · intraoperative OCT references</summary>

Intraoperative OCT and closely related surgical OCT references.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| iOCT | Intraoperative OCT set for vitreoretinal disease analysis. | [Paper](https://pubmed.ncbi.nlm.nih.gov/26265908/) | [Open](resources/ioct.md) |

</details>

<a id="longitudinal"></a>
<details>
<summary><strong>Longitudinal</strong> · 2 datasets · follow-up, repeated-visit, and progression-style resources</summary>

Datasets designed for sequential follow-up, progression analysis, or repeated-visit study.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| OLIVES | Longitudinal OCT treatment-response dataset with repeated visits. | [Paper](https://arxiv.org/abs/2209.11195) | [Open](resources/olives.md) |
| SIGF-database | Sequential fundus dataset for glaucoma forecasting. | [Official Page](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_60) | [Open](resources/sigf_database.md) |

</details>

<a id="registration"></a>
<details>
<summary><strong>Registration</strong> · 3 datasets · retinal registration and correspondence datasets</summary>

Resources commonly used for retinal image registration and correspondence evaluation.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| FIMD | Myopia fundus control-point registration benchmark. | [IEEE DataPort](https://ieee-dataport.org/documents/fundus-image-myopia-development-fimd-dataset) | [Open](resources/fimd.md) |
| FIRE | Classic fundus image registration benchmark. | [Official Page](https://projects.ics.forth.gr/cvrl/fire/) | [Open](resources/fire.md) |
| VARPA_r2 | Retinal registration benchmark from the VARPA set. | [Official Page](http://www.varpa.es/research/biometrics.html) | [Open](resources/varpa_r2.md) |

</details>

<a id="octa"></a>
<details>
<summary><strong>OCTA</strong> · 2 datasets · OCTA vascular and quality benchmarking resources</summary>

Optical coherence tomography angiography datasets and OCTA-specific quality or FAZ benchmarks.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| OCTA-500 | Large paired OCT/OCTA benchmark with structural and vascular data. | [IEEE DataPort](https://ieee-dataport.org/open-access/octa-500) | [Open](resources/octa500.md) |
| quality_assessment | OCTA quality assessment and FAZ segmentation dataset. | [Official Page](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4073651) | [Open](resources/quality_assessment.md) |

</details>

<a id="oct"></a>
<details>
<summary><strong>OCT</strong> · 12 datasets · OCT classification, structural analysis, and lesion segmentation resources</summary>

Retinal OCT datasets spanning classification, structural analysis, and lesion segmentation.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| 2014_BOE_Srinivasan | Retinal OCT classification benchmark from Srinivasan et al. | [Paper](https://ieeexplore.ieee.org/document/9190742) | [Open](resources/d_2014_boe_srinivasan.md) |
| 2015_BOE_Chiu2 | Retinal OCT layer segmentation benchmark. | [Official Page](https://people.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm) | [Open](resources/d_2015_boe_chiu2.md) |
| 8kt969dhx6-1 | Large OCT B-scan dataset with CNV, drusen, and normal cases. | [Mendeley Data](https://data.mendeley.com/datasets/8kt969dhx6/1) | [Open](resources/d_8kt969dhx6_1.md) |
| archive | Bundled OCT archive collecting several classic sets. | [Official Page](https://www.kaggle.com/datasets/kmader/eye-oct-datasets) | [Open](resources/archive.md) |
| Data on OCT and Fundus Images | Paired OCT and fundus collection for healthy and glaucomatous eyes. | [Mendeley Data](https://data.mendeley.com/datasets/2rnnz5nz74/2) | [Open](resources/data_on_oct_and_fundus_images.md) |
| OCT2017.tar | Classic four-class retinal OCT classification benchmark. | [Mendeley Data](https://data.mendeley.com/datasets/rscbjbr9sj/1) | [Open](resources/oct2017.md) |
| OCT_Manual_Delineations-2018_June_29 | Retinal OCT delineation set for healthy controls and multiple sclerosis. | [Official Page](https://iacl.ece.jhu.edu/index.php?title=Main_Page) | [Open](resources/oct_manual_delineations_2018_june_29.md) |
| OCTDL | High-resolution OCT dataset across multiple pathologies. | [Paper](https://arxiv.org/abs/2312.08255) | [Open](resources/octdl.md) |
| OCTIRD | Retinal OCT disease recognition dataset. | [Official Page](https://www.openicpsr.org/openicpsr/project/108503/version/V1/view?path=/openicpsr/108503/fcr:versions/V1&type=project) | [Open](resources/octird.md) |
| octlayerdataverse_files | OCT pathology dataset from the OCTID Dataverse release. | [Official Page](https://borealisdata.ca/dataverse/OCTID) | [Open](resources/octlayerdataverse_files.md) |
| THOCT1800 | Preprocessed SD-OCT benchmark for AMD, DME, and normal scans. | [GitHub](https://github.com/SJD095/OCT-Segmentation) | [Open](resources/thoct1800.md) |
| ZhangLabData | OCT benchmark popularized by the Kermany Cell release. | [Paper](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5) | [Open](resources/zhanglabdata.md) |

</details>

<a id="additional_curated"></a>
<details>
<summary><strong>Additional Curated</strong> · 3 datasets · extra public entries added beyond the imported reference list</summary>

Additional public entries already curated in this repository beyond the imported reference list.

| Dataset | Snapshot | Official | Profile |
| --- | --- | --- | --- |
| MMRDR | Multimodal DR benchmark spanning CFP, OCT, and UWF imaging. | [Nature](https://www.nature.com/articles/s41597-026-07005-9) | [Open](resources/mmrdr.md) |
| MultiEYE | Training-time multimodal benchmark with fundus-only inference. | [GitHub](https://github.com/xmed-lab/MultiEYE) | [Open](resources/multieye.md) |
| Open Ultrawidefield Fundus Dataset | Public UWF fundus dataset with diagnosis and quality labels. | [Nature](https://www.nature.com/articles/s41597-024-04113-2) | [Open](resources/open_uwf_fundus.md) |

</details>

---

## Directory Links

- [All dataset profiles](resources/README.md)
- [Tag search hub](tags/README.md)
- [Browse by modality](tags/modality.md)
- [Browse by task](tags/task.md)
- [Browse by disease / target](tags/disease_target.md)
- [Browse by input signal](tags/input_signal.md)
- [Browse by label form](tags/label_form.md)
- [Browse by property](tags/property.md)
