# AICheck: AI-Based Social Media Content Authenticity Checker

> Multi-Modal AI System for Detecting Manipulated Media and AI-Generated Content

AICheck is a web-based cybersecurity and digital forensics application designed to verify the authenticity of digital content across images, videos, and text. The system leverages state-of-the-art deep learning models, Vision Transformers (ViTs), and Natural Language Processing (NLP) to detect deepfakes, visual manipulation artifacts, and AI-generated writing.

---

## Features
* **Image Authenticity Analysis:** Detects facial inconsistencies, lighting anomalies, and edge distortions using Vision Transformer (ViT) models.
* **Video Frame-by-Frame Processing:** Extracts video frames sequentially to identify temporal inconsistencies and deepfake manipulation.
* **AI-Generated Text Detection:** Evaluates textual content using transformer-based NLP models (roberta-base-openai-detector) to distinguish human-written text from AI-generated content.
* **Automated PDF Reporting:** Generates professional analysis reports containing timestamps, status, detection results, and detailed anomaly reasons.
* **Database Logging:** Utilizes SQLite to securely log uploads and analysis history.

---

## Tech Stack
* **Backend:** Python, Flask, SQLite
* **AI / Deep Learning:** PyTorch, Torchvision, Hugging Face Transformers, TIMM (Vision Transformer - ViT)
* **Computer Vision:** OpenCV, PIL
* **Frontend:** HTML5, Tailwind CSS, JavaScript
* **Reporting:** FPDF

---

## Installation & Running Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/mashaeell009-cpu/AICheck.git](https://github.com/mashaeell009-cpu/AICheck.git)
   cd AICheck
