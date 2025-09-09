# 📰 News Topic Classifier Using BERT  

## 📌 Objective  
This project fine-tunes a **BERT transformer model** to classify **news headlines** into topic categories.  
The aim is to leverage transfer learning for efficient and accurate text classification.  

---

## 📊 Dataset  
- **AG News Dataset** (available on [Hugging Face Datasets](https://huggingface.co/datasets/ag_news))  
- Dataset Details:  
  - **Training Samples:** 120,000  
  - **Test Samples:** 7,600  
  - **Categories:**  
    - 🌍 World  
    - 🏅 Sports  
    - 💼 Business  
    - 🔬 Science/Technology  

---

## ⚙️ Project Workflow  

### 1. Data Preprocessing  
- Tokenized and preprocessed text using Hugging Face **Tokenizer**  
- Converted dataset into PyTorch-compatible DataLoader  

### 2. Model Fine-tuning  
- Base Model: **bert-base-uncased**  
- Fine-tuned using Hugging Face **Transformers** library  
- Optimized with learning rate scheduling and gradient clipping  

### 3. Evaluation  
- Metrics: **Accuracy** & **F1-Score**  
- Results:  
  - ✅ Accuracy: ~95%  
  - ✅ F1-Score: **95%**  

### 4. Deployment  
- Deployed using **Streamlit** and **Gradio** for real-time interaction  
- Users can input custom news headlines and receive predicted categories instantly  

---

## 🚀 Skills Gained  
- 🧠 Natural Language Processing (NLP) using Transformers  
- 🔄 Transfer Learning & Fine-tuning  
- 📊 Evaluation Metrics for Text Classification  
- 🌐 Lightweight Model Deployment Gradio  


