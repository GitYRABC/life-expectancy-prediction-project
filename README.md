# 🏥 Life Expectancy Predictor

A **machine learning-powered web application** that predicts life expectancy categories (**Low / Medium / High**) based on key health and economic indicators.  
Built with Flask and scikit-learn, and deployed seamlessly on Render.

---

## 📋 Table of Contents
- [✨ Features](#-features)  
- [🛠️ Technologies](#-technologies)  
- [⚙️ Installation](#️-installation)  
- [💻 Usage](#-usage)  
- [📁 Project Structure](#-project-structure)  
- [🧠 Model Details](#-model-details)  
- [🌐 Deployment](#-deployment)  
- [🤝 Contributing](#-contributing)  
- [📜 License](#-license)  

---

## ✨ Features
- 🧠 **ML-powered predictions** using a Decision Tree Classifier  
- 📊 Trained on **real-world WHO Life Expectancy dataset**  
- 🌍 **Web-based interface** for easy access  
- 📱 **Responsive UI** for mobile & desktop  
- ✅ **Input validation** and error handling  
- 🚀 **One-click deployment** ready (Render / Heroku)  

---

## 🛠️ Technologies
- **Backend**: Python (Flask)  
- **Machine Learning**: scikit-learn, pandas, NumPy  
- **Frontend**: HTML5, CSS3  
- **Deployment**: Render, Gunicorn  
- **Model Persistence**: Pickle  

---

## ⚙️ Installation
### Prerequisites
- Python **3.8+**  
- pip package manager  

### Steps
```bash
# Clone the repository
git clone https://github.com/your-username/life-expectancy-predictor.git
cd life-expectancy-predictor

# Install dependencies
pip install -r requirements.txt

# Run the Flask server
python app.py
