# 🧬 Acetylcholinesterase pIC50 Prediction App 

This is a **bioinformatics project** focused on predicting the bioactivity (**pIC50 values**) of compounds targeting **acetylcholinesterase (AChE)**, a key enzyme involved in **Alzheimer's disease**. Additionally, this repository includes Google Colab notebooks containing the complete workflow for building machine learning models for the same task.

## 📌 Project Overview
- **Goal:** Develop a **machine learning model** to predict **AChE inhibitors** based on molecular descriptors.
- **Data Source:** ChEMBL bioactivity data.
- **Implementation:** Built using **Streamlit**, with molecular descriptors computed via **PaDEL-Descriptor**.

## 🚀 Features
✔ **Upload a file** with molecular structures.  
✔ **Compute molecular descriptors** using PaDEL-Descriptor.  
✔ **Predict pIC50 values** using a pre-trained ML model.  
✔ **Download the results** as a CSV file.  

## 📁 Folder Structure

```
📂 acetylcholinesterase_pIC50_prediction_app
 ├── 📄 app_2.py                                     # Streamlit app
 ├── 📄 acetylcholinesterase_model.pkl               # Pre-trained ML model
 ├── 📄 descriptor_list.csv                          # Selected molecular descriptors
 ├── 📄 example_acetylcholinesterase.txt             # Sample input file
 ├── 📂 PaDEL-Descriptor/                            # Descriptor calculation tool
```


## 🛠 Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/jcea97/drug-discovery-project.git
cd drug-discovery-project/acetylcholinesterase_pIC50_prediction_app
```

### 2️⃣ Run the app

```bash
streamlit run app_2.py
```

## Application Preview

Here is how the application looks when running with the example .txt:

![App Interface Pre-Analysis]("C:\Users\Jesús Cea García\Downloads\prediciton_pre.png")
![App Interface Post-Analysis]("C:\Users\Jesús Cea García\Downloads\prediciton_post.png")


