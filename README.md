# Insurance Purchase Prediction using Neural Network

This project predicts whether a person will buy insurance based on their age and affordability using a simple neural network built with TensorFlow Keras.

## 📂 Dataset
- File: `insurance_data.csv`
- Columns:
  - `age`
  - `affordibility`
  - `bought_insurance` (0 or 1)

## 🧠 Model
- Framework: TensorFlow / Keras
- Architecture: Sequential model with one Dense layer (sigmoid activation)
- Loss: Binary Crossentropy
- Optimizer: Adam

## ⚙️ Steps
1. Load and preprocess dataset
2. Scale features
3. Split into train and test sets
4. Build and train neural network
5. Evaluate model performance
6. Predict and extract learned weights