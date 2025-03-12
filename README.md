# Forest Fire Prediction using Linear Regression

## 🌿 Project Overview
This project predicts the area of forest fires in Algeria using linear regression. The model is trained on the **Algerian Forest Fires Dataset** and deployed via Flask on Render.

## 🚀 Live Demo
Check out the live app here: [Forest Fire Prediction](https://algeria-forest-fire-fj8i.onrender.com/predictdata)

## 📊 Dataset
- **Dataset:** Algerian Forest Fires Dataset
- **File:** `dataset/Algerian_forest_fires_cleaned_dataset.xls`
- The dataset contains meteorological data and information about the area affected by forest fires.

## 🔧 Project Structure
```
├── dataset
│   └── Algerian_forest_fires_cleaned_dataset.xls
├── models
│   ├── Ayu_ridge.pkl
│   └── Ayu_scaler.pkl
├── notebook
│   ├── Ayush ALgeria.ipynb
│   └── Ayush_modeling.ipynb
├── templates
│   ├── home.html
│   └── index.html
├── app.py
├── requirements.txt
└── README.md
```

## 📦 Installation

1. **Clone the repository:**
```bash
git clone <your-repository-link>
cd Forest-Fire--main
```

2. **Create a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

## 🚀 Running the App

1. **Run the Flask app:**
```bash
python app.py
```

2. **Access the app locally:**
- Open your browser and go to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

## 🏋️ Model Details
- **Algorithm:** Ridge Regression
- **Scaler:** Used to normalize data before feeding it into the model
- **Trained models:** Stored in the `models/` folder

## 🌟 How to Use
- **Homepage:** Enter meteorological data (temperature, wind speed, etc.)
- **Predict:** The app returns the predicted area affected by the forest fire

## ✨ Deployment
- **Platform:** Render
- **Deployment link:** [Forest Fire Prediction App](https://algeria-forest-fire-fj8i.onrender.com/predictdata)

## 📧 Contact
For any questions or collaborations, feel free to reach out via LinkedIn or email.

---

Feel free to tweak the content based on your preferences!

