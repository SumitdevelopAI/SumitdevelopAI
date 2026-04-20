<h1 align="center">Sumit Sharma</h1>

<p align="center">
  <b>AI Researcher &nbsp;·&nbsp; Quantum ML &nbsp;·&nbsp; Multimodal Systems &nbsp;·&nbsp; LLM Safety</b><br>
  <sub>B.Tech CSE (AI) &nbsp;·&nbsp; Parul Institute of Technology, Vadodara &nbsp;·&nbsp; Expected Jun 2026</sub>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3500&pause=1000&color=3FB950&center=true&vCenter=true&width=600&lines=Quantum+ML+%7C+VQE+%7C+QAOA+%7C+Qiskit+%7C+PennyLane;Vision-Language+Models+%7C+LoRA+%7C+Multimodal+Reasoning;LLM+Safety+%7C+Interpretability+%7C+Noise+Robustness;Inference+Optimisation+%7C+TensorRT+%7C+Production+ML" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ICML%202026-Under%20Review-blueviolet?style=flat-square&logo=arxiv" />
  <img src="https://img.shields.io/badge/Qiskit-Quantum%20ML-6929C4?style=flat-square&logo=ibm" />
  <img src="https://img.shields.io/badge/PyTorch-ML%20%26%20DL-EE4C2C?style=flat-square&logo=pytorch" />
  <img src="https://img.shields.io/badge/TensorRT-Inference%20Opt-76B900?style=flat-square&logo=nvidia" />
  <img src="https://img.shields.io/badge/HuggingFace-Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=000" />
  <img src="https://img.shields.io/badge/GDSC-Campus%20Lead-4285F4?style=flat-square&logo=google" />
</p>

---

## 🔬 Research Focus

Quantum machine learning, variational quantum algorithms, and hybrid classical–quantum systems — alongside vision-language model development, multimodal representation learning, LLM reasoning & reliability, neuro-symbolic agents, and production-grade ML with a focus on inference optimisation and real-world deployment.

---

## 📄 Research

### 📌 ICML 2026 (Submitted) — First Author
**Buffer Dynamics and Noise Robustness of Deductive and Inductive Reasoning in Language Models**

> Formalised reasoning as interactions among working-memory buffers. Compared attention averaging, recurrent state-space buffers (decay/drift), and holographic/vector-symbolic binding under increasing input noise. Identified mechanism-specific failure modes: **semantic dilution**, **drift instability**, **phase-transition behaviour** — measured via retrieval fidelity (cosine similarity) and symbolic correctness (argmax accuracy).

---

## 🚀 Projects

### ⚛️ VQE & QAOA — Quantum Optimisation Study
`Qiskit` `PennyLane` `UCCSD` `COBYLA/ADAM` `NumPy`

- Implemented **VQE** for ground-state energy estimation of H₂ and LiH using parameterised UCCSD ansatz circuits on Qiskit Aer simulator
- Implemented **QAOA** (depth p=1–3) for Max-Cut on random Erdős–Rényi graphs; benchmarked approximation ratio vs classical greedy; analysed barren-plateau sensitivity
- Simulated **depolarising and readout noise channels** to identify circuit-depth fidelity thresholds — relevant to quantum error characterisation
- Cross-validated using **PennyLane** for framework portability; documented as reproducible Jupyter notebooks with parameter sweep utilities

---

### 🖼️ Multimodal Document Understanding Pipeline — VLM Fine-tuning
`PyTorch` `LLaVA-1.5 (7B)` `LoRA/QLoRA` `PEFT` `Transformers`

- Fine-tuned LLaVA-1.5 on document-image QA (form extraction, layout parsing) using LoRA/QLoRA on a single A100 — **+12% over zero-shot** on DocVQA-style benchmarks
- End-to-end multimodal data pipeline: OCR-free tokenisation, perceptual-hash deduplication, synthetic augmentation
- Structured output extraction via JSON schema forcing (constrained decoding) for downstream retrieval-augmented workflows

---

### 🤖 6-DoF Object Pose Estimation for Bin Picking
`PyTorch` `OpenCV` `TensorRT` `PnP/RANSAC`

- 6-DoF pose estimation using PnP/RANSAC for occlusion-heavy bin-picking; benchmarked with ADD/ADI metrics
- TensorRT INT8 quantisation → **22% inference latency reduction** while preserving pose accuracy within ADD threshold
- Extended with batched inference + async pre-processing for multi-camera industrial setups

---

### 🫀 PhysioNet 2025 — Chagas Disease Detection (CNN–LSTM)
`PyTorch` `WFDB` `scikit-learn` `Platt Scaling`

- CNN–LSTM ECG classifier for 12-lead screening across CODE-15%, SaMi-Trop, PTB-XL datasets
- Automated evaluation harness: AUROC validation, Platt probability calibration, regression tracking

---

### 🧠 NS-SMH — Neuro-Symbolic Safe Agent
`PyTorch` `LLM` `VAD Bottleneck` `Docker`

- Safety-first agent separating neural affect perception from deterministic intervention selection
- Stress-tested against 100+ adversarial prompts via VAD semantic bottleneck to suppress unsafe instruction-following
- Dockerised with REST endpoints — production-grade deployment pattern

---

### 🧬 EEG Foundation Model — Representation Learning for Neuro-Signals
`PyTorch` `Transformers` `Contrastive Learning`

- Contrastive representation learning for EEG embeddings with cross-subject transfer robustness
- MAE-style masking adapted for time-series — mirrors vision encoder pre-training paradigms

---

## ⚙️ Stack

| Domain | Tools |
|---|---|
| **Quantum** | Qiskit (Aer · Terra · Ignis), PennyLane, VQE, QAOA, UCCSD |
| **ML / DL** | PyTorch, TensorFlow, HuggingFace Transformers, PEFT (LoRA/QLoRA), scikit-learn |
| **Vision & Multimodal** | LLaVA, CLIP, ViT, DETR, OpenCV, TorchVision |
| **Inference Optimisation** | TensorRT, FP16/INT8 quantisation, ONNX export, batched serving |
| **Training Infra** | Docker, Git, Linux, WandB, Jupyter, SLURM (basic) |
| **Research / Eval** | LLM evaluation, safety testing, benchmark harness design, statistical ablations |
| **Familiar** | Tensor networks (MPS/DMRG), quantum error correction (surface code), DeepSpeed ZeRO, RLHF/DPO, vLLM |

---

## 🏆 Achievements

- 🔬 **ICML 2026 Submission** — First-author paper on LLM buffer dynamics & noise robustness *(under review)*
- 🛰️ **Finalist** — ISRO Space Hackathon (2024); Indian International Science Festival Hackathon (2023, 2024)
- 🎓 **GDSC Campus Lead** — 10+ workshops · 500+ students · 10+ mentored project teams

---

## 💼 Experience

**Machine Learning Intern @ L&T Technology Services** *(May – Jul 2025)*
Reduced object-detection inference latency **15%** via TensorRT + FP16 for industrial P&ID perception. Integrated vision outputs into SCADA workflows; built batched inference wrappers.

**Campus Lead @ Google Developer Student Community** *(2025 – Present)*
Led PyTorch, CV, and applied ML workshops for 500+ students; mentored 10+ teams end-to-end.

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sumit45-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/sumit45)
[![Email](https://img.shields.io/badge/Email-sumit336sharma%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:sumit336sharma@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-SumitdevelopAI-181717?style=flat-square&logo=github)](https://github.com/SumitdevelopAI)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SumitdevelopAI&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=8b949e" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SumitdevelopAI&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e" height="150" />
</p>

<p align="center">
  <sub><i>// building AI systems that reason, explain, and align</i></sub>
</p>
