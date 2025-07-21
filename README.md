# 🔧 Code Generation for Hardware using LLMs

This project explores the use of **Large Language Models (LLMs)** to automatically generate code for embedded systems and robotics platforms like **Arduino** and **KUKA KRL**.

## 📌 Project Highlights

- ✅ Fine-tuned LLMs for Arduino and KUKA code generation
- 🧠 Supports prompt-to-code generation
- 📊 Evaluation of code accuracy and execution
- 📁 User interface built with Gradio

## 📂 Folder Structure


## 🚀 How to Run

> **Note:** All steps are demonstrated in the `CGHLLM.ipynb` notebook.

1. Open notebook in Google Colab or Jupyter
2. Install dependencies (Transformers, Gradio)
3. Load model from `fine-tuned-*` folders
4. Provide input prompt and generate hardware code

## 📘 Dependencies

- Python 3.8+
- `transformers`
- `gradio`
- `torch`

## 🤖 Models Used

- Fine-tuned [DeepSeek-Coder](https://huggingface.co/deepseek-ai/deepseek-coder-1.3b-base)
- Custom datasets: Arduino & KUKA prompts

## 📈 Results

- 90%+ accuracy for basic Arduino operations
- ~82% for multi-step KUKA motion scripts
- Evaluation includes syntax checks and simulated runs

## 👨‍💻 Authors

- Shivaprakash G

---

