# Power Plant Energy Prediction – ANN Regression

## 📖 About This Project
This project uses an **Artificial Neural Network (ANN)** to predict the **net hourly electrical energy output (EP)** of a Combined Cycle Power Plant based on environmental factors.
It’s a hands-on machine learning project that applies regression techniques with TensorFlow/Keras.

---

## 📂 Contents
- `combined_cycle_power_plant_ann.ipynb` → The Jupyter Notebook containing the model code
- `Folds5x2_pp.xlsx` → The dataset
- `README.md` → This file

---

## ⚙ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/power-plant-energy-prediction-ann.git
cd power-plant-energy-prediction-ann
```

### 2️⃣ Install dependencies
Make sure you have Python 3.8+ installed, then:
```bash
pip install -r requirements.txt
```
Required libraries:
- pandas
- numpy
- tensorflow
- matplotlib
- scikit-learn
- openpyxl

---

## ▶ How to Run

### Step 1 — Open the Notebook
```bash
jupyter notebook combined_cycle_power_plant_ann.ipynb
```

### Step 2 — Run all cells
- The notebook loads the dataset
- Preprocesses it (scaling)
- Builds and trains the ANN
- Evaluates performance

---

## 🧠 Model Details
- **Input Layer:** 4 neurons (Temperature, Vacuum, Pressure, Humidity)
- **Hidden Layers:** Dense layers with ReLU activation
- **Output Layer:** 1 neuron (Linear activation — regression output)
- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Adam

---

## 📊 Expected Output
- Training loss graph over epochs
- Predicted vs. Actual values comparison
- MSE and R² Score for performance evaluation

---

## 📜 License
MIT License — free to use and modify.

---

## ✍ Author
**Sambit Bhattacharjee**  
Machine Learning Enthusiast | Engineering Student
