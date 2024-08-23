# Medical-imaging-data-sets
- **内容简介**:汇集了不同类型的医学成像相关的数据集，每一个数据集都有相关的介绍和下载地址处。
- **主要分为以下几个大类：**
  - 一. QA类型与语言类型的数据集
  - 二. 医学图像类数据集
  - 三. Captioning dataset（The task is to write a long caption or report given one or a set of images.）
  - 四. 集合多种数据集类型的数据集
  - 五. 专门针对一个部位/器官的数据集
___________________________________________
## 一. QA类型与语言类型的数据集:

### （1）Chat-Doctor（Yunxiang et al. 2023）的数据集
- **Chat-Doctor模型简介：**
  - 官方介绍：A Medical Chat Model Fine-Tuned on a Large Language Model Meta-AI (LLaMA) Using Medical Domain Knowledge
  - 论文中提及的运用介绍：ChatDoctor is a monolingual medical LLM based on LLaMA and further fine-tuned, leverages 100,000 real-world patient-doctor dialogues in English, marking it as a distinct medical LLM. We employ the 7B parameter model, applying a fine-tuning evaluation framework.
- **模型涵盖的内容：**
  - Autonomous ChatDoctor with Disease Database Demo.
  - 100k real conversations between patients and doctors from HealthCareMagic.com HealthCareMagic-100k.
  - Real conversations between patients and doctors from icliniq.com icliniq-10k.
  - Checkpoints of ChatDoctor.
  - Stanford Alpaca data for basic conversational capabilities. 
- **模型中的数据集下载地址：**
  - InstructorDoctor-5K：https://drive.google.com/file/d/1nDTKZ3wZbZWTkFMBkxlamrzbNz0frugg/view
  - InstructorDoctor-200k：https://drive.google.com/file/d/1lyfqIwlLSClhgrCutWuEe_IACNq6XNUt/view

### （2）PubMedQA（Jin 等人，2019 年）
- **数据集官方简介：**
  - A Dataset for Biomedical Research Question Answering
  - PubMedQA has 1k expert labeled, 61.2k unlabeled and 211.3k artificially generated QA instances
- **数据集摘要：**
  The task of PubMedQA is to answer research questions with yes/no/maybe (e.g.: Do preoperative statins reduce atrial fibrillation after coronary artery bypass grafting?) using the corresponding abstracts.
- **数据集下载地址：**
  https://github.com/pubmedqa/pubmedqa

### （3）MedMCQA（Pal, Umapathi 等人，2022 年）
- **数据集官方简介：**
  A large-scale (194k), Multiple-Choice Question Answering (MCQA) dataset designed to address realworld medical entrance exam questions.
- **数据集摘要：**
  - MedMCQA has more than 194k high-quality AIIMS & NEET PG entrance exam MCQs covering 2.4k healthcare topics and 21 medical subjects are collected with an average token length of 12.77 and high topical diversity.
  - The dataset contains questions about the following topics: Anesthesia、Anatomy、Biochemistry、Dental、ENT、Forensic Medicine (FM)、Obstetrics and Gynecology (O&G)、Medicine、Microbiology、Ophthalmology、Orthopedics、Pathology、Pediatric、Pharmacology、Physiology、Psychiatry、Radiology、Skin、Preventive & Social Medicine (PSM)、Surgery.
- **数据集下载地址：**
   https://drive.google.com/uc?export=download&id=15VkJdq5eyWIkfb_aoD3oS8i4tScbHYky

### （4）HEAD-QA
- **数据集官方简介：**
  A Healthcare Dataset for Complex Reasoning.
- **数据集摘要：**
  HEAD-QA is a multi-choice HEAlthcare Dataset. The questions come from exams to access a specialized position in the Spanish healthcare system, and are challenging even for highly specialized humans. They are designed by the Ministerio de Sanidad, Consumo y Bienestar Social, who also provides direct access to the exams of the last 5 years (in Spanish).
- **数据集下载地址：**
https://huggingface.co/datasets/dvilares/head_qa

