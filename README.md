# Beyond Factual QA: Mentorship-Oriented Question Answering from Long-Form Multilingual Content

[![Paper](https://img.shields.io/badge/Paper-ArXiv-red.svg)](https://arxiv.org/abs/2601.17173) 
[![Dataset](https://img.shields.io/badge/Dataset-HuggingFace-yellow.svg)](https://huggingface.co/datasets/AIM-SCU/MentorQA) 

This repository contains the dataset and code for our paper: 

**Beyond Factual QA: Mentorship-Oriented Question Answering from Long-Form Multilingual Content**.

📄 **Preprint:** [https://arxiv.org/pdf/2601.17173](https://arxiv.org/pdf/2601.17173)

<p align="center">
  <img src="Mentorship.jpg" alt="Mentorship Overview" width="30%">
</p>

## 📖 Overview

We introduce **MentorQA**, the first multilingual benchmark for mentorship-focused question answering from long-form videos. Standard AI benchmarks often reward models for generating generic, surface-level factual answers. However, real-world users seeking advice need deep, actionable guidance. 

This project shows that our multi-agent QA systems produce significantly more effective guidance than factual QA baselines—especially for complex topics and low-resource languages—while highlighting the limits of current automated evaluation.

### Core Objectives & Real-World Impact
* **Time-Efficient Learning:** Access key mentorship knowledge without needing to watch hours of long-form video.
* **Enhanced Accessibility:** Support learners with attention deficits or limited focus spans by distilling complex topics into clear, bite-sized QAs.
* **Global Reach:** Democratize mentorship access across multiple languages, breaking down cultural and linguistic barriers.
* **Advanced AI Extraction:** Utilize multi-agent, multimodal AI to efficiently pinpoint and extract only the most valuable insights from a sea of content.

---

## 📊 Dataset

The MentorQA dataset contains the video links and generated QA pairs evaluated in our study. It can be accessed directly on HuggingFace:

🔗 **[https://huggingface.co/datasets/AIM-SCU/MentorQA](https://huggingface.co/datasets/AIM-SCU/MentorQA)**

---

## 📂 Repository Structure

```text
MentorQA/
├── Anonymized-Dataset/  # The anonymized human evaluation dataset
├── LLMChunking/         # Code for standard LLM chunking baseline methods
├── MultiAgentChunking/  # Core multi-agent chunking and extraction framework (Ours)
├── RAG/                 # Retrieval-Augmented Generation baseline implementation
├── SingleQA/            # Baseline Single-Agent QA pipeline scripts
├── common_utils/        # Shared utility functions and evaluation scripts
├── preprocess.py        # Main script for preprocessing video transcripts

└── run.py               # Main execution script for the generation pipelines
```


## 🛠️ Setup

### 1. Clone the repository:

```bash
git clone https://github.com/AIM-SCU/MentorQA.git
cd MentorQA
```

### 2. Create a virtual environment (Recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Core Dependencies:
Our pipeline utilizes **Qwen2.5-7B-Instruct-1M** and BGE-M3 models. You can install the required libraries directly using pip:

```bash
# Production namespace


# Preview namespace

```

### 4. 


### 5. Run

```bash

```



## 📝 License

MIT License


