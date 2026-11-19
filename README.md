<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img src="assets/banner-dark.svg" width="100%" alt="Yassien Wasfy. I fix and ship models, from Keras to vLLM.">
  </picture>
</p>

```python
from yassien import Engineer

me = Engineer(city="Cairo", works_on=["Keras", "ONNX", "vLLM", "FastAPI"])
me.ask("What do you do?")
# I port models into Keras, fix the serving stack under them (vLLM, ONNX,
# OpenVINO), and ship the result as FastAPI services that run in production.
```

AI engineer from Cairo working where models meet systems: architectures, speed, and production backends. Code merged into [Google's KerasHub](https://github.com/keras-team/keras-hub), [ONNX](https://github.com/onnx/onnx), [vLLM](https://github.com/vllm-project/vllm) and [Keras OpenVINO](https://github.com/keras-team/keras-openvino).

- 📖 Reading *Designing Data-Intensive Applications*, *Fluent Python*, *Fundamentals of Software Engineering*
- 💬 Open to junior AI and Python backend roles in Cairo, and to freelance work

<a href="https://www.linkedin.com/in/yassien-wasfy-315ab5349"><img src="https://img.shields.io/badge/LinkedIn-161b22?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn" /></a>
<a href="https://kaggle.com/yassienwasfy"><img src="https://img.shields.io/badge/Kaggle-161b22?style=for-the-badge&logo=kaggle&logoColor=58a6ff" alt="Kaggle" /></a>
<a href="https://huggingface.co/masterofaudio2077"><img src="https://img.shields.io/badge/Hugging%20Face-161b22?style=for-the-badge&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" /></a>
<a href="mailto:yassienashraf2025@gmail.com"><img src="https://img.shields.io/badge/Email-161b22?style=for-the-badge&logo=gmail&logoColor=bc8cff" alt="Email" /></a>

## 🧩 Open source

Pull requests I got merged into the libraries I use. Each tile opens its pull request.

<p align="center">
  <a href="https://github.com/keras-team/keras-hub/pull/2699"><img src="assets/tiles/blip2.svg" width="32%" alt="BLIP-2, vision and text, KerasHub, merged July 2026"></a>
  <a href="https://github.com/keras-team/keras-hub/pull/2932"><img src="assets/tiles/t5-kv-cache.svg" width="32%" alt="T5 KV cache and Seq2SeqLM, KerasHub, merged August 2026"></a>
  <a href="https://github.com/vllm-project/vllm/pull/66289"><img src="assets/tiles/vllm-triton.svg" width="32%" alt="vLLM T4 fix with a Triton kernel, merged November 2026"></a>
  <a href="https://github.com/onnx/onnx/pull/8266"><img src="assets/tiles/onnx-geglu.svg" width="32%" alt="ONNX GeGLU operator at opset 29, merged November 2026"></a>
  <a href="https://github.com/keras-team/keras-openvino/pull/66"><img src="assets/tiles/openvino-topk.svg" width="32%" alt="OpenVINO top_k fix for bfloat16, merged November 2026"></a>
  <a href="https://github.com/keras-team/keras-hub/pull/3186"><img src="assets/tiles/qwen3-vl.svg" width="32%" alt="Qwen3-VL for KerasHub, in review"></a>
</p>

- **BLIP-2** ([#2699](https://github.com/keras-team/keras-hub/pull/2699)): a vision-language model with weight-conversion scripts and numerical-parity tests against OPT-2.7B/6.7B and Flan-T5-XL/XXL checkpoints (5.0K lines, 32 files).
- **T5 KV caching and a `Seq2SeqLM` task** ([#2932](https://github.com/keras-team/keras-hub/pull/2932)): removes redundant recomputation during autoregressive decoding.
- **vLLM** ([#66289](https://github.com/vllm-project/vllm/pull/66289), bug [#66288](https://github.com/vllm-project/vllm/issues/66288)): Qwen3.5 compiled GPU kernels at startup and could fail to build on T4 GPUs. The fix uses a Triton kernel on GPUs older than SM80, so nothing needs compiling.
- **ONNX** ([#8266](https://github.com/onnx/onnx/pull/8266)): added GeGLU as a function operator at opset 29.
- **Keras OpenVINO** ([#66](https://github.com/keras-team/keras-openvino/pull/66)): fixed `top_k` on bfloat16 inputs, which was breaking KerasHub's OpenVINO CI.
- **In review:** Qwen3-VL for KerasHub ([#3186](https://github.com/keras-team/keras-hub/pull/3186), 33 files), shared model-test helpers that remove duplicated tests ([#3184](https://github.com/keras-team/keras-hub/pull/3184)), and a 2D multi-organ segmentation example with TransUNet for keras.io ([#2361](https://github.com/keras-team/keras-io/pull/2361)).
- Filed 21 issues across Keras, KerasHub, keras-io, JAX and vLLM; maintainers fixed 4 of my 6 bug reports in Keras, KerasHub and JAX.

## 🛠️ Projects

<p align="center">
  <a href="https://github.com/yassienashrafwasfy/PII-Masking-System"><img src="assets/tiles/pii-masking.svg" width="32%" alt="PII Masking System, FastAPI, GLiNER, XLM-R"></a>
  <a href="https://github.com/yassienashrafwasfy/hadith-search"><img src="assets/tiles/hadith-search.svg" width="32%" alt="Hadith Search, pgvector, LangGraph"></a>
  <a href="https://huggingface.co/masterofaudio2077"><img src="assets/tiles/hf-models.svg" width="32%" alt="Hugging Face models and datasets"></a>
</p>

- **[PII Masking System](https://github.com/yassienashrafwasfy/PII-Masking-System):** masks personal data in PDF, text, CSV and JSON. One gateway routes each request to a private per-team model service (XLM-RoBERTa, GLiNER, MedRoBERTa) that runs a shared detection and redaction pipeline, then returns masked files with consistent fake replacements. Comes with an evaluation leaderboard, CI/CD and VPS deployment.
- **[AI-powered Hadith Search](https://github.com/yassienashrafwasfy/hadith-search):** full-stack Arabic search over the six hadith books with FastAPI, PostgreSQL, pgvector, React, TypeScript and LangGraph. Hybrid BM25 + vector search with rank fusion, spelling suggestions and a reranker; the embedding model is shrunk and served with ONNX Runtime. 84 of the 121 commits are mine.
- **[Models and datasets on Hugging Face](https://huggingface.co/masterofaudio2077):** [FADA](https://huggingface.co/masterofaudio2077/Fada_ar_embedding), an Arabic embedding model (similarity score 48.5 → 69.1, ahead of multilingual-e5-small); an [Arabizi to Arabic converter](https://huggingface.co/masterofaudio2077/byt5-small-arabizi-word); an [Arabic book OCR model](https://huggingface.co/masterofaudio2077/arabic-nougat-base-books-ocr) (0.9% character error rate); an [Egyptian Arabic text-to-speech model](https://huggingface.co/masterofaudio2077/voicetut-egyptian-tashkeel) fine-tuned on 59 hours of voweled speech; and labelled Egyptian Arabic datasets such as [2,466 PII call scripts](https://huggingface.co/datasets/masterofaudio2077/egyptian-pii-call-scripts).

## 📈 In numbers

<p align="center">
  <a href="https://huggingface.co/masterofaudio2077"><img src="assets/tiles/stat-hf.svg" width="32%" alt="9.5K all-time downloads across 46 Hugging Face models and datasets"></a>
  <a href="https://kaggle.com/yassienwasfy"><img src="assets/tiles/stat-kaggle.svg" width="32%" alt="827 forks on Kaggle, 16 models, 117 upvotes"></a>
  <a href="https://github.com/yassienashrafwasfy"><img src="assets/tiles/stat-oss.svg" width="32%" alt="5 merged pull requests in Keras, ONNX, vLLM and OpenVINO"></a>
</p>

<sub>Hugging Face counts are all-time downloads from the Hub API on 19 Nov 2026. Kaggle figures are from my Kaggle profile.</sub>

## 💼 Experience

**AI Engineer Intern** | Cegedim, Cairo, Egypt | Jul 2026 – Sep 2026

Personal-data masking platform for Dutch, French and English medical letters and PDFs, used by 3 AI teams. Team of 6.

- Wrote 49% of its Python (24,863 of 50,897 lines by `git blame`), the most of the 6 engineers.
- Cut text-processing time 30% (1,189 to 835 ms) and cache memory 57% (15.4 to 6.7 MB) after profiling with Scalene.
- Added French and English support, new ID types (SSN, NPI, NHS number, GMC) and scanned-page reading; routed each document to the right language model with a rollback switch (XLM-RoBERTa, ONNX Runtime, PP-OCRv6).
- Wrote the training code and datasets for the detector, the versioned API contracts (v1.2 to v1.4) and the PDF redaction that keeps the page layout.
- Wrote about half of all tests, fixed about 39 bugs, and closed a leak that saved detected personal data in clear text.

**AI Trainee** | NAID, New Capital, Egypt | Jul 2025 – Sep 2025

**Full-Stack Trainee** | NAID, New Capital, Egypt | Jul 2024 – Sep 2024

## 🧰 Toolkit

**Languages & backend** &nbsp;
<img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=4584b6" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009485" alt="FastAPI" />
<img src="https://img.shields.io/badge/Django-161b22?style=flat-square&logo=django&logoColor=44B78B" alt="Django" />
<img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/React-161b22?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />

**ML frameworks** &nbsp;
<img src="https://img.shields.io/badge/JAX-161b22?style=flat-square&logo=google&logoColor=58a6ff" alt="JAX" />
<img src="https://img.shields.io/badge/Keras%203-161b22?style=flat-square&logo=keras&logoColor=FF4B4B" alt="Keras 3" />
<img src="https://img.shields.io/badge/TensorFlow-161b22?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" />
<img src="https://img.shields.io/badge/PyTorch-161b22?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
<img src="https://img.shields.io/badge/Hugging%20Face-161b22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" />
<img src="https://img.shields.io/badge/scikit--learn-161b22?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn" />

**Data** &nbsp;
<img src="https://img.shields.io/badge/NumPy-161b22?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy" />
<img src="https://img.shields.io/badge/Pandas-161b22?style=flat-square&logo=pandas&logoColor=F03FA0" alt="Pandas" />
<img src="https://img.shields.io/badge/Polars-161b22?style=flat-square&logo=polars&logoColor=CD792C" alt="Polars" />
<img src="https://img.shields.io/badge/Roboflow-161b22?style=flat-square&logo=roboflow&logoColor=A351FB" alt="Roboflow" />

**Training at scale** &nbsp;
<img src="https://img.shields.io/badge/TPU%20v5e--8-161b22?style=flat-square&logo=googlecloud&logoColor=4285F4" alt="TPU v5e-8" />
<img src="https://img.shields.io/badge/Multi--GPU-161b22?style=flat-square&logo=nvidia&logoColor=76B900" alt="Multi-GPU" />
<img src="https://img.shields.io/badge/Weights%20%26%20Biases-161b22?style=flat-square&logo=weightsandbiases&logoColor=FFBE00" alt="Weights and Biases" />
<img src="https://img.shields.io/badge/MLflow-161b22?style=flat-square&logo=mlflow&logoColor=0194E2" alt="MLflow" />
<img src="https://img.shields.io/badge/LoRA%20%2F%20QLoRA-161b22?style=flat-square&logoColor=bc8cff" alt="LoRA and QLoRA" />

**Deploy & optimize** &nbsp;
<img src="https://img.shields.io/badge/vLLM-161b22?style=flat-square&logoColor=bc8cff" alt="vLLM" />
<img src="https://img.shields.io/badge/ONNX%20Runtime-161b22?style=flat-square&logo=onnx&logoColor=e6edf3" alt="ONNX Runtime" />
<img src="https://img.shields.io/badge/OpenVINO-161b22?style=flat-square&logo=intel&logoColor=0071C5" alt="OpenVINO" />
<img src="https://img.shields.io/badge/TensorRT-161b22?style=flat-square&logo=nvidia&logoColor=76B900" alt="TensorRT" />
<img src="https://img.shields.io/badge/Quantization-161b22?style=flat-square&logoColor=bc8cff" alt="Quantization" />
<img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
<img src="https://img.shields.io/badge/GitLab%20CI-161b22?style=flat-square&logo=gitlab&logoColor=FC6D26" alt="GitLab CI" />
<img src="https://img.shields.io/badge/Gradio-161b22?style=flat-square&logo=gradio&logoColor=F97316" alt="Gradio" />
<img src="https://img.shields.io/badge/Streamlit-161b22?style=flat-square&logo=streamlit&logoColor=FF4B4B" alt="Streamlit" />
<img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
<img src="https://img.shields.io/badge/Linux-161b22?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