### （5）PMC-VQA
- **数据集官方简介：**
  PMC-VQA is a large-scale medical visual question-answering dataset, which contains 227k VQA pairs of 149k images that cover various modalities or diseases.
- **数据集下载地址：**
  https://huggingface.co/datasets/xmcmic/PMC-VQA

### （6）VQA-RAD (Visual Question Answering in Radiology)
- **数据集官方简介：**
  VQA-RAD consists of 3,515 question–answer pairs on 315 radiology images.
- **数据集下载地址：**
  https://huggingface.co/datasets/flaviagiammarino/vqa-rad

### （7）ScanQA模型的数据集
- **模型的官方简介：**
  3D Question Answering for Spatial Scene Understanding
- **模型的官方摘要：**
  We propose a new 3D spatial understanding task for 3D question answering (3D-QA). In the 3D-QA task, models receive visual information from the entire 3D scene of a rich RGB-D indoor scan and answer given textual questions about the 3D scene. 
- **模型数据的集官方摘要：**
  Our new ScanQA dataset contains over 41k question-answer pairs from 800 indoor scenes obtained from the ScanNet dataset. 
- **模型的数据集下载地址：**
  https://drive.google.com/drive/folders/1-21A3TBE0QuofEwDg5oDz2z0HEdbVgL2 
  （数据集使用教程地址：https://github.com/ATR-DBI/ScanQA/blob/main/docs/dataset.md）

### （8）FrenchMedMCQA
- **数据集官方简介：**
  FrenchMedMCQA is the first publicly available Multiple-Choice Question Answering (MCQA) dataset in French for medical domain. It is composed of 3,105 questions taken from real exams of the French medical specialization diploma in pharmacy, mixing single and multiple answers.
- **数据集下载地址：**
  https://huggingface.co/datasets/qanastek/frenchmedmcqa

### （9）MMedC
- **数据集官方简介：**
  A multilingual medical corpus with 25.5 billion tokens.
- **数据集下载地址：**
  https://huggingface.co/datasets/Henrychur/MMedC

### （10）Medical Meadow
- **数据集官方简介：**
  Medical Meadow currently encompasses roughly 1.5 million data points across a diverse range of tasks, including openly curated medical data transformed into Q/A pairs with OpenAI's and a collection of established NLP tasks in the medical domain. 
- **数据集下载地址：**
  https://huggingface.co/datasets/medalpaca/medical_meadow_medqa

### （11）CulturaX
- **数据集摘要：**
  We present CulturaX, a substantial multilingual dataset with 6.3 trillion tokens in 167 languages, tailored for large language model (LLM) development. Our dataset undergoes meticulous cleaning and deduplication through a rigorous pipeline of multiple stages to accomplish the best quality for model training, including language identification, URL-based filtering, metric-based cleaning, document refinement, and data deduplication. We employ MinHash at document level to achieve fuzzy deduplication for the datasets in different languages. Our data cleaning framework includes diverse criteria and threshold selections, guided by extensive data samples, ensuring comprehensive noise filtering in various aspects.
- **数据集下载地址：**
  https://huggingface.co/datasets/uonlp/CulturaX

### （12）PMC-CaseReport
- **论文中对数据集的简介：**
  PMC-CaseReport is a filtered subset of PMC-Inline with around 103K case reports, where the doctors typically document the valuable clinical cases. In contrast to PMC-VQA , we keep background information of the patients to simulate the clinical diagnosis scenario, thus can be seen as a medical contextual VQA dataset.
- **数据集下载地址：**
  https://huggingface.co/datasets/chaoyi-wu/PMC-CaseReport

### （13）SLAKE
- **数据集官方简介：**
  SLAKE is an English-Chinese bilingual dataset consisting of 642 images and 14,028 question-answer pairs for training and testing Med-VQA systems.
- **数据集下载地址：**
  https://huggingface.co/datasets/BoKelvin/SLAKE

### （14）NLM-TB
- **数据集简介：**
  NLM-TB 是一个用于肺结核研究和管理的数据库，主要由美国国家医学图书馆（NLM）构建，旨在为健康专业人士和研究人员提供性和细节信息。该数据库收录了相关文献、数据以及其他材料，以支持结核病的预防、诊断和治疗。
- **数据集下载地址：（两个途径）**
  - https://openi.nlm.nih.gov/imgs/collections/NLM-MontgomeryCXRSet.zip
  - https://openi.nlm.nih.gov/imgs/collections/ChinaSet_AllFiles.zip
___________________________________________
## 二. 医学图像类数据集

### （1）QUILT-1M
- **论文中对数据集的介绍：**
  The Quilt1m dataset, which gathers pathology image-text pairs from four public sources: PubMed articles, LAION , OpenPath , and Youtube videos.
- **数据集摘要：**
  From YouTube, we curate Quilt: a large-scale vision-language dataset consisting of 768,826 image and text pairs. Quilt was automatically curated using a mixture of models, including large language models, handcrafted algorithms, human knowledge databases, and automatic speech recognition. In comparison, the most comprehensive datasets curated for histopathology amass only around 200K samples. We combine Quilt with datasets, from other sources, including Twitter, research papers, and the internet in general, to create an even larger dataset: Quilt-1M, with 1M paired image-text samples, marking it as the largest vision-language histopathology dataset to date.
- **数据集下载地址：**
  Two versions of the data can be accessed after agreeing to certain terms, protecting against further distribution of the dataset and committing to its specified research use.
  -  (Rescaled) On https://zenodo.org/records/8239942Zenodo you can access the dataset with all images resized to 512x512 px (36 Gb)
  -  (Full) To access the dataset with full-sized images via Google Drive, please request time-limited access through this form https://docs.google.com/forms/d/e/1FAIpQLSdSe06DIbPn71jA2rCxe_5tUPfyHhSH1Z7ZTJBxWM26cnpZFg/viewform (110 Gb)

### （2）MIMIC-CXR
- **论文中对数据集的简介：**
  MIMIC-CXR has chest X-ray scans from 227,835 studie.
- **数据集摘要：**
  The MIMIC Chest X-ray (MIMIC-CXR) Database v2.0.0 is a large publicly available dataset of chest radiographs in DICOM format with free-text radiology reports. The dataset contains 377,110 images corresponding to 227,835 radiographic studies performed at the Beth Israel Deaconess Medical Center in Boston, MA. The dataset is de-identified to satisfy the US Health Insurance Portability and Accountability Act of 1996 (HIPAA) Safe Harbor requirements. Protected health information (PHI) has been removed. The dataset is intended to support a wide body of research in medicine including image understanding, natural language processing, and decision support.
- **数据集下载地址：**
  https://physionet.org/content/mimic-cxr/2.1.0/

### （3）CT-RATE
- **数据集官方简介：**
  CT-RATE consists of 25,692 non-contrast chest CT volumes, expanded to 50,188 through various reconstructions, from 21,304 unique patients, along with corresponding radiology text reports, multi-abnormality labels, and metadata. 
- **数据集下载地址：**
  https://huggingface.co/datasets/ibrahimhamamci/CT-RATE

### （4）MMC4
- **数据集官方简介：**
  MultimodalC4 is a multimodal extension of c4 that interleaves millions of images with text.
- **数据集摘要：**
  We release mmc4, an augmentation of the popular text-only c4 corpus with images interleaved. We use a linear assignment algorithm to place images into longer bodies of text using CLIP features. mmc4 spans everyday topics like cooking, travel, techology, etc. A manual inspection of a random sample of documents shows that the images are, on average, relevant to the topic/content of the text, and, frequently specific to their assigned sentences. After filtering NSFW images, ads, etc., the corpus contains 585M images across 103M text documents interleaved with 43B English tokens.
- **数据集下载地址：**
  https://github.com/allenai/mmc4

### （5）VinDr-Mammo
- **数据集官方简介：**
  A large-scale benchmark dataset for computer-aided detection and diagnosis in full-field digital mammography.
- **数据集摘要：**
  Breast cancer is one of the most prevalent types of cancer and the leading type of cancer death. Mammography is the recommended imaging modality for periodic breast cancer screening. A few datasets have been published to develop computer-aided tools for mammography analysis. However, these datasets either have a limited sample size or consist of screen-film mammography (SFM), which have been replaced by full-field digital mammography (FFDM) in clinical practices. This project introduces a large-scale full-field digital mammography dataset of 5,000 four-view exams, which are double read by experienced mammographers to provide cancer assessment and breast density following the Breast Imaging Report and Data System (BI-RADS). Breast abnormalities that require further examination are also marked by bounding rectangles.
- **数据集下载地址：**
  https://physionet.org/content/vindr-mammo/1.0.0/

### （6）VinDr-SpineXR
- **数据集官方简介：**
  A large annotated medical image dataset for spinal lesions detection and classification from radiographs.
- **数据集摘要：**
  Radiographs are used as the most critical imaging tool for identifying spine anomalies in clinical practice. The evaluation of spinal bone lesions, however, is a challenging task for radiologists. To the best of our knowledge, no existing studies are devoted to developing and evaluating a comprehensive system for classifying and localizing multiple spine lesions from X-ray scans. The lack of large-scale spine X-ray datasets with high-quality images and human expert annotations is the key obstacle. To fill this gap, we introduce a large-scale annotated medical image dataset for spinal lesion detection and classification from radiographs. The dataset, called VinDr-SpineXR, contains 10,466 spine X-ray images from 5,000 studies, each of which is manually annotated with 13 types of abnormalities by an experienced radiologist with bounding boxes around abnormal findings. This is the largest dataset to date that provides radiologist's bounding-box annotations for developing supervised-learning algorithms for spine X-ray analysis.
- **数据集下载地址：**
  https://physionet.org/content/vindr-spinexr/1.0.0/

### （7）VinDr-PCXR
- **数据集官方简介：**
  An open, large-scale pediatric chest X-ray dataset for interpretation of common thoracic diseases
- **数据集摘要：**
  Computer-aided diagnosis systems in adult chest radiography (CXR) have recently achieved great success thanks to the availability of large-scale, annotated datasets and the advent of high-performance supervised learning algorithms. However, the development of diagnostic models for detecting and diagnosing pediatric diseases in CXR scans is undertaken due to the lack of high-quality physician-annotated datasets. To overcome this challenge, we introduce and release in this paper a new pediatric CXR dataset of 9,125 studies that were retrospectively collected from a major pediatric hospital in Vietnam between 2020-2021. Each scan was manually annotated by an experienced radiologist for the presence of 36 critical findings and 15 diseases. In particular, each abnormal finding was identified via a rectangle bounding box on the image. To the best of our knowledge, this is the first and largest pediatric CXR dataset containing lesion-level labels and image-level labels for multiple findings and diseases. For algorithm development, the dataset is divided into a training set of 7,728 and a test set of 1,397.
- **数据集下载地址：**
  https://physionet.org/content/vindr-pcxr/1.0.0/

### （8）RAD-ChestCT Dataset
- **数据集官方简介：**
  The RAD-ChestCT dataset is a large medical imaging dataset developed by Duke MD/PhD student Rachel Draelos during her Computer Science PhD supervised by Lawrence Carin. The full dataset includes 35,747 chest CT scans from 19,661 adult patients. This Zenodo repository contains an initial release of 3,630 chest CT scans, approximately 10% of the dataset. This dataset is of significant interest to the machine learning and medical imaging research communities.
- **数据集下载地址：**
  https://zenodo.org/records/6406114#.Ytl6OXbMLAQ

### （9）ChestX-ray dataset
- **数据集摘要：**
  ChestX-ray dataset comprises 112,120 frontal-view X-ray images of 30,805 unique patients with the text-mined fourteen disease image labels (where each image can have multi-labels), mined from the associated radiological reports using natural language processing. Fourteen common thoracic pathologies include Atelectasis, Consolidation, Infiltration, Pneumothorax, Edema, Emphysema, Fibrosis, Effusion, Pneumonia, Pleural_thickening, Cardiomegaly, Nodule, Mass and Hernia, which is an extension of the 8 common disease patterns listed in our CVPR2017 paper.
- **数据集下载地址：（有两个途径）**
  - https://huggingface.co/datasets/alkzar90/NIH-Chest-X-ray-dataset
  - https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345

### （10）LIDC-IDRI
- **数据集官方简介：**
  - The Lung Image Database Consortium image collection (LIDC-IDRI) consists of diagnostic and lung cancer screening thoracic computed tomography (CT) scans with marked-up annotated lesions.
  - Seven academic centers and eight medical imaging companies collaborated to create this data set which contains 1018 cases.  Each subject includes images from a clinical thoracic CT scan and an associated XML file that records the results of a two-phase image annotation process performed by four experienced thoracic radiologists. 
- **数据集下载地址：**
  https://www.cancerimagingarchive.net/collection/lidc-idri/

### （11）COVIDx CXR-4
- **数据集官方简介：**
  An Expanded Multi-Institutional Open-Source Benchmark Dataset for Chest X-ray Image-Based Computer-Aided COVID-19 Diagnostics.
- **数据集摘要：**
  - An expanded multi-institutional open-source benchmark dataset for chest X-ray image-based computer-aided COVID-19 diagnostics. 
  - COVIDx CXR-4 expands significantly on the previous COVIDx CXR-3 dataset by increasing the total patient cohort size by greater than 2.66 times, resulting in 84,818 images from 45,342 patients across multiple institutions.
- **数据集下载地址：**
  https://www.kaggle.com/datasets/andyczhao/covidx-cxr2
  
### （12）PadChest
- **数据集官方简介：**
  一个大型胸部 X 射线成像数据集，带有多标签注释报告
- **数据集摘要：**
  - 这是一个大规模、高分辨率的胸部 X 射线标记数据集，用于自动化医学图像探索及其相关报告。该数据集包括 2009 年至 2017 年圣胡安医院放射科医生对 67,000 名患者的 160,000 多张图像进行解释和报告，涵盖六种不同的位置视图以及有关图像采集和患者人口统计学的其他信息。
  - 报告标有 174 种不同的放射学发现、19 种鉴别诊断和 104 个解剖位置，这些位置组织为映射到标准统一医学语言系统 （UMLS） 术语的分层分类法。大约27%的报告是由训练有素的临床医生手动注释的，其余的报告集是使用基于具有注意力机制的递归神经网络的监督方法进行标记的。生成的标签经过验证，使用独立测试套件获得 0.93 Micro-F1 的分数。
- **数据集下载地址：**
  https://bimcv.cipf.es/bimcv-projects/padchest/
  
### （13）ChestX-Det 
- **数据集官方简介：**
  - ChestX-Det consists of 3578 images from NIH ChestX-14. We invite three board-certified radiologists to annotate them with 13 common categories of diseases or abnormalities.
  - The 13 categories are Atelectasis, Calcification, Cardiomegaly, Consolidation, Diffuse Nodule, Effusion, Emphysema, Fibrosis, Fracture, Mass, Nodule, Pleural Thickening, Pneumothorax.
- **数据集下载地址：**
  https://github.com/Deepwise-AILab/ChestX-Det-Dataset?tab=readme-ov-file

### （14）VinDr-CXR
- **数据集官方简介：**
  An open dataset of chest X-rays with radiologist annotations.
- **数据集摘要：**
  We describe here a dataset of more than 100,000 chest X-ray scans that were retrospectively collected from two major hospitals in Vietnam. Out of this raw data, we release 18,000 images that were manually annotated by a total of 17 experienced radiologists with 22 local labels of rectangles surrounding abnormalities and 6 global labels of suspected diseases. The released dataset is divided into a training set of 15,000 and a test set of 3,000. Each scan in the training set was independently labeled by 3 radiologists, while each scan in the test set was labeled by the consensus of 5 radiologists. All images are in DICOM format and the labels from training and test sets are made publicly available.
