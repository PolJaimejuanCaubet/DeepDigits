# 📷 Image Clasificator 

## 📌 Project Overview

This repository contains a Machine Learning model for classifcate images match outc


## 📂 Dataset

The dataset used for training is located at:

>LeaguesDataset/LaLiga.csv

It includes match statistics such as:

- Home Team & Away Team
- Goals scored by each team
- Match date (converted into numerical features)
- Final match result (encoded as a categorical variable)

## 🛠️ Technologies Used

- **Python** 🐍
- **Pandas** (Data manipulation)
- **Scikit-learn** (Machine Learning algorithms)

## 🚀 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/PolJaimejuanCaubet/DeepDigits.git
   cd DeepDigits

2. Install dependencies:

   You shoud first have installed `uv` in your global python dependencies, *if not* the case follow this steps:
   ```bash
   pip install uv

   Then, install project dependencies such as pandas, numpy or maplotlib among others.
   ```bash 
   uv sync
   
3. Run the notebook:

   Open and execute the steps inside **Football_Predictor.ipynb**.

## 🔍 Model Training & Prediction

The model follows these steps:

**1.** Load and clean the dataset.

**2.** Convert categorical values to numerical ones using LabelEncoder.

**3.** Split the data into training and validation sets.

**4.** Train a Decision Tree Regressor and evaluate it using Mean Absolute Error (MAE).

**5.** Optimize the model by tuning the number of leaf nodes.

**6.** Convert numerical predictions back to categorical results.

## 📊 Example Prediction Output

>Match: Real Madrid vs Barcelona - Predicted Result: Draw

>Match: Sevilla vs Atletico Madrid - Predicted Result: Home Win

## 📌 Future Improvements

- **Implement** Random Forest for better accuracy.

- **Add** more detailed match statistics.

- **Extend** predictions to multiple leagues.

## 🤝 Contributing

Feel free to fork this repository and **submit pull requests** to improve the model! 🚀