<p align="center">
  <img src="assets/subaru-subaru-natsuki.gif" alt="Subaru animation" width="320" />
</p>

<h1 align="center">Yassien Wasfy</h1>
<p align="center"><i>Building intelligent systems, one ambitious idea at a time.</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/yassien-wasfy-315ab5349"><img src="https://img.shields.io/badge/LinkedIn-161b22?style=for-the-badge&logo=linkedin&logoColor=58a6ff" alt="LinkedIn" /></a>
  <a href="https://kaggle.com/yassienwasfy"><img src="https://img.shields.io/badge/Kaggle-161b22?style=for-the-badge&logo=kaggle&logoColor=58a6ff" alt="Kaggle" /></a>
  <a href="https://huggingface.co/masterofaudio2077"><img src="https://img.shields.io/badge/Hugging%20Face-161b22?style=for-the-badge&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" /></a>
  <a href="mailto:yassienashraf2025@gmail.com"><img src="https://img.shields.io/badge/Email-161b22?style=for-the-badge&logo=gmail&logoColor=bc8cff" alt="Email" /></a>
</p>

<br />

## Open source

**[keras-team/keras-hub](https://github.com/keras-team/keras-hub)** is Google's pretrained model library.
Added **BLIP-2** vision-language support and JAX auto-sharding. Reported 10+ bugs that were fixed.

<img src="https://img.shields.io/badge/Keras%20Hub-161b22?style=flat-square&logo=keras&logoColor=FF4B4B" alt="Keras Hub" />

**[onnx/onnx](https://github.com/onnx/onnx)** is the interchange format used across the ML ecosystem.
Proposed the **GeGLU** operator as a function-op at opset 28. It is the gated activation behind T5 v1.1, Gemma, and PaLM.

<img src="https://img.shields.io/badge/ONNX-161b22?style=flat-square&logo=onnx&logoColor=e6edf3" alt="ONNX" />

<br />

## Experience

**Computer Vision Trainee** | NAID, New Capital, Egypt | Jul-Sep

- Studied and applied deep learning concepts, including segmentation and object detection, across the ML lifecycle.
- Built a GAN-based model to recover audio signals from noisy environments and improve reconstruction quality on degraded inputs.

**Intern** | Cegedim, Cairo, Egypt | Jul 2026-Aug 2026

- Built an NLP pipeline for data masking and PII detection to support EU GDPR requirements.
- Tracked experiments and wrote tests while working across a complex multi-branch Git setup.
- Worked with the MLOps team on deployment and reached the project's first milestone.
- Shipped a fully deployed application as part of one of the few Cegedim teams to do so.

<br />


## Projects

<table>
<tr>
<td width="50%" valign="top">

**Text2Img Generation Model**

Scraped 1.3M images and rewrote their captions with the LLaVA vision-language model. Trained a U-Net from scratch for a week on a TPU v5e-8 pod, with W&B logging metrics, model artifacts, and generated images throughout training. Inference runs on a mobile-budget CPU in under 30 seconds, removing the need for expensive deployment infrastructure.

`TensorFlow` `Keras 3` `JAX` `W&B` `TPU v5e-8` `NumPy` `Vue` `FastAPI`

[Live demo →](https://huggingface.co/spaces/masterofaudio2077/Stable_Diffusion_Text-to-img)

</td>
<td width="50%" valign="top">

**Face Attributes**

Multi-label classifier over 40 facial attributes on CelebA, built on MobileNetV5 and trained distributed across an 8-chip TPU v5e pod. 91% validation accuracy.

`MobileNetV5` `Keras 3` `JAX` `TPU v5e-8`

[Live demo →](https://huggingface.co/spaces/masterofaudio2077/celeb_a_identifier_1)

</td>
</tr>
</table>

<br />

## Toolkit

**Frameworks**

<p>
  <img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=4584b6" alt="Python" />
  <img src="https://img.shields.io/badge/JAX-161b22?style=flat-square&logo=google&logoColor=58a6ff" alt="JAX" />
  <img src="https://img.shields.io/badge/Keras%203-161b22?style=flat-square&logo=keras&logoColor=FF4B4B" alt="Keras 3" />
  <img src="https://img.shields.io/badge/TensorFlow-161b22?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/PyTorch-161b22?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
  <img src="https://img.shields.io/badge/scikit--learn-161b22?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn" />
</p>

**Data**

<p>
  <img src="https://img.shields.io/badge/NumPy-161b22?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy" />
  <img src="https://img.shields.io/badge/Pandas-161b22?style=flat-square&logo=pandas&logoColor=F03FA0" alt="Pandas" />
  <img src="https://img.shields.io/badge/Polars-161b22?style=flat-square&logo=polars&logoColor=CD792C" alt="Polars" />
  <img src="https://img.shields.io/badge/Hugging%20Face-161b22?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Roboflow-161b22?style=flat-square&logo=roboflow&logoColor=A351FB" alt="Roboflow" />
</p>

**Training at scale**

<p>
  <img src="https://img.shields.io/badge/TPU%20v5e--8-161b22?style=flat-square&logo=googlecloud&logoColor=4285F4" alt="TPU v5e-8" />
  <img src="https://img.shields.io/badge/Multi--GPU-161b22?style=flat-square&logo=nvidia&logoColor=76B900" alt="Multi-GPU" />
  <img src="https://img.shields.io/badge/Weights%20%26%20Biases-161b22?style=flat-square&logo=weightsandbiases&logoColor=FFBE00" alt="Weights and Biases" />
  <img src="https://img.shields.io/badge/MLflow-161b22?style=flat-square&logo=mlflow&logoColor=0194E2" alt="MLflow" />
  <img src="https://img.shields.io/badge/LoRA%20%2F%20QLoRA-161b22?style=flat-square&logoColor=bc8cff" alt="LoRA and QLoRA" />
</p>

**Deploy & optimize**

<p>
  <img src="https://img.shields.io/badge/ONNX-161b22?style=flat-square&logo=onnx&logoColor=e6edf3" alt="ONNX" />
  <img src="https://img.shields.io/badge/TensorRT-161b22?style=flat-square&logo=nvidia&logoColor=76B900" alt="TensorRT" />
  <img src="https://img.shields.io/badge/Quantization-161b22?style=flat-square&logoColor=bc8cff" alt="Quantization" />
  <img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=009485" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Gradio-161b22?style=flat-square&logo=gradio&logoColor=F97316" alt="Gradio" />
  <img src="https://img.shields.io/badge/Streamlit-161b22?style=flat-square&logo=streamlit&logoColor=FF4B4B" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-161b22?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux" />
</p>
