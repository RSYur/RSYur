<div align="center">

<img src="back.png" width="100%" alt="Monochrome octopus connecting medical imaging and neural data structures"/>

# Roman Yurovskikh

### Junior Research Fellow · Lead ML Engineer · Acting Head of the Laboratory of Mathematical Modeling

**Medical AI · Computer Vision · Robotic Surgery Analytics · Medical Imaging · Scientific Software**

<p>
  <a href="https://github.com/RSYur">
    <img src="https://img.shields.io/badge/GitHub-RSYur-111111?style=flat-square&logo=github&logoColor=white" alt="GitHub profile"/>
  </a>
  <a href="mailto:rsyurovskih@yandex.ru">
    <img src="https://img.shields.io/badge/Email-Contact-333333?style=flat-square&logo=maildotru&logoColor=white" alt="Email Roman Yurovskikh"/>
  </a>
  <img src="https://img.shields.io/badge/Ufa-Russia-555555?style=flat-square&logo=googlemaps&logoColor=white" alt="Ufa, Russia"/>
  <img src="https://img.shields.io/badge/Focus-Medical_AI-777777?style=flat-square" alt="Medical AI"/>
</p>

*From medical pixels, voxels and video streams to reproducible datasets,*<br>
*measurable signals and usable research software.*

**你好 · Привет · Hi**

