# 🌾 Crop Recommendation System: A Data Science Project

## 💡 Project Goal & Importance
This project implements an **end-to-end Machine Learning-based Crop Recommendation System** that leverages environmental and soil condition data to recommend the most suitable crop for cultivation.

By providing optimal crop suggestions based on measurable parameters (N, P, K, pH, Temperature, etc.), this system:
* **Enhances Productivity:** Supports farmers and policymakers in making data-driven agricultural decisions.
* **Optimizes Resources:** Reduces resource waste (water, fertilizer) and supports sustainable farming practices.
* **Addresses Complexity:** Uses machine learning to model the intricate, non-linear dependencies between multiple environmental factors.

---

## ⚙️ Project Methodology: The Data Science Lifecycle
This project follows a complete Data Science lifecycle, demonstrating expertise in:
1.  **Problem Definition** & **Data Collection**
2.  **Data Exploration** and **Preprocessing** (Handling Missing Values, Scaling, Encoding)
3.  **Model Selection, Training, & Evaluation** (Using multiple classifiers for comparison)
4.  **Model Persistence** (Saving model and preprocessor for deployment)

## 📊 Dataset
| Field | Details |
| :--- | :--- |
| **Source** | Reputable agricultural data repository |
| **Content** | Key soil nutrients (N, P, K, pH) and climatic parameters (Temperature, Rainfall, Humidity) used to predict 22 optimal crop types. |
| **Link** | [Crop Recommendation Dataset (Kaggle)](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset) |

---

## 💻 How to Run the Notebook (Google Colab)

The entire project is contained within the Colab notebook. **No complex environment setup is required.**

1.  **Open the Notebook:** Click the badge below to open the Colab file directly.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<[INSERT_YOUR_NOTEBOOK_GITHUB_URL_HERE](https://github.com/KalihoseMigisha/crop-recommender-system/commit/8975368bd1300a4b77469fb6244e4b6f9fb79d08#diff-92a48ce834837e83df796223a20b7c106e736f972c3cb086b79d647ca916a2e2)>) 

2.  **Install Dependencies:** Run the cell containing the installation command:
    ```bash
    !pip install numpy pandas matplotlib seaborn scikit-learn
    ```
3.  **Execute:** Run all cells sequentially (Runtime > Run all).

### 🗃️ Key Project Steps Covered in the Notebook

| Section | Key Activities |
| :--- | :--- |
| **Exploratory Data Analysis (EDA)** | Feature correlation, distribution analysis, and relationship between soil nutrients and crop type. |
| **Preprocessing** | Target variable encoding, feature scaling using **MinMaxScaler/StandardScaler**. |
| **Model Training** | Comparison of **Logistic Regression, Random Forest, Decision Tree, KNN, and SVM** to select the best-performing model. |
| **Prediction** | Building and testing the final predictive function. |
| **Persistence** | Saving the final model and preprocessor using `pickle` or `joblib`. |

---

## 📈 Conclusion and Future Work

The **Random Forest** classifier was found to be the most accurate model, demonstrating the power of ensemble learning in modeling complex agricultural dependencies.

**Future Enhancements:**
* Integrate real-time weather APIs for adaptive recommendations.
* Expand the dataset with location/seasonal parameters.
* Deploy the final model as a web or mobile application (e.g., using Streamlit or Flask).

---

## 👨‍💻 Author & License

| Detail | Contact |
| :--- | :--- |
| **Author** | Kalihose Migisha |
| **Email** | Kalihosemigisha@gmail.com |
| **GitHub** | [@KalihoseMigisha](https://github.com/KalihoseMigisha) |
| **X (Twitter)** | [@KalihoseMigisha](https://twitter.com/KalihoseMigisha) |

**License:** This project is licensed under the **MIT License**.