- **数据集下载地址：**
  https://physionet.org/content/vindr-cxr/1.0.0/

### （15）Medical Segmentation Decathlon
- **数据集官方简介：**
  The Medical Segmentation Decathlon is a collection of medical image segmentation datasets. It contains a total of 2,633 three-dimensional images collected across multiple anatomies of interest, multiple modalities and multiple sources. Specifically, it contains data for the following body organs or parts: Brain, Heart, Liver, Hippocampus, Prostate, Lung, Pancreas, Hepatic Vessel, Spleen and Colon.
- **数据集下载地址：**
  http://medicaldecathlon.com/

### （16）FUMPE
- **数据集官方简介：**
  FUMPE consists of computed-tomography angiography (CTA) images for pulmonary embolism (PE) of 35 different patients. Annotations were made by two radiologist experts, proving the ground-truth with the aid of a semi-automated image-processing software tool.
- **数据集下载地址：**
  https://www.kaggle.com/datasets/andrewmvd/pulmonary-embolism-in-ct-images

### （17）AbdomenCT-1K
- **数据集官方简介：**
  We present a large and diverse abdominal CT organ segmentation dataset, termed AbdomenCT-1K, with more than 1000 (1K) CT scans from 12 medical centers, including multi-phase, multi-vendor, and multi-disease cases.
- **数据集下载地址：**
  https://docs.google.com/forms/d/e/1FAIpQLSeuZ3yanPc0E-SxvYD2ZX8eu-BKxxdQT5GQUpyzfUeK39ytow/viewform

### （18）ATLAS Data
- **数据集包含内容：**
  - 955 T1-weighted MRI scans, divided into a training dataset (n=655 T1w MRIs with manually-segmented lesion masks) and a test dataset (n=300 T1w MRIs only; lesion masks not released)
  - MNI152 standard-space T1-weighted average structural template image
  - Two .csv files containing lesion and scanner metadata
- **数据集下载地址：**
  https://fcon_1000.projects.nitrc.org/indi/retro/atlas_download.html

### （19）FDG-PET-CT-Lesions【该数据集主要为图像（419GB左右），还有1.34MB的临床数据】
- **数据集官方介绍：**
  501 consecutive whole body FDG-PET/CT data sets of patients with malignant lymphoma, melanoma and non small cell lung cancer (NSCLC) as well as 513 data sets without PET-positive malignant lesions (negative controls) examined between 2014 and 2018 at the University Hospital Tübingen were included. All examinations were acquired on a single, state-of-the-art PET/CT scanner (Siemens Biograph mCT). The imaging protocol consists of a diagnostic CT scan (mainly from skull base to mid-thigh level) with intravenous contrast enhancement in most cases, except for patients with contraindications. The following CT parameters were used: reference dose of 200 mAs, tube voltage of 120 kV, iterative reconstruction with a slice thickness of 2 - 3 mm. In addition, a whole-body FDG-PET scan was acquired 60 minutes after I.V. injection of 300-350 MBq 18F-FDG. PET data were reconstructed using an ordered-subset expectation maximization (OSEM) algorithm with 21 subsets and 2 iterations and a gaussian kernel of 2 mm and a matrix size of 400 x 400.
- **数据集下载地址：**
  https://www.cancerimagingarchive.net/collection/fdg-pet-ct-lesions/

### （20）CT-ORG
- **数据集官方简介：**
  CT volumes with multiple organ segmentations
- **数据集摘要：**
  - This dataset consists of 140 computed tomography (CT) scans, each with five organs labeled in 3D: lung, bones, liver, kidneys and bladder. The brain is also labeled on the minority of scans which show it.
  - The images come from a wide variety of sources, including abdominal and full-body; contrast and non-contrast; low-dose and high-dose CT scans. 131 images are dedicated CTs, the remaining 9 are the CT component taken from PET-CT exams. 
  - The data are divided into a testing set of 21 CT scans, and a training set of the remaining 119.
