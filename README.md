# 🎷 Vibe Navigator

Vibe Navigator is an intelligent audio-driven experience recommender built using machine learning and data science. It processes audio inputs and recommends moods, music styles, or locations, helping users discover content and destinations aligned with their current vibes.

---

## 🚀 Features

* 🎧 **Voice Input Recognition**
* 🎼 **Mood-based Music or Location Recommendation**
* 🧠 **Machine Learning Powered Backend**
* 🌍 **Integration with Google Maps / APIs**
* 📂 Supports `.env` for secure API management

---

## 📁 Project Structure

```
Vibe_Navigator/
│
├── Code/
│   ├── Final_code.ipynb          # Main notebook with model logic
│   ├── Test_and_needed.ipynb     # Testing and supporting code
│   ├── requirements.txt          # All dependencies
│   ├── .env                      # Environment variables (ignored in Git)
│   └── readme.md                 # Project-specific notes
│
├── Requirement/
│   └── Problem statement.pdf     # Official problem statement
└── README.md                     # This file
```

---

## 🔧 Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/Mithun017/Vibe_Navigator.git
cd Vibe_Navigator/Code
```

2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install the required packages**

```bash
pip install -r requirements.txt
```

4. **Create a `.env` file and add your API keys (e.g., Groq, OpenAI)**

```bash
touch .env
# Inside .env:
GROQ_API_KEY=your_api_key_here
```

---

## 🧪 Usage

Open the main notebook and run it step-by-step:

```bash
jupyter notebook Final_code.ipynb
```

Or use:

```bash
python Final_code.py  # If converted to .py
```

---

## 🛡️ Security Note

* Secrets such as API keys should be **kept in `.env`** and **never committed**.
* `.env` is included in `.gitignore` by default.

---

## 🧠 Tech Stack

* Python
* Jupyter Notebook
* Machine Learning (e.g., TensorFlow / Scikit-Learn)
* Audio Processing (e.g., librosa, pyaudio)
* Google Maps API / External APIs
* dotenv

---

## 📌 Future Enhancements

* Deploy as a web app (Flask / FastAPI)
* Add real-time speech-to-text
* Integrate emotion detection
* Improve recommendation engine with deep learning

---

## 🙇‍♂️ Author

**Mithun S**
[GitHub](https://github.com/Mithun017) 
