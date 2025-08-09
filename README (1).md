# ANN Regression Model - Combined Cycle Power Plant

## 📌 Project Overview
This project implements an **Artificial Neural Network (ANN)** for regression to predict the net hourly electrical energy output (EP) of a Combined Cycle Power Plant using environmental parameters such as ambient temperature, exhaust vacuum, ambient pressure, and relative humidity.

The dataset used is `Folds5x2_pp.xlsx`, which contains 9568 data points collected from a real power plant.

---

## 📂 Dataset
- **Source:** UCI Machine Learning Repository  
- **Features:**
  - **AT**: Ambient Temperature (°C)
  - **V**: Exhaust Vacuum (cm Hg)
  - **AP**: Ambient Pressure (mbar)
  - **RH**: Relative Humidity (%)
- **Target:**
  - **EP**: Net Hourly Electrical Energy Output (MW)

---

## 🛠 Tech Stack
- **Python**
- **TensorFlow / Keras**
- **Pandas, NumPy**
- **Matplotlib** (for visualization)

---

## 🚀 Steps Performed
1. **Data Loading & Preprocessing**
   - Imported dataset from Excel
   - Normalized/Scaled data for better ANN performance
2. **Model Architecture**
   - Input Layer: 4 neurons (one for each feature)
   - Hidden Layers: Dense layers with ReLU activation
   - Output Layer: 1 neuron (Linear activation for regression)
3. **Training**
   - Loss Function: Mean Squared Error (MSE)
   - Optimizer: Adam
4. **Evaluation**
   - Used test data to measure model accuracy using MSE and R² score
5. **Visualization**
   - Loss curve over epochs

---

## 📊 Results
- Model successfully predicted the **electrical energy output** with high accuracy.
- Performance metrics:
  - **MSE:** *Low value indicates good fit*
  - **R² Score:** *Close to 1 means strong predictive ability*

---

## 📦 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ccpp-ann-regression.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## 📜 License
This project is licensed under the MIT License - you are free to use, modify, and distribute it.

---

## ✨ Author
**Sambit Bhattacharjee**  
Machine Learning Enthusiast | Engineering Student
