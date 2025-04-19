# HCE-706-Slot-1-Team-2
# 🕵️‍♀️ Step-Fraud-Review-Detector

A project aimed at detecting **fraudulent product reviews** using NLP techniques, structured data processing, and robust feature engineering. The repository contains datasets, preprocessing scripts, schema design files, and notebooks to support review authenticity detection and analysis.


## 📂 Project Structure

.
├── Dataset/
│   ├── FRDDS.csv
│   └── shuffleFRDDS.csv
│
├── Week1/
│   └── (Initial planning: wireframes, task division, etc.)
│
├── Week2/
│   ├── Amazon_reviews_2023_(clean).ipynb
│   ├── Fake_Review_Detection_Dataset_(Small).ipynb
│   ├── M-2.1 List of Data Sources.xlsx
│   ├── M-2.2 Data Repository - Raw Extracts and Datasets.xlsx
│   ├── M-2.3 - ER Diagram.docx
│   ├── M-2.4 - Data Dictionary.xlsx
│   └── M-2.5 - Database Design.docx
│
└── README.md

---

## 📦 Datasets

### `FRDDS.csv`
Original dataset containing product reviews with labels for fake and genuine reviews.

### `shuffleFRDDS.csv`
Randomly shuffled version of `FRDDS.csv` used for evaluation and cross-validation purposes.

---

## 📊 Notebooks & Analysis

### 🔹 `Amazon_reviews_2023_(clean).ipynb`
- Focuses on preprocessing of the Amazon Reviews dataset.
- Steps:
  - Data Loading
  - Initial Data Cleaning
  - Text Processing
  - Feature Engineering
  - Table Creation
  - Final Data Cleaning

### 🔹 `Fake_Review_Detection_Dataset_(Small).ipynb`
- Contains processing steps for a smaller subset of the Fake Review Detection Dataset.
- Steps:
  - Data Loading
  - Initial Data Cleaning
  - Text Processing
  - Feature Engineering

---

## 🗂️ Documentation & Design Files

The following files document the backend planning, schema, and structure of the database and data flow:

- M-2.1 - List of Data Sources.xlsx – Reference list of all data sources used.
- M-2.2 - Data Repository - Raw Extracts and Datasets.xlsx – Detailed dataset descriptions.
- M-2.3 - ER Diagram.docx – Entity Relationship diagram for database schema.
- M-2.4 - Data Dictionary.xlsx – Attribute descriptions and types.
- M-2.5 - Database Design.docx – Complete backend schema design plan.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Jupyter Notebook
- Excel
- Natural Language Processing (NLP)
- Git & GitHub

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Step-Fraud-Review-Detector/HCE-706-Slot-1-Team-2.git
   cd HCE-706-Slot-1-Team-2
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy
   ```

3. **Open notebooks**
   Use Jupyter or Google Colab to open and run `.ipynb` files in the `Week2` folder.

---

## 👥 Contributors

- [Aankit Satapathy](https://github.com/aankitsatapathy)
- [Medha Srivastava](https://github.com/khushicbilko)
- [Chettim Chetty Hemasri](https://github.com/HEMASRI2175)
- [Nagoor](https://github.com/nagoor107)

---

## 📌 Project Status

- ✅ Data Collection
- ✅ Initial Preprocessing & Cleaning
- ✅ Schema Design and Documentation
- ⏳ Model Building and Evaluation (In Progress)

---
