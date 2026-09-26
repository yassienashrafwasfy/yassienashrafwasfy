
# Yassien Wasfy

<img align="right" src="assets/ascii-art.png" width="240" alt="" />

**ML engineer from Cairo** working where models meet systems: implementing architectures, making them fast, and shipping them to production.

- 📖 Reading *Designing Data-Intensive Applications*, *Flunt-python*, *Fundamentals of Software Engineering*
- 📺 Enrolled *FastAPI Packet Course*
- 💬 Open to ML engineering and research roles, and freelance work

<a href="https://www.linkedin.com/in/yassien-wasfy-315ab5349"><img src="https://img.shields.io/badge/LinkedIn-161b22?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn" /></a>
<a href="https://kaggle.com/yassienwasfy"><img src="https://img.shields.io/badge/Kaggle-161b22?style=for-the-badge&logo=kaggle&logoColor=58a6ff" alt="Kaggle" /></a>
<a href="https://huggingface.co/masterofaudio2077"><img src="https://img.shields.io/badge/Hugging%20Face-161b22?style=for-the-badge&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" /></a>
<a href="mailto:yassienashraf2025@gmail.com"><img src="https://img.shields.io/badge/Email-161b22?style=for-the-badge&logo=gmail&logoColor=bc8cff" alt="Email" /></a>

<br clear="right" />

## Open source

**[keras-team/keras-hub](https://github.com/keras-team/keras-hub)** is Google's pretrained model library.

- Added the **BLIP-2** vision-language model ([#2699](https://github.com/keras-team/keras-hub/pull/2699)), with weight-conversion scripts and numerical-parity tests against OPT-2.7B/6.7B and Flan-T5-XL/XXL checkpoints.
- Added **KV caching** and a **Seq2SeqLM** task to T5 ([#2932](https://github.com/keras-team/keras-hub/pull/2932)), removing redundant recomputation during autoregressive decoding.
- Filed 15 issues across Keras, KerasHub and keras-io; maintainers fixed 5 of my 6 bug reports.

## Experience

**AI Engineer Intern** | Cegedim, Cairo, Egypt | Jul 2026 – Sep 2026

- Built **Octo**, a PII detection and masking pipeline combining an XLM-R model with rule-based detection that reached **98% recall** on QA documents, and integrated it into Chameleon, the company's masking software, for GDPR compliance.
- Built the shared masking engine all three team models run on, using PyMuPDF and ONNX Runtime to mask personal data in PDF and text files while keeping the original layout, with detectors for five countries' identifiers and a PP-OCRv6 fallback for scanned pages.
- Cut text processing time by **48%** and halved reference-data memory by profiling with Scalene and removing repeated file reads and per-document setup.
- Restructured the engine around rule tables and injected dependencies behind feature toggles, and added mutation testing that found gaps the passing test suite had hidden.
- Shipped to production via GitLab CI with blue/green releases, and helped build an MLflow + FastAPI setup that scored every team's model on the same synthetic data.

**Computer Vision Trainee** | NAID, New Capital, Egypt | Jul 2025 – Sep 2025

- Trained segmentation and object-detection models across the full ML lifecycle.
- Built a GAN-based model to denoise and reconstruct audio recorded in noisy environments.

## Toolkit

**Frameworks** &nbsp;
<img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=4584b6" alt="Python" />
<img src="https://img.shields.io/badge/JAX-161b22?style=flat-square&logo=google&logoColor=58a6ff" alt="JAX" />
<img src="https://img.shields.io/badge/Keras%203-161b22?style=flat-square&logo=keras&logoColor=FF4B4B" alt="Keras 3" />
<img src="https://img.shields.io/badge/TensorFlow-161b22?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" />
<img src="https://img.shields.io/badge/PyTorch-161b22?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
<img src="https://img.shields.io/badge/scikit--learn-161b22?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn" />

**Data** &nbsp;
<img src="https://img.shields.io/badge/NumPy-161b22?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy" />
<img src="https://img.shields.io/badge/Pandas-161b22?style=flat-square&logo=pandas&logoColor=F03FA0" alt="Pandas" />
<img src="https://img.shields.io/badge/Polars-161b22?style=flat-square&logo=polars&logoColor=CD792C" alt="Polars" />
<img src="https://img.shields.io/badge/Hugging%20Face-161b22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" />
<img src="https://img.shields.io/badge/Roboflow-161b22?style=flat-square&logo=roboflow&logoColor=A351FB" alt="Roboflow" />

**Training at scale** &nbsp;
<img src="https://img.shields.io/badge/TPU%20v5e--8-161b22?style=flat-square&logo=googlecloud&logoColor=4285F4" alt="TPU v5e-8" />
<img src="https://img.shields.io/badge/Multi--GPU-161b22?style=flat-square&logo=nvidia&logoColor=76B900" alt="Multi-GPU" />
<img src="https://img.shields.io/badge/Weights%20%26%20Biases-161b22?style=flat-square&logo=weightsandbiases&logoColor=FFBE00" alt="Weights and Biases" />
<img src="https://img.shields.io/badge/MLflow-161b22?style=flat-square&logo=mlflow&logoColor=0194E2" alt="MLflow" />
<img src="https://img.shields.io/badge/LoRA%20%2F%20QLoRA-161b22?style=flat-square&logoColor=bc8cff" alt="LoRA and QLoRA" />

**Deploy & optimize** &nbsp;
<img src="https://img.shields.io/badge/ONNX%20Runtime-161b22?style=flat-square&logo=onnx&logoColor=e6edf3" alt="ONNX Runtime" />
<img src="https://img.shields.io/badge/TensorRT-161b22?style=flat-square&logo=nvidia&logoColor=76B900" alt="TensorRT" />
<img src="https://img.shields.io/badge/Quantization-161b22?style=flat-square&logoColor=bc8cff" alt="Quantization" />
<img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
<img src="https://img.shields.io/badge/GitLab%20CI-161b22?style=flat-square&logo=gitlab&logoColor=FC6D26" alt="GitLab CI" />
<img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009485" alt="FastAPI" />
<img src="https://img.shields.io/badge/Gradio-161b22?style=flat-square&logo=gradio&logoColor=F97316" alt="Gradio" />
<img src="https://img.shields.io/badge/Streamlit-161b22?style=flat-square&logo=streamlit&logoColor=FF4B4B" alt="Streamlit" />
<img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
<img src="https://img.shields.io/badge/Linux-161b22?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
