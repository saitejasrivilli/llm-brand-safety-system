# 🛡️ LLM Brand Safety System

A production-style, multi-modal **brand safety and content moderation system** built using **BERT, CLIP, and Hugging Face Transformers**.  
Designed to demonstrate real-world ML engineering skills across **model training, inference, explainability, and deployment**.

---

## 🚀 Live Demo

👉 **Hugging Face Space:**  
https://huggingface.co/spaces/SaiTejaSrivilli/LLMBrandSafetySystem

Recruiters can interact with:
- Text-only moderation
- Image-only safety checks
- Combined text + image analysis
- Visual confidence scores and final policy decisions

---

## 🔍 What This System Does

This system evaluates whether user-generated or advertising content is **safe for brand association**, producing:

- **Final verdict:** `APPROVE`, `REVIEW`, or `REJECT`
- **Category-level risk scores**
- **Human-readable explanations**
- **Latency metrics**
- **Visual confidence plots**

It mirrors how moderation pipelines are implemented in **ad platforms, social media, and marketplaces**.

---

## 🧠 Models & Techniques

### Text Moderation
- Fine-tuned **BERT (bert-base-uncased)**
- Multi-label classification across 6 categories:
  - Toxicity
  - Hate Speech
  - Political Content
  - Adult Content
  - Spam
  - Safe
- Sigmoid-based scoring with policy thresholds

### Image Moderation
- **CLIP (ViT-B/32)** for zero-shot image safety detection
- Evaluates images against safety concepts such as:
  - Violent content
  - Adult imagery
  - Hate symbols
  - Spam advertisements

### Decision Logic
- Text and image signals are combined
- Conservative escalation rules:
  - Any high-risk signal → `REVIEW` or `REJECT`
- Clear explanations generated for every decision

---

## 📊 Explainability & Visualization

- Category-level probability outputs
- Horizontal bar charts for both text and image risk
- Transparent rule-based verdict logic
- Designed to be understandable by **non-ML stakeholders**

---

## 🏗️ Architecture Overview

# 🛡️ LLM Brand Safety System

A production-style, multi-modal **brand safety and content moderation system** built using **BERT, CLIP, and Hugging Face Transformers**.  
Designed to demonstrate real-world ML engineering skills across **model training, inference, explainability, and deployment**.

---

## 🚀 Live Demo

👉 **Hugging Face Space:**  
https://huggingface.co/spaces/SaiTejaSrivilli/LLMBrandSafetySystem

Recruiters can interact with:
- Text-only moderation
- Image-only safety checks
- Combined text + image analysis
- Visual confidence scores and final policy decisions

---

## 🔍 What This System Does

This system evaluates whether user-generated or advertising content is **safe for brand association**, producing:

- **Final verdict:** `APPROVE`, `REVIEW`, or `REJECT`
- **Category-level risk scores**
- **Human-readable explanations**
- **Latency metrics**
- **Visual confidence plots**

It mirrors how moderation pipelines are implemented in **ad platforms, social media, and marketplaces**.

---

## 🧠 Models & Techniques

### Text Moderation
- Fine-tuned **BERT (bert-base-uncased)**
- Multi-label classification across 6 categories:
  - Toxicity
  - Hate Speech
  - Political Content
  - Adult Content
  - Spam
  - Safe
- Sigmoid-based scoring with policy thresholds

### Image Moderation
- **CLIP (ViT-B/32)** for zero-shot image safety detection
- Evaluates images against safety concepts such as:
  - Violent content
  - Adult imagery
  - Hate symbols
  - Spam advertisements

### Decision Logic
- Text and image signals are combined
- Conservative escalation rules:
  - Any high-risk signal → `REVIEW` or `REJECT`
- Clear explanations generated for every decision

---

## 📊 Explainability & Visualization

- Category-level probability outputs
- Horizontal bar charts for both text and image risk
- Transparent rule-based verdict logic
- Designed to be understandable by **non-ML stakeholders**

---

## 🏗️ Architecture Overview

User Input
├── Text → BERT → Risk Scores
├── Image → CLIP → Risk Scores
└── Policy Engine → Final Verdict
↓
Gradio UI (HF Spaces)



---

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **Hugging Face Transformers**
- **CLIP**
- **Gradio**
- **Plotly**
- **Hugging Face Spaces**

---

## 📦 Repository Notes

- Model weights are hosted on **Hugging Face Spaces**
- GitHub repo contains only:
  - Application code
  - Configuration
  - Documentation
- No large binaries checked into GitHub

---

## 💡 Why This Project Matters

This project demonstrates:
- End-to-end ML system design
- Multi-modal inference pipelines
- Realistic moderation policies
- Deployment-ready interfaces
- Production-style engineering decisions

It reflects the kind of work done in:
- Ads safety teams
- Trust & Safety orgs
- Content moderation platforms
- ML platform engineering roles

---

## 👤 Author

**Sai Teja Srivilli**  
Machine Learning Engineer / Applied AI  
🔗 Hugging Face • GitHub

---

