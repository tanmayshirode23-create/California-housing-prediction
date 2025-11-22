# California-housing-prediction
End-to-end machine learning pipeline for California housing price prediction using Python &amp; Scikit-Learn.

California Housing Price Prediction
A fully-implemented end-to-end Machine Learning project that predicts median house prices in California using a scalable preprocessing pipeline and a trained Random Forest model.
🚀 Project Overview

This project builds a complete workflow for training + inference, including:
- Robust data preprocessing (stratified sampling, missing-value handling, scaling, encoding).
- Modular Pipeline + ColumnTransformer architecture.
- Training a Random Forest Regressor.
- Saving the model and preprocessing pipeline using Joblib.
- Generating predictions for new datasets and exporting results to CSV.

📁 Project Structure:

|-- main.py               # Training + inference script
|-- housing.csv           # California Housing dataset
|-- input.csv             # Example input data for inference
|-- output.csv            # Model predictions output
|-- model.pkl             # Saved trained model (auto-generated)
|-- pipeline.pkl          # Saved preprocessing pipeline (auto-generated)
|-- requirements.txt      # Project dependencies

⚙️ How to Use:
- Install Dependencies : pip install -r requirements.txt
- Trains the model, builds the pipeline, Automatically loads saved model + pipeline and generates: python main.py

🛠 Tech Stack:
- Python
- Pandas, NumPy
- Scikit-Learn
- Joblib

📌 Key Highlights:
- End-to-end ML flow in a single unified script
- Clean and modular preprocessing pipeline
- Reusable training and inference architecture
- Dataset-driven design with stratified sampling
