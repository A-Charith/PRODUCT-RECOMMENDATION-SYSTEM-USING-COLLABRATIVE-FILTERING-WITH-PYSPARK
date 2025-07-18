# 🛍️ Product Recommendation System using Collaborative Filtering with PySpark

This project implements a **Product Recommendation System** using **Collaborative Filtering** techniques powered by **Apache Spark (PySpark)**. It aims to recommend personalized products to users based on their previous interactions and similarities with other users.

## 📊 Dataset

- **Source**: [Amazon Ratings Dataset on Kaggle](https://www.kaggle.com/datasets/skillsmuggler/amazon-ratings/data)
- **Size**: ~1 million ratings
- **Attributes**:
  - `userId`: Unique identifier for users
  - `productId`: Unique identifier for products
  - `rating`: Rating given by the user (1-5)
  - `timestamp`: Time when the rating was given
📦 Dataset used: Amazon Ratings on Kaggle

## 📁 Repository Structure

/PRODUCT-RECOMMENDATION-SYSTEM-USING-COLLABRATIVE-FILTERING-WITH-PYSPARK
├── Project_code.ipynb # Main Jupyter Notebook with code implementation
├── big_data_project_report.pdf # Detailed project report
├── big_data_ppt[1].pptx # Presentation slides
└── README.md # This file


## 🚀 Technologies Used

- **PySpark (Apache Spark for Python)**
- **ALS (Alternating Least Squares)** Collaborative Filtering Algorithm
- **Jupyter Notebook**
- **Pandas, Matplotlib** for data analysis & visualization

## 🛠️ Key Features

- Preprocessing of large-scale Amazon product rating data
- Splitting data into training and testing sets
- Building a recommendation model using PySpark's `ALS` algorithm
- Evaluation using RMSE (Root Mean Square Error)
- Generating top-N product recommendations for a user

## 📌 How to Run

1. **Install dependencies**:
   Ensure Spark is installed and configured correctly. You can use Google Colab or local Jupyter with PySpark configured.

2. **Run the notebook**:
   Open `Project_code.ipynb` in Jupyter/Colab and execute the cells step by step.

3. **Replace file paths**:
   If you're running locally, update the dataset path according to your system location.

## 📈 Evaluation

- The model is evaluated using **Root Mean Square Error (RMSE)**.
- Recommendation examples and model accuracy are included in the notebook and report.

## 📄 Project Documents

- `big_data_project_report.pdf` – In-depth documentation of methodology, implementation, and results.
- `big_data_ppt[1].pptx` – Slide deck summarizing project goals, steps, and outcomes.

## 👨‍💻 Author

- **A. Charith**  
  GitHub: [@A-Charith](https://github.com/A-Charith)

## 📅 Last Updated

July 2025

## 📜 License

This project is for academic and learning purposes. Dataset belongs to respective copyright holders.
