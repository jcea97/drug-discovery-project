Acetylcholinesterase pIC50 Prediction App 🧬

This is a bioinformatics project focused on predicting the bioactivity (pIC50 values) of compounds targeting acetylcholinesterase (AChE), a key enzyme involved in Alzheimer's disease.

Project Overview

Goal: Develop a machine learning model to predict AChE inhibitors based on molecular descriptors.

Data Source: ChEMBL bioactivity data.

Implementation: The app is built using Streamlit, with molecular descriptors calculated via PaDEL-Descriptor.

Features

✔ Upload a file with molecular structures.

✔ Compute molecular descriptors using PaDEL-Descriptor.

✔ Predict pIC50 values using a pre-trained model.

✔ Download the prediction results.


Folder Structure

📂 acetylcholinesterase_pIC50_prediction_app
 ├── app.py                  # Streamlit app
 ├── model.pkl               # Pre-trained ML model
 ├── descriptor_list.csv      # Selected molecular descriptors
 ├── example_input.txt        # Sample input file
 ├── PaDEL-Descriptor/        # Descriptor calculation tool


Installation & Usage

1. Clone the repository
   
git clone https://github.com/yourusername/drug-discovery-project.git

cd drug-discovery-project/acetylcholinesterase_pIC50_prediction_app


3. Run the app
   
streamlit run app_2.py


