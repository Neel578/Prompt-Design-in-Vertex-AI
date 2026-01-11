<div align="center">

# 🤖 Vertex AI Prompt Engineering

### Master the Art of Talking to LLMs with Google Gemini

[![Google Cloud](https://img.shields.io/badge/Google_Cloud-Vertex_AI-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/vertex-ai)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Gemini](https://img.shields.io/badge/Model-Gemini_2.5_Flash-8E75B2?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-Apache_2.0-green?style=for-the-badge)](LICENSE)

[Overview](#-overview) •
[Key Concepts](#-key-concepts) •
[Installation](#-installation) •
[Usage](#-usage) •
[Repository Structure](#-repository-structure)

</div>
---

## 📖 Overview

Welcome to the **Vertex AI Prompt Design** repository. This project is a comprehensive guide and code laboratory demonstrating how to effectively communicate with Large Language Models (LLMs) using the **Google Cloud Vertex AI SDK**.

Prompt engineering is no longer just "asking questions"—it is the programming language of the new AI age. This lab explores advanced techniques to reduce hallucinations, improve latency, and force deterministic outputs from generative models.

## 🚀 Key Concepts

This repository covers the following best practices for production-grade prompt engineering:

| Concept | Description |
| :--- | :--- |
| **✨ Conciseness** | Reducing noise to prevent the LLM from misinterpreting intent. |
| **🎯 Specificity** | Moving from generic queries to well-defined constraints. |
| **🧩 Single-Tasking** | Breaking complex logic into solitary, manageable tasks. |
| **🛡️ Guardrails** | Using **System Instructions** to prevent hallucinations and off-topic answers. |
| **🧠 Few-Shot Learning** | Providing examples (1-shot, few-shot) to guide style and tone. |
| **🔄 Classification** | Turning open-ended generative tasks into strict classification problems. |

---

## 📦 Installation

To run this lab locally, you need a Google Cloud Project with the **Vertex AI API** enabled.

### 1. Clone the Repository
```bash
git clone [https://github.com/YourUsername/vertex-ai-prompt-engineering.git](https://github.com/YourUsername/vertex-ai-prompt-engineering.git)
cd vertex-ai-prompt-engineering
