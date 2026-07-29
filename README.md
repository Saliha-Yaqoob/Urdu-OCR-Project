# Urdu OCR - Code Saviours SI-26

## 📌 Project Overview
This project is an **Urdu Optical Character Recognition (OCR)** system built as part of the **Code Saviours ML/AI Internship (Batch SI-26)**. It utilizes the VisionEncoderDecoder architecture to extract Urdu text from printed image snippets.

---

## 🛠️ How It Works
1. **Model**: Powered by `microsoft/trocr-base-printed` via Hugging Face Transformers.
2. **Preprocessing**: Images are normalized using `ViTImageProcessor`.
3. **Inference**: Text tokens are generated using `VisionEncoderDecoderModel` and decoded with `RobertaTokenizer`.
4. **Interface**: Interactive UI built using **Gradio**.

---

## 🚀 Live Demo & Deployment
- **Interactive Gradio App**: Created using Gradio Interface.
- **Hugging Face Space**: Deployed at `Saliha1845/urdu-ocr-codesaviours-si26-saliha`.

---

## 💻 How to Run Locally

### 1. Clone the Repository
```bash
git clone [https://github.com/Saliha-Yaqoob/Urdu-OCR-Project.git](https://github.com/Saliha-Yaqoob/Urdu-OCR-Project.git)
cd Urdu-OCR-Project
