# AI-Chemist-Pioneering-the-Future-of-Chemical-Science-with-Gemini-Vision-Pro
Absolutely — here’s a clean, well-structured `README.md` you can use for your Health Management / AI Chemist App project:

---

# 📱 AI Chemist App — Health Management App

Welcome to the **AI Chemist App**, an intelligent health management tool powered by Google's Gemini AI Vision API. This app analyzes images of tablets or medicine strips and provides detailed information about each drug — including its uses, applications, and key characteristics — just by uploading an image.

---

## 📝 Features

* 📸 Upload images of medicine or tablet strips.
* 🧠 AI-powered analysis using **Google Gemini Vision API**.
* 📝 Returns comprehensive details of each tablet:

  * Name & appearance
  * Use cases & applications
  * Key properties & distinguishing features
* 🖼️ Displays uploaded image preview.
* 🔒 Secure API key management using `.env` file.

---

## 🚀 Tech Stack

* **Python**
* **Streamlit** — Interactive web UI
* **Google Generative AI API (Gemini 2.0 Flash)**
* **PIL (Python Imaging Library)** — Image handling
* **dotenv** — Environment variable management

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-chemist-app.git
cd ai-chemist-app
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set up `.env` File

Create a `.env` file in the root directory and add your Google API key:

```bash
GOOGLE_API_KEY=your_google_api_key_here
```

---

## 🖥️ How to Run

```bash
streamlit run app.py
```

---

## 📸 Usage

1. Launch the app.
2. Enter any additional text prompt if needed.
3. Upload an image containing medicine tablets.
4. Click **"Tell me"**.
5. View AI-generated details about each tablet in the image.

---

## 📖 Example Prompt

```
Identify the tablets and provide their use cases and possible side effects.
```

---

## 📂 Project Structure

```
├── app.py               # Main Streamlit application
├── .env                 # Environment variables
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
```

---

## ✅ Requirements

* Python 3.9+
* Google API key with access to Gemini AI API
* Stable internet connection



## 🤝 Acknowledgments

* [Google Generative AI API](https://ai.google.dev/)
* [Streamlit](https://streamlit.io/)
* [Python PIL](https://pillow.readthedocs.io/en/stable/)

---
