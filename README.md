# Hey there! I'm Taehoon Kang

<div align="center">
  
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=CS+Student+%40+University+of+Minnesota;Incoming+Software+Engineer+Intern+%40+Microsoft;Snap+Lens+Scholar;AI+Systems+%26+Product+Engineering;Inference+Benchmarking+%26+LLM+Evaluation;Building+Useful+Software+for+Real+Problems)](https://git.io/typing-svg)

</div>

---

## About Me

> *"I like building systems that are technically rigorous and useful in practice."*

**Computer Science Student** @ University of Minnesota  
**Incoming Software Engineer Intern** @ Microsoft  
**Software Engineer Intern** @ Snap Inc  
**Student Instructor** @ Stanford Code in Place  
**Undergraduate Research Intern** @ Minnesota Supercomputing Institute  
**Location:** Minneapolis, MN | **Email:** thkang091@gmail.com

### Current Focus

- AI systems and inference benchmarking
- LLM evaluation and document AI infrastructure
- Backend, mobile, and cloud-connected product engineering
- Reliable software for real-world workflows

---

## Tech Arsenal

<div align="center">

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### AI / ML Systems

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-Inference-4B5563?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-GPU_Benchmarking-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![LLM Evaluation](https://img.shields.io/badge/LLM-Evaluation-111827?style=for-the-badge)

### Backend, Cloud, and Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Product and Mobile

![Swift](https://img.shields.io/badge/Swift-iOS-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-iOS-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![REST APIs](https://img.shields.io/badge/REST_APIs-Backend-374151?style=for-the-badge)

</div>

---

## Featured Projects

<div align="center">

### DraftVerifyBench

*GPU inference benchmarking framework for studying when speculative decoding helps or hurts LLM inference.*

[![Repository](https://img.shields.io/badge/Repository-DraftVerifyBench-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/thkang091/DraftVerifyBench)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)]()
[![vLLM](https://img.shields.io/badge/vLLM-Inference-4B5563?style=flat-square)]()
[![CUDA](https://img.shields.io/badge/CUDA-GH200-76B900?style=flat-square&logo=nvidia&logoColor=white)]()

**Focus:** Speculative decoding | GPU latency benchmarking | Model routing | Reproducible ML systems evaluation

- Benchmarked Qwen 2.5 and Llama 3 draft/verifier pairs on an NVIDIA GH200 480GB.
- Measured speculative-decoding latency across 1,800 benchmark rows and two seeds per model family.
- Characterized slowdown regimes where draft-model overhead can dominate verifier-call savings.
- Built reproducible tooling with raw traces, YAML configs, summaries, tests, and report-style analysis.

---

### ReceiptInject

*LLM document-agent evaluation infrastructure for testing extraction systems under embedded prompt-injection attacks.*

[![Repository](https://img.shields.io/badge/Repository-ReceiptInject-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/thkang091/ReceiptInject)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)]()
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)]()
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)]()
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)]()

**Focus:** LLM evaluation | Document AI | Agent safety | Provider benchmarking | Reproducible pipelines

- Evaluated OpenAI, Mistral, and Gemini document agents across synthetic receipts, invoices, policies, and bank statements.
- Produced a reproducible 2,700-row benchmark across 300 examples, 3 providers, and 3 prompting strategies.
- Measured malicious-instruction compliance, safe completion, and unsafe tool-execution risk.
- Built a Dockerized FastAPI pipeline with provider abstraction, SQLite caching, structured logging, and resumable runs.

---

### Dutchie

*AI-assisted receipt and expense-splitting app focused on making shared payments easier and more accurate.*

[![Repository](https://img.shields.io/badge/Repository-Dutchie-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/thkang091/Dutchie)
[![Swift](https://img.shields.io/badge/Swift-iOS-FA7343?style=flat-square&logo=swift&logoColor=white)]()
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)]()
[![OCR](https://img.shields.io/badge/OCR-Document_AI-374151?style=flat-square)]()
[![LLM](https://img.shields.io/badge/LLM-Extraction-111827?style=flat-square)]()

**Focus:** Mobile engineering | OCR/Document AI | Expense splitting | Group balances | Product correctness

- Built receipt and statement workflows for scanning, parsing, reviewing, and splitting shared expenses.
- Integrated OCR/LLM-based extraction with validation for items, subtotal, tax, tip, discounts, and totals.
- Designed group balance and settlement flows to help users track who owes whom across shared expenses.
- Focused on correctness and reducing the risk of incorrect payment splits before users send payments.

</div>

---

## Background

<table>
<tr>
<td width="25%">

### Microsoft

Incoming Software Engineer Intern

</td>
<td width="25%">

### Snap Inc.

Software Engineer Intern

</td>
<td width="25%">

### Stanford

Student Instructor, Code in Place

</td>
<td width="25%">

### Minnesota Supercomputing Institute

Undergraduate Research Intern

</td>
</tr>
</table>

---

## Currently Exploring

<div align="center">

![Speculative Decoding](https://img.shields.io/badge/Speculative_Decoding-LLM_Inference-111827?style=for-the-badge)
![Model Routing](https://img.shields.io/badge/Model_Routing-AI_Systems-374151?style=for-the-badge)
![Document AI](https://img.shields.io/badge/Document_AI-Evaluation-4B5563?style=for-the-badge)
![GPU Benchmarking](https://img.shields.io/badge/GPU_Benchmarking-Performance-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Product Engineering](https://img.shields.io/badge/Product_Engineering-Software-2563EB?style=for-the-badge)

</div>

---

## Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-taehoon--kang-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/taehoon-kang/)
[![Email](https://img.shields.io/badge/Email-thkang091%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thkang091@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-thkang091-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/thkang091)

</div>
