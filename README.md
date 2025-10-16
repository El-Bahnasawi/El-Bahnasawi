# 👋 Mahmoud El-Bahnasawi

**ML engineer shipping NLP systems**  
Built sub-second hate-speech moderation with **BERTweet + LoRA**, FastAPI on GPU, and real user feedback.

**Live:** **[Repo](https://github.com/El-Bahnasawi/AI-Powered-Textual-Hate-Content-Moderation)** • **[Demo](https://hate-speech-detection-app.streamlit.app/)** • **[W&B](https://wandb.ai/medoxz543-zewail-city-of-science-and-technology/Textual%20Hate%20Content%20Moderation%20with%20BERTweet%20%2B%20LoRA?nw=nwusermedoxz543)** • **[Model](https://huggingface.co/medoxz543/hate-speech)**

---

## 🔥 Highlights

- **84.5% Macro-F1** on 530k+ tweets (**+4.5% over MetaHate**)
- **LoRA fine-tuning** with **1.4% weight updates** - efficient and effective
- **Sub-second inference** via FastAPI on Hugging Face GPU
- **Full-stack system**: browser extension → API → feedback DB → active learning

---

## 🚀 What I Build

- **Production NLP**: Fine-tuned transformers that actually ship
- **Measurable Systems**: Clear latency and accuracy targets from day one  
- **User-Facing ML**: Demos and extensions that validate real-world usefulness
- **Instrumented Workflows**: W&B for honest, reproducible metrics
- **Feedback Loops**: Systems that learn from real user interactions

---

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Weights&Biases](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

## 🛡️ AI-Powered Hate Speech Moderation

### TL;DR
Three-tier pipeline: **regex pre-filter** → **LoRA-tuned BERTweet** → **decision service**. Real-time moderation via browser extension and web UI, with Supabase feedback for continuous learning.

### 🎯 Results That Matter
- **84.5% Macro-F1** on 530k+ tweets (beats MetaHate by +4.5%)
- **1.4% weights updated** via LoRA - highly parameter-efficient  
- **Sub-second inference** on GPU-backed FastAPI
- **Active learning** pipeline with Supabase feedback storage

### 🔥 System Architecture - See the Magic!
<details>
<summary>🚀 **CLICK TO SEE THE FULL SYSTEM FLOW** → *This is where the engineering happens!*</summary>
<br>

![Hate Speech Moderation System Architecture](system_overview.png)

**🎯 How It Actually Works:**
- **Real-time Input**: Browser extension + Streamlit demo capture user text
- **Smart Filtering**: Regex catches obvious slurs → BERTweet handles nuanced cases  
- **GPU Power**: Hugging Face Spaces with T4 GPU for lightning inference
- **Continuous Learning**: Supabase stores edge cases to make the model smarter
- **Instant Decisions**: Three clear thresholds with visual feedback

*This isn't just a model - it's a production system that learns and improves!*
</details>

### ⚡ Smart Decision Logic
| Hate Score | Action | Blocked By | UI |
|------------|--------|------------|----|
| < 0.40 | ✅ Allow | - | 🟢 |
| 0.40 - 0.99 | 🚫 Block | **Fine-tuned BERTweet** | 🟠 |
| = 1.00 | 🚫 Block | **Regex Rules** | 🔴 |

**Key Insight**: Regex handles obvious cases instantly, BERTweet catches nuanced hate speech!

### 🔗 Live & Working Right Now
- **📁 Full Code**: [AI-Powered-Textual-Hate-Content-Moderation](https://github.com/El-Bahnasawi/AI-Powered-Textual-Hate-Content-Moderation)  
- **🎯 Try the Demo**: [Live Streamlit App](https://hate-speech-detection-app.streamlit.app/)
- **📊 Real Training Logs**: [W&B Dashboard](https://wandb.ai/medoxz543-zewail-city-of-science-and-technology/Textual%20Hate%20Content%20Moderation%20with%20BERTweet%20%2B%20LoRA)
- **🤗 Production Model**: [Hugging Face Model](https://huggingface.co/medoxz543/hate-speech)
---

## 📚 Other Projects

### 📊 Graph-Based Text Summarization
<details>
<summary>SBERT · PageRank · ROUGE L2 ≈ 0.41 · Streamlit</summary>

- Semantic graph summarization with SBERT + PageRank
- **ROUGE L2 ≈ 0.41** on CNN/DailyMail
- **~0.04s/article** inference, interactive visualization

**Repo**: https://github.com/El-Bahnasawi/Graph-Based-Text-Summarization  
**Demo**: https://graph-based-text-summarization.streamlit.app/
</details>

### 🎯 Walmart Sales Analytics  
<details>
<summary>Plotly Dash · Docker · Clustering · Render</summary>

- Multi-tab dashboard for 45 stores × 98 departments
- Store segmentation (4 tiers) and holiday impact analysis
- Dockerized deployment on Render

**Repo**: https://github.com/El-Bahnasawi/Walmart-Dataset-Analysis  
**Live**: https://walmart-dataset-analysis.onrender.com/
</details>

### 🔬 U.S. Crime Analysis
<details>
<summary>XGBoost · Statistical Testing · Plotly</summary>

- 30-year trend analysis and policy impact assessment
- Recidivism prediction (98-100% accuracy) with interpretable features

**Repo**: https://github.com/El-Bahnasawi/Analyzing-U.S.-Crime-Data
</details>

---

## 🎯 Focus Areas

- **Production NLP**: Fine-tuning, optimization, and deployment
- **ML Systems**: End-to-end pipelines with monitoring and feedback
- **Practical MLOps**: Experiment tracking, deployment, and iteration

---

## 📫 Reach Out

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mahmoud-elbahnasawi1/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:m.elbahnasawi.ai@gmail.com)
