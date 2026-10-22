# Hi, I'm Yushen Ding 👋

M.S. student in Electrical and Computer Engineering (Machine Learning and Data Science) at USC, focused on AI/ML engineering, multimodal AI, and computer vision.

Currently seeking Summer 2027 internships in AI/ML Engineering, Agentic AI, Multimodal AI, and Computer Vision.

## 🔥 Featured Projects

### [Chinese Name Generator — AI-Assisted Legacy Modernization](https://github.com/ethandingsc/Chinese-Name-Generator-AI-Assisted-Legacy-Modernization) · *Aug 2026 – Oct 2026*

<p align="center">
  <a href="https://github.com/ethandingsc/Chinese-Name-Generator-AI-Assisted-Legacy-Modernization">
    <img src="assets/nameai.png" width="75%" alt="Chinese Name Generator — AI-Assisted Legacy Modernization">
  </a>
</p>

- Modernized a legacy employee-facing naming system into a **Next.js, TypeScript, and FastAPI** application while preserving deterministic birth-data, Five-Element, stroke-count, character, and taboo constraints.
- Built an **agentic recommendation workflow** combining BM25 and vector retrieval, classical-poetry RAG, constrained candidate exploration, and LLM-based whole-name evaluation with diversity control and user-feedback refinement.
- Added **evidence-grounded explanations** that verify poetry quotations and cultural sources, separating factual references from creative interpretation to reduce unsupported AI claims.
- Productionized the system with **126 Golden Tests, 178+ automated tests, GitHub Actions CI, and Docker Compose** deployment with persistent workflow state and retrieval caches.

### [CloudBox — Multi-Source RAG for Technical Support](https://github.com/ethandingsc/cloudbox-multi-source-rag) · *Sep 2026 – Oct 2026*

<p align="center">
  <a href="https://github.com/ethandingsc/cloudbox-multi-source-rag">
    <img src="assets/cloudbox.png" width="75%" alt="CloudBox — Multi-Source RAG for Technical Support">
  </a>
</p>

- Built a **multi-source technical-support RAG system** integrating official documentation, customer forums, and technical blogs with source-specific chunking and **ChromaDB** vector retrieval.
- Combined **source-authority weighting, CrossEncoder reranking, and version-aware conflict resolution** to select reliable evidence and generate grounded answers with traceable chunk citations.
- Achieved **95.00% Hit@5 and 93.54% Recall@5** at the final evidence-selection stage on a fixed **120-query synthetic evaluation set**, with reproducible retrieval experiments.
- Delivered **FastAPI endpoints, Kafka-backed asynchronous workers, and Redis caching and session history**, packaged with **Docker Compose** and GitHub Actions CI running offline regression tests.

### [Agentic Driving Video Understanding with Qwen2.5-VL](https://github.com/ethandingsc/Agentic-Driving-Video-Understanding-with-Qwen2.5-VL) · *Sep 2026*

<p align="center">
  <a href="https://github.com/ethandingsc/Agentic-Driving-Video-Understanding-with-Qwen2.5-VL">
    <img src="assets/Image13_02_33.png" width="75%" alt="Agentic Driving Video Understanding with Qwen2.5-VL">
  </a>
</p>

* Fine-tuned **Qwen2.5-VL-7B with LoRA** for multi-frame driving-video understanding, improving **MCQ Accuracy from 76.40% to 81.62%** and **Lingo-Judge from 61.71% to 73.74%**
* Evaluated **Uniform / Dense / Event-aware temporal sampling** and found that dense sampling can lose long-range temporal context despite capturing more local motion
* Built a **LangGraph agent** that uses Qwen2.5-VL as a planner to select safety-critical temporal segments, then performs **local re-sampling and detailed multimodal analysis**
* Integrated lightweight **RAG** for driving-safety knowledge grounding and deployed the fine-tuned model with **SGLang + Gradio**


### [LLaVA Multimodal VQA Fine-Tuning & Deployment](https://github.com/ethandingsc/LLaVA-ScienceQA-LoRA-Fine-Tuning-SGLang-Deployment) · *Aug 2026*

<p align="center">
  <a href="https://github.com/ethandingsc/LLaVA-ScienceQA-LoRA-Fine-Tuning-SGLang-Deployment">
    <img src="assets/llava.png" width="75%" alt="LLaVA Multimodal VQA Fine-Tuning & Deployment">
  </a>
</p>

* Fine-tuned **LLaVA-v1.6-Vicuna-7B** on ScienceQA using **LoRA**
* Improved accuracy from **56.32% → 70.10% (+13.78 pp)**
* Built an end-to-end inference pipeline with **SGLang, OpenAI-compatible API, and Gradio**


### [GSMBNet — Medical Image Segmentation](https://github.com/ethandingsc/GSMBNet) · *Jun 2025 – Dec 2025*

<p align="center">
  <a href="https://github.com/ethandingsc/GSMBNet">
    <img src="assets/gsmbnet.png" width="75%" alt="GSMBNet — Medical Image Segmentation">
  </a>
</p>

- Designed a cross-scale morphology and boundary modeling network for medical image segmentation
- Conducted **80+ comparative and ablation experiments**
- Achieved **2%+ improvement in mIoU and mDSC** over U-Net baselines on ISIC2017/2018


## 💼 Experience

### Traffic Control Technology Co., Ltd. — Deep Learning Data Intern

**Railway Autonomous Driving | Jul 2025 – Aug 2025**

* Worked on visual dataset iteration for **railway autonomous driving**, including data quality analysis, annotation standards, and hard-example mining
* Introduced a **lightweight-model auto-labeling + human review** workflow to improve annotation efficiency
* Analyzed challenging scenarios including **rain/fog, low-light conditions, curves, and small objects** to identify data and detection bottlenecks

### Beijing Limingtang Culture Technology Co., Ltd. — TTS Development Intern

**Speech Cloning | Jun 2024 – Aug 2024**

* Built and processed speech-cloning datasets using **GPT-SoVITS-TTS**, including denoising, segmentation, and normalization
* Improved dataset balance with dialect and noisy-environment samples and tuned training configurations to improve voice-cloning quality


## 🛠️ Technical Skills

**Languages:** Python · C++ · TypeScript  
**ML / DL:** PyTorch · LoRA · CNNs · Transformers · Vision-Language Models  
**Computer Vision:** OpenCV · Image Segmentation · Multimodal Learning  
**AI & Engineering:** SGLang · Gradio · Claude Code · Gemini API · Git · Linux

## 🎓 Education

**University of Southern California**
M.S. Electrical and Computer Engineering — Machine Learning & Data Science

**Relevant Coursework:** EE 503 Engineering Probability · EE 510 Engineering Linear Algebra · EE 541 Deep Learning · EE 559 Machine Learning · CSCI 677 Advanced Computer Vision

**Tiangong University**
B.S. Computer Science and Technology

## 📄 Publications

* **GSMBNet: A Cross-Scale Morpho-Boundary Modeling Network for Medical Image Segmentation** — ICIC 2026, Springer LNCS
* **Enhanced YOLO Optimization Study for Road Sign Detection in Autonomous Driving** — CVIDL 2024, IEEE

## 📫 Contact

📧 [yushending1014@gmail.com](mailto:yushending1014@gmail.com)