[About](#about) ·
[Research](#research-focus) ·
[Projects](#selected-projects) ·
[Expertise](#expertise) ·
[Collaboration](#collaboration)

</div>

---

## About

<img src="face-avatar-bw.png" width="185" align="right" alt="Roman Yurovskikh"/>

I am a machine learning engineer and researcher working at the intersection of
**artificial intelligence, medicine, mathematical modeling and scientific
software engineering**.

At the **Laboratory of Mathematical Modeling, Bashkir State Medical University**,
I combine research, engineering and technical leadership. I design medical
computer-vision systems, coordinate multidisciplinary work with clinical experts,
develop reproducible experimental pipelines and turn research concepts into
auditable software.

My work covers the complete lifecycle of an applied medical AI system:

- formalizing clinical and scientific questions;
- medical data governance, de-identification and dataset design;
- annotation protocols and quality control;
- model development, independent benchmarking and error analysis;
- desktop, web and command-line research tools;
- quantitative visualization and structured reporting;
- technical specifications, validation protocols and scientific documentation.

I am especially interested in systems where a strong model metric is only the
beginning. The final result should be **measurable, reproducible, traceable,
interpretable and useful to a domain expert**.

<br clear="right"/>

### Кратко по-русски

Я разрабатываю интеллектуальные системы для анализа медицинских изображений,
видеоданных и биомедицинской информации. Основные направления — компьютерное
зрение в медицине, анализ робот-ассистированных операций, обработка КЛКТ и КТ,
сегментация анатомических структур, детекция, оценка ключевых точек, трекинг,
количественный анализ движений и создание воспроизводимого исследовательского ПО.

---

## Professional snapshot

| | |
|---|---|
| **Current roles** | Junior Research Fellow · Lead ML Engineer · Acting Head of Laboratory |
| **Primary domain** | Artificial intelligence in healthcare |
| **Core expertise** | Computer vision · Medical imaging · Surgical video analytics · Scientific software |
| **Research tasks** | Detection · Segmentation · Pose estimation · Tracking · Quantitative morphology |
| **Engineering focus** | Reproducible ML pipelines · Dataset versioning · Benchmarking · GUI/CLI tools |
| **Primary stack** | Python · PyTorch · MONAI · OpenCV · VTK · DICOM |
| **Education** | BSc in Mathematics and Computer Science · MSc candidate in Data Analysis and Computer Modeling |
| **Location** | Ufa, Russia |

---

## Research focus

### Surgical video intelligence

Transforming long robot-assisted surgery videos into structured and measurable
representations of instruments, surgical stages and motion:

- instrument detection and class recognition;
- tip, wrist and shaft keypoint estimation;
- temporal tracking and class stabilization;
- stage-aware video and dataset analysis;
- bimanual coordination and motion metrics;
- weak-fragment discovery and model-assisted annotation;
- model comparison on complete operations;
- auditable clip selection and expert-oriented reporting.

### Medical image analysis

| Modality | Research tasks |
|---|---|
| **Surgical video** | Detection, pose, tracking, stage analysis and motion metrics |
| **Dental CBCT / CT** | Tooth ROI analysis, tissue segmentation, morphology and 3D reconstruction |
| **Ultrasound** | Lesion localization, classification and quantitative analysis |
| **Coronary CT / angiography** | Centerline extraction, curvature, tortuosity and vessel morphology |
| **Genomic sequencing data** | Input validation, quality control and reproducible workflow orchestration |

### Scientific software engineering

I build maintainable research systems rather than isolated notebooks:

- modular Python packages and configuration-driven pipelines;
- local-first desktop applications and command-line tools;
- structured schemas, manifests and immutable identifiers;
- dataset and model registries;
- reproducible experiment runners and machine-readable reports;
- synchronized 2D/3D visualization;
- deterministic processing, audit logs and data lineage.

### Mathematical and computational modeling

My background also includes numerical simulation and scientific visualization of
ceramic sintering, multiparticle cold spray processes and biomedical geometry.
This work connects mathematical formalization, computational experiments,
performance-aware implementation and engineering interpretation.

---

## From clinical question to auditable software

```text
Clinical or scientific question
        ↓
System boundaries and measurable acceptance criteria
        ↓
Data governance · de-identification · dataset design
        ↓
Annotation protocol · quality control · versioned manifest
        ↓
Baseline model · controlled experiments · model registry
        ↓
Independent benchmark · calibration · error taxonomy
        ↓
Expert-oriented GUI / CLI · 2D and 3D visualization
        ↓
Structured report · expert review · scientific communication
```

The guiding principle is simple: every prediction, metric and derived artifact
should be traceable to its source data, configuration, model checkpoint and
evaluation protocol.

---

# Selected projects

## OpeLab / ML-Learn-DaVinci

**Robot-assisted surgical video analytics**

OpeLab is a research and engineering platform for extracting measurable
information from robot-assisted surgery video. It combines computer vision,
temporal analysis, dataset engineering, annotation tooling, quantitative motion
analysis and independent benchmarking.

**Core work**

- surgical instrument detection and class-aware evaluation;
- tip and wrist keypoint estimation;
- physically plausible temporal tracking;
- stage-aware clip selection from complete operations;
- bimanuality and coordination metrics;
- model-assisted annotation with human verification;
- versioned operation-level dataset splits;
- desktop software for annotation, analysis and reporting.

**Current engineering priorities**

- improving wrist-keypoint stability;
- reducing visually similar instrument class confusion;
- stabilizing temporal predictions;
- discovering weak fragments across full procedures;
- comparing checkpoints under one independent protocol;
- preserving reproducibility across seeds, environments and GPUs.

### Independent benchmark snapshot

The values below describe a specific research experiment on an independent real
test set. They are not clinical performance claims.

| Metric | Internal model | External baseline |
|---|---:|---:|
| Detection F1 | 0.5028 | 0.4872 |
| Macro F1 | 0.4963 | 0.3529 |
| PCK@0.05 overall | 0.8045 | 0.6375 |
| Keypoint RMSE | 99.7 px | 133.8 px |
| Tip PCK | 0.8189 | 0.9682 |
| Wrist PCK | 0.7901 | 0.3068 |
| Bounding-box IoU | 0.8351 | 0.6040 |

This comparison illustrates why a single aggregate score is insufficient: model
selection must reflect the downstream research question, individual instrument
classes and anatomy-aware keypoint quality.

**Stack:** `Python` · `PyTorch` · `YOLO Pose` · `OpenCV` · `Qt` · `DVC/MLflow concepts`

---

## OpeTrace / SIVERA-D

**Structured surgical data and research infrastructure**

OpeTrace is the data-management layer surrounding surgical video research.
SIVERA-D extends this direction into a software-analytical platform for
registering, structuring and analyzing minimally invasive surgical video.

The architecture connects:

```text
Operation → Video → Stage → Clip → Frame → Annotation → Prediction → Report
```

Key principles include immutable identifiers, privacy-aware metadata,
operation-level split control, annotation history, explicit dataset versions,
traceability from model output to source frame and export to standardized
training and benchmark formats.

**Stack:** `Python` · `Structured schemas` · `PostgreSQL` · `Local-first GUI` · `Audit logs`

---

## MorphiDentAI / Deep2Dent / ДентАналитика

**Dental CBCT analysis, tissue segmentation and 3D morphology**

This research software ecosystem transforms dental CBCT/CT studies into
tooth-centered visual and quantitative representations.

```text
DICOM / CBCT
    → study validation
    → tooth and ROI selection
    → preprocessing and tissue segmentation
    → post-processing and mesh generation
    → 2D/3D visualization
    → quantitative morphology
    → structured research report
```

Depending on the module and study design, the system can represent enamel,
dentin, pulp cavity, root canals, crown, roots, restoration material,
surrounding bone and regions associated with caries or restoration defects.

The engineering focus includes spatial metadata validation, orientation
normalization, multiplanar reconstruction, transparent tissue layers,
morphometric indicators and a clear distinction between model output and expert
conclusion.

**Stack:** `Python` · `PyTorch` · `MONAI` · `UNETR / U-Net` · `DICOM` · `VTK`

---

## ArtPiece / CoronaryCurvature

**Quantitative coronary artery geometry**

Research software for coronary centerline analysis, local and global curvature,
torsion, vessel length, tortuosity indices, inflection points and branch
geometry.

```text
CT / angiography
    → vessel segmentation
    → centerline extraction
    → smoothing and resampling
    → curvature and torsion
    → segment-level metrics
    → 3D validation and report
```

Special attention is given to voxel spacing, centerline noise, smoothing bias,
branch-point handling, stable curvature estimation and reproducible vessel
segment selection.

**Stack:** `Python` · `NumPy` · `SciPy` · `VTK` · `C++`

---

## RenVisio / KidneyTumorSearch

**Computer vision for kidney ultrasound**

A research direction focused on ultrasound quality control, kidney localization,
lesion candidate detection, classification, region-of-interest extraction,
confidence output and explainable visualization.

Research challenges include operator-dependent acquisition, variation in gain
and contrast, limited labeled datasets, class imbalance, calibration,
false-positive control and external validation.

**Stack:** `Python` · `OpenCV` · `PyTorch` · `MONAI` · `NumPy`

---

<details>
<summary><strong>More research and software projects</strong></summary>
<br>

### Model Benchmark V1

A framework-independent evaluation contour for comparing model families and
checkpoints under a single deterministic protocol. It includes model adapters,
one-to-one matching, class-aware metrics, checkpoint inspection, failure-case
export and structured reports.

### Automated assessment of abutment teeth

A research decision-support concept for quantitative assessment of potential
abutment teeth in dental bridge planning using CBCT-derived morphology,
bone-supported root surface, effective root length and interpretable geometric
indicators.

### Medical genomics pipeline

A local and reproducible tumor/normal/RNA sequencing workflow with strict input
validation, FASTQ quality control, checksums, resumable stages, deterministic
file naming, machine-readable summaries and container-ready environments.

### Medical LLM / RAG assistant

An evidence-aware architecture for controlled medical knowledge bases:
document ingestion, hybrid retrieval, context assembly, citation traceability,
access control, audit logs and hallucination-oriented evaluation.

### SimplySintering

Scientific desktop software for mathematical modeling and visualization of
ceramic sintering processes, including time-dependent simulation, parameter
comparison and 3D rendering.

### Cold Spray Multiparticle

Numerical and visual modeling of multiparticle cold-spray processes: particle
trajectories, impact conditions, particle–substrate interaction and engineering
interpretation.

### Additional prototypes

- automated footprint segmentation and geometric assessment;
- VR relaxation environment and interaction concept;
- educational projects in programming, data analysis and medical AI.

</details>

---

# Expertise

## Computer vision and medical imaging

`Object detection` · `Semantic segmentation` · `Instance segmentation` ·
`Pose estimation` · `Keypoints` · `Multi-object tracking` · `Temporal analysis` ·
`DICOM` · `CBCT / CT` · `Ultrasound` · `Surgical video` · `3D reconstruction` ·
`Mesh processing` · `Centerline geometry`

## Machine learning

`PyTorch` · `MONAI` · `YOLO` · `U-Net` · `UNETR` · `nnU-Net concepts` ·
`scikit-learn` · `TensorFlow / Keras` · `XGBoost` · `ONNX` · `TensorRT` ·
`Calibration` · `Ablation studies` · `Error analysis`

## Scientific computing and visualization

`NumPy` · `SciPy` · `Pandas` · `OpenCV` · `VTK` · `SimpleITK` · `Matplotlib` ·
`Plotly` · `Numerical modeling` · `2D/3D visualization`

## Software and data engineering

`Python 3.11+` · `C++` · `C#` · `R` · `Bash` · `SQL` · `Qt / PySide / PyQt` ·
`FastAPI` · `PostgreSQL` · `MongoDB` · `Redis` · `MinIO / S3` ·
`REST APIs` · `CLI applications` · `Desktop software`

## Reproducibility and infrastructure

`Git` · `GitHub Actions` · `Docker` · `MLflow` · `DVC` · `Dataset manifests` ·
`Model registries` · `Experiment configuration` · `CUDA / NVIDIA` ·
`Environment capture` · `Automated validation`

<details>
<summary><strong>Engineering principles</strong></summary>
<br>

- define the scientific question before selecting the model;
- split medical data by independent clinical case when leakage is possible;
- preserve fixed, independent evaluation data;
- change one experimental factor at a time whenever possible;
- version datasets, annotations, configurations and checkpoints;
- compare early and late checkpoints instead of trusting the final epoch;
- distinguish detection quality, matched-object keypoint quality and
  end-to-end system quality;
- inspect class-level, temporal and anatomy-aware errors;
- treat data selection as part of model development;
- keep research hypotheses separate from production or clinical claims;
- produce both machine-readable artifacts and expert-readable reports.

</details>

---

## Research leadership

As Acting Head of the Laboratory of Mathematical Modeling, my responsibilities
include:

- research and project portfolio planning;
- technical architecture and prioritization;
- translating clinical ideas into executable engineering stages;
- defining requirements, acceptance criteria and validation protocols;
- coordinating engineers, researchers and clinical experts;
- dataset and compute-resource planning;
- reviewing model-development plans and experimental results;
- standardizing documentation and reproducibility practices;
- mentoring junior developers and student research teams;
- preparing scientific, technical and software-registration materials.

My preferred working style is based on explicit boundaries, written decisions,
small controlled iterations, measurable acceptance criteria, honest error
analysis and maintainable systems.

---

## Education

<img src="u-logo-sign.png" width="76" align="left" alt="Ufa University of Science and Technology mark"/>

### Master of Science candidate

**Ufa University of Science and Technology**<br>
02.04.01 — Data Analysis and Computer Modeling<br>
2025–2027 · ongoing

<br clear="left"/>

<img src="u-logo-sign.png" width="76" align="left" alt="Ufa University of Science and Technology mark"/>

### Bachelor of Science

**Ufa University of Science and Technology**<br>
02.03.01 — Mathematics and Computer Science<br>
2021–2025

<br clear="left"/>

My academic foundation connects mathematics, algorithms, numerical methods,
probability, statistics, data analysis, computer modeling and scientific
computing.

---

## Selected registered software

| Software | Registration reference |
|---|---|
| **DEEP2DENT** | RU 2024688889 |
| **COLD SPRAY MULTIPARTICLE** | RU 2024668896 |
| **SIMPLY SINTERING** | RU 2023667644 |

---

# Collaboration

I am interested in research and engineering collaboration around:

- robot-assisted surgery video and surgical workflow understanding;
- instrument detection, pose estimation, tracking and motion analytics;
- dental CBCT, tissue segmentation and medical 3D reconstruction;
- quantitative vascular morphology and ultrasound computer vision;
- medical dataset governance and AI-assisted annotation;
- reproducible medical AI benchmarks;
- scientific desktop software and expert-oriented visualization;
- applied mathematics and computational modeling in biomedicine;
- international datasets, comparative validation and joint publications.

### What I can contribute

`Problem formalization` · `Technical specifications` · `Dataset protocols` ·
`ML baselines` · `Detection / segmentation / pose / tracking` ·
`Independent benchmarks` · `Error analysis` · `Scientific GUI` ·
`3D medical visualization` · `Quantitative metrics` ·
`Research documentation` · `Technical coordination`

<div align="center">

### Let’s connect

[GitHub](https://github.com/RSYur) ·
[Email](mailto:rsyurovskih@yandex.ru)

**Building auditable medical AI systems from data to decision-support software.**

<sub>Roman Yurovskikh · Ufa · 2026</sub>

</div>

---

> [!NOTE]
> Repositories and descriptions on this profile may contain research prototypes,
> experimental metrics, early-stage software and non-clinical validation.
> Unless explicitly stated otherwise, these systems are not certified medical
> devices and should not be interpreted as autonomous diagnostic tools.
