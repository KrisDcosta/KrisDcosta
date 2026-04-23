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
publications. One granted patent. Currently graduate researcher at MOSAIC Lab, UCSD.

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

### [RL Agent → NPU Deployment: CartPole PPO](https://github.com/KrisDcosta/cart-pole-ppo)
PPO agent in PyTorch exported via ONNX to Qualcomm AI Hub for NPU inference on Snapdragon.
Real-time web visualization. Full test suite. Docker containerized.

`PyTorch` `ONNX` `Qualcomm AI Hub` `Docker`

---

### [Coastal Flood Prediction: OOD ML Pipeline](https://github.com/KrisDcosta/coastal-flood-ml)
ML competition — predict coastal flooding across 12 stations with OOD generalization as the
core challenge. Modular `src/` pipeline with SQL feature engineering, fixed seeds, MCC metric.

`Python` `XGBoost` `SQL` `scikit-learn`

---

### [ARMD-NetX: Multimodal Retinal Disease Classification](https://github.com/KrisDcosta/armd-netx)
Curated and published a unified multimodal retinal dataset (~4,700 images, 8 sources) on Kaggle.
Two-stage ensemble: CNN + transfer learning + meta-learner soft voting.

- OCT: 95% F1 / 0.997 AUC &nbsp;·&nbsp; Fundus: 98% F1 / 0.999 AUC
- Accepted: IEEE ICCCNT 2025

`Python` `TensorFlow` `OpenCV` `Kaggle`

---

### [Recipe Recommender: Time-Aware Collaborative Filtering](https://github.com/KrisDcosta/recipe-recommender-cf)
Rebuilt a broken evaluation benchmark on 1.1M Food.com interactions. Time-aware matrix
factorization with bias terms to model 18-year rating drift. Best model RMSE: 0.69.

`Python` `Pandas` `scikit-learn`

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
| 2024 | Enhancing Bone Fracture Detection: A Comparative Study with VGG16+CNN Hybrid Architecture | IEEE ICCC 2024 |
| 2024 | DoppelScan | Indian Patent Office (Granted) |

---

## Skills

**ML/AI:** PyTorch · TensorFlow · scikit-learn · ONNX · llama.cpp · Transformers  
**Languages:** Python · Java · SQL · JavaScript  
**Systems:** Android (Java/Kotlin) · Flask · Docker · ADB  
**Cloud:** AWS · GCP · Databricks  
**Tools:** Git · HuggingFace · Kaggle · OpenCV
