<h1 align="center">Kris Dcosta</h1>

<p align="center">
  MS Data Science · UC San Diego &nbsp;|&nbsp; GPA 4.0
  <br/>
  Applied ML &nbsp;·&nbsp; Inference Optimization &nbsp;·&nbsp; On-Device AI
</p>

<p align="center">
  <a href="https://linkedin.com/in/kris-dcosta">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://huggingface.co/krisdcosta">HuggingFace</a> &nbsp;·&nbsp;
  <a href="mailto:kdcosta@ucsd.edu">kdcosta@ucsd.edu</a>
</p>

---

## What I work on

I build ML systems end-to-end — from research and experimentation to deployment on
real hardware. My work spans model evaluation, inference optimization, data pipelines,
and on-device AI across mobile, x86, and GPU targets.

Previously: 1.5 years at IIT Bombay's Vision & Image Processing Lab. Three IEEE
publications. One published patent. Currently graduate researcher at MOSAIC Lab, UCSD.

---

## Projects

### [Edge LLM Benchmarking: Cross-Device GGUF Quantization](https://github.com/KrisDcosta/edge-llm-bench)
Reproducible benchmarking framework for 7 GGUF variants of Llama 3.2 3B and Qwen 2.5 1.5B
across Pixel 6a (ARM), Intel x86, and Apple M4 (Metal GPU).

- Thermal isolation protocol reduced trial variance from ±8% → ±2%
- Q2_K runs 112% faster than Q6_K on ARM; Metal GPU reverses the ranking entirely
- Modeled KV-cache throughput cliff; predicted x86 collapse within 8%
- Published dataset on HuggingFace · Live interactive dashboard with CI/CD

**[→ Dashboard](https://krisdcosta.github.io/edge-llm-bench/) &nbsp;·&nbsp;
[→ Dataset](https://huggingface.co/datasets/krisdcosta/edge-llm-bench)**

`Python` `llama.cpp` `ADB` `CI/CD`

---

### [Recipe Recommender: Time-Aware Collaborative Filtering](https://github.com/KrisDcosta/recipe-recommender-system)
Production-grade recommender system on 1.1M Food.com interactions. Time-aware matrix
factorization with bias terms to model 18-year rating drift. Deployed as a REST API
with semantic search and full MLOps stack.

- RMSE 0.68 &nbsp;·&nbsp; NDCG@10 0.23
- FastAPI + FAISS vector search · Deployed on Google Cloud Run
- 162 tests · CI/CD pipeline · Docker containerized

`Python` `FastAPI` `FAISS` `scikit-learn` `Docker` `GCP`

---

### Qualcomm AI Workshops *(coming soon)*
On-device AI projects: RL agent NPU deployment (CartPole PPO → ONNX → Snapdragon),
agentic inference, and an additional project in progress. Full repo public later this month.

`PyTorch` `ONNX` `Qualcomm AI Hub` `Docker`

---

### [Coastal Flood Prediction: OOD ML Pipeline](https://github.com/KrisDcosta/coastal-flood-ml)
ML competition — predict coastal flooding across 12 tide gauge stations with OOD generalization
as the core challenge. Trained on 9 stations, evaluated on 3 unseen. Modular `src/` pipeline
with SQL feature engineering, fixed seeds, MCC primary metric.

`Python` `XGBoost` `SQL` `scikit-learn`

---

### [ARMD-NetX: Multimodal Retinal Disease Classification](https://github.com/KrisDcosta/armd-netx)
Curated and published a unified multimodal retinal dataset (~4,700 images, 8 sources) on Kaggle.
Two-stage ensemble: custom CNN + transfer learning (ResNet50, VGG16, EfficientNetB0, DenseNet121)
+ logistic regression meta-learner.

- OCT: **99.41% accuracy** &nbsp;·&nbsp; Fundus: **97.70% accuracy**
- Dataset DOI: [10.34740/kaggle/ds/7394927](https://doi.org/10.34740/kaggle/ds/7394927)
- Accepted: IEEE ICCCNT 2025

`Python` `TensorFlow` `OpenCV` `Kaggle`

---

### [DataHacks 2025](https://github.com/hannahmypham/DataHacks) *(contributor)*
Hackathon project built on AWS and Databricks. Contributed SnapTrash — a geospatial feature
for crowdsourced waste mapping with location-tagged image classification.

`AWS` `Databricks` `Python`

---

## Research & Publications

| Year | Title | Venue |
|------|-------|-------|
| 2025 | ARMD-NetX: Multimodal Retinal Disease Classification | IEEE ICCCNT 2025 |
| 2025 | Low-Cost Portable Biometric Attendance System Using R307 Fingerprint Scanner Integrated with Raspberry Pi Pico W | INOACC 2025 |
| 2025 | Enhancing Bone Fracture Detection: A Comparative Study with VGG16+CNN Hybrid Architecture | IEEE ICCC 2025 · [DOI: 10.1109/ICCC64910.2025.11077288](https://doi.org/10.1109/ICCC64910.2025.11077288) |
| 2024 | DoppelScan | Indian Patent Office (Published) |

---

## Skills

**ML/AI:** PyTorch · TensorFlow · scikit-learn · ONNX · llama.cpp · Transformers  
**Languages:** Python · Java · SQL · JavaScript  
**Systems:** Android (Java/Kotlin) · Flask · Docker · ADB  
**Cloud:** AWS · GCP · Databricks  
**Tools:** Git · HuggingFace · Kaggle · OpenCV