- **数据集下载地址：**
  https://www.cancerimagingarchive.net/collection/ct-org/

### （21）Pancreas CT
- **数据集官方简介：**
  The National Institutes of Health Clinical Center performed 82 abdominal contrast enhanced 3D CT scans (~70 seconds after intravenous contrast injection in portal-venous) from 53 male and 27 female subjects.  Seventeen of the subjects are healthy kidney donors scanned prior to nephrectomy.  The remaining 65 patients were selected by a radiologist from patients who neither had major abdominal pathologies nor pancreatic cancer lesions.  Subjects' ages range from 18 to 76 years with a mean age of 46.8 ± 16.7. The CT scans have resolutions of 512x512 pixels with varying pixel sizes and slice thickness between 1.5 − 2.5 mm, acquired on Philips and Siemens MDCT scanners (120 kVp tube voltage).
- **数据集下载地址：**
  https://www.cancerimagingarchive.net/collection/pancreas-ct/
___________________________________________

## 三. Captioning datasets（The task is to write a long caption or report given one or a set of images.）

### （1）MIMIC-CXR Database
- **数据集摘要：**
  The MIMIC Chest X-ray (MIMIC-CXR) Database v2.0.0 is a large publicly available dataset of chest radiographs in DICOM format with free-text radiology reports. The dataset contains 377,110 images corresponding to 227,835 radiographic studies performed at the Beth Israel Deaconess Medical Center in Boston, MA. The dataset is de-identified to satisfy the US Health Insurance Portability and Accountability Act of 1996 (HIPAA) Safe Harbor requirements. Protected health information (PHI) has been removed. The dataset is intended to support a wide body of research in medicine including image understanding, natural language processing, and decision support.
- **数据集下载地址：**
  https://physionet.org/content/mimic-cxr/2.1.0/

### （2）PMC-OA
- **论文中对数据集的介绍：**
  PMC-OA is a large-scale medical visual question-answering dataset, which contains 227k VQA pairs of 149k images that cover various modalities or diseases.
- **数据集下载地址：**
  https://huggingface.co/datasets/axiong/pmc_oa#pmc-oa-dataset
___________________________________________

## 四. 集合多种数据集类型的数据集

### （1）SAT-DS
- **数据集官方简介：**
  A medical data collection of 72 public segmentation datasets, contains over 22K 3D images, 302K segmentation masks and 497 classes from 3 different modalities (MRI, CT, PET) and 8 human body regions.
- **数据集下载地址：**
  https://github.com/zhaoziheng/SAT-DS

___________________________________________

## 五. 专门针对一个部位/器官的数据集

### （1）Amos
- **数据集官方简介：**
  - A large-scale abdominal multi-organ benchmark for versatile medical image segmentation
  - AMOS provides 500 CT and 100 MRI scans collected from multi-center, multi-vendor, multi-modality, multi-phase, multi-disease patients, each with voxel-level annotations of 15 abdominal organs, providing challenging examples and test-bed for studying robust segmentation algorithms under diverse targets and scenarios. 
- **数据集下载地址：**
  https://zenodo.org/records/7262581

### （2）Couinaud
- **数据集简介：**
  Couinaud数据集是一个在肝胆外科领域广泛使用的数据库，它包含了许多肝分区手术的病例信息，涉及患者的临床和病理数据。该数据集主要用于研究肝胆疾病患者的治疗方法选择和手术风险评估。
- **数据集下载地址：**
  https://github.com/GLCUnet/dataset

### （3）CTPelvic1K数据集
- **数据集简介：**
  CTPelvic1K是一个由7个来源组成的大型综合性骨盆CT数据集，包含了1,184组三维体积图像（约32万张切片）。这些源包括临床收集的数据以及多个公开可用的数据集，覆盖了无金属伪影和有金属伪影的骨折病例，肾和肾脏肿瘤分割任务，多器官分割，结肠癌瘤分割等多种医疗情境。
- **数据集下载地址：**
  https://zenodo.org/records/4588403#YEyLq
___________________________________________
