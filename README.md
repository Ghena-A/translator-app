# translator-app
# 🌍 Multilingual Translator App

A simple and elegant multilingual translation web app built with **Gradio** and **MarianMT** models from the **Hugging Face Transformers** library.  
This project allows users to translate text between **English**, **Arabic**, and **French** seamlessly.

---

## 🚀 Demo

👉 **Try it on Hugging Face Spaces:** [Click here to open the app]([PUT-YOUR-HUGGINGFACE-LINK-HERE](https://huggingface.co/spaces/ghenaa/translator-app))

---

## 🧠 About the Project

This translator uses **MarianMT** models provided by [Helsinki-NLP](https://huggingface.co/Helsinki-NLP), which are pre-trained machine translation models for multiple languages.

It supports the following translation directions:

- 🇬🇧 English → 🇫🇷 French  
- 🇫🇷 French → 🇬🇧 English  
- 🇬🇧 English → 🇸🇦 Arabic  
- 🇸🇦 Arabic → 🇬🇧 English  

The app automatically loads the appropriate model depending on the selected translation direction.

---

## 🧩 Features

✨ Multilingual support (English, Arabic, French)  
⚡ On-demand model loading (loads models only when needed)  
🎨 Beautiful and simple **Gradio UI**  
🪶 Lightweight and easy to deploy on Hugging Face Spaces  

---

## 🛠️ Technologies Used

- 🐍 **Python 3.9+**  
- 🤗 **Transformers (Hugging Face)**  
- 🎛️ **Gradio**  
- 🔥 **PyTorch**

---

## 📦 Installation & Usage

### 🧱 1. Clone the repository
```bash
git clone https://github.com/your-username/translator-app.git
cd translator-app
