# Week 2 Tasks - Data Science & Analytics Internship

This folder contains the projects, Jupyter Notebooks, datasets, and generated technical reports completed during **Week 2** of the Data Science Internship.

---

## 📂 Folder Structure & Projects

### 1. Task 4: Sales Data Analysis Dashboard (`Task_4_Sales_Data_Analysis_Dashboard/`)
* **Objective:** Clean, preprocess, and analyze transactional sales data to extract business trends and present insights through data visualization[cite: 1].
* **Dataset:** Kaggle Sales Dataset (Initial: 9,994 records, 19 columns; Cleaned: 9,993 records after removing 1 duplicate)[cite: 1].
* **Key Metrics & Findings:**
  * **Total Sales:** $2,296,919.49 | **Total Profit:** $286,409.08[cite: 1].
  * **Top Category:** *Technology* generated the highest sales ($836,154.03) and profit ($145,454.95)[cite: 1].
  * **Top Region:** *West* recorded the highest regional performance across sales, profit, and quantity[cite: 1].
  * **Key Insight:** High sales volume does not guarantee high profitability (e.g., top customer by sales, Sean Miller, recorded a negative total profit)[cite: 1].
* **Deliverables:** Jupyter Notebook (`.ipynb`), cleaned dataset (`Sales_data.csv`), and a detailed Word report (`Task_1_Sales_Data_Analysis_Dashboard_Report.docx`)[cite: 1].

---

### 2. Task 5: Sentiment Analysis on Twitter Data (`Task_5_Sentiment_Analysis/`)
* **Objective:** Build an end-to-end natural language processing (NLP) pipeline to clean, preprocess, and classify tweet sentiments into *Positive*, *Neutral*, or *Negative* classes[cite: 2].
* **Dataset:** Pre-collected Twitter dataset (Initial: 74,682 rows; Final cleaned dataset: 57,714 rows)[cite: 2].
* **Methodology & Model:**
  * Text cleaning included lowercasing, removal of URLs, mentions, punctuation, and stopwords, paired with WordNet lemmatization[cite: 2].
  * Feature extraction utilized **TF-IDF Vectorizer** (unigrams and bigrams, up to 10,000 features)[cite: 2].
  * Classification was performed using a **Logistic Regression** model trained on an 80:20 stratified split[cite: 2].
* **Model Performance:**
  * **Test Accuracy:** 79.23%[cite: 2]
  * **Weighted F1-Score:** 79.16%[cite: 2]
  * **Key Insight:** *Negative* sentiment achieved the highest class-level F1-score (0.82), while *Neutral* tweets were the hardest class to distinguish due to overlap with positive and negative classes[cite: 2].
* **Deliverables:** Jupyter Notebook (`.ipynb`), cleaned dataset (`Sentiment_Analysis_Cleaned.csv`), and a comprehensive report (`Task_2-Sentiment_Analysis_Report.docx`)[cite: 2].

---

### 3. Task 6: Customer Segmentation Using Clustering (`Task_6_Customer_Segmentation/`)
* **Objective:** Apply unsupervised machine learning (K-Means clustering) to segment customers based on behavioral and demographic attributes[cite: 3].
* **Dataset:** Mall Customers Dataset (200 records, 5 columns)[cite: 3].
* **Methodology:**
  * Features used: *Age*, *Annual Income (k$)*, and *Spending Score (1-100)*, normalized using `StandardScaler`[cite: 3].
  * **Optimal Clusters:** Evaluated via the Elbow Method, selecting **$K = 6$** optimal clusters[cite: 3].
* **Key Customer Segments Identified:**
  * **Cluster 3:** High-income, high-spending premium customers (39 customers)[cite: 3].
  * **Cluster 2:** High-income, low-spending customers (33 customers) — ideal for targeted engagement[cite: 3].
  * **Cluster 4:** Younger, low-income, high-spending customers (23 customers)[cite: 3].
* **Deliverables:** Jupyter Notebook (`.ipynb`), clustered data export (`Customer_Segmentation_Clusters.csv`), 2D/3D visualizations, and the project report (`Customer_Segmentation_Report.docx`)[cite: 3].

---

## 🛠️ Technologies & Libraries Used
* **Languages:** Python[cite: 1, 2, 3]
* **Data Manipulation & Math:** Pandas, NumPy[cite: 1, 2, 3]
* **Machine Learning & NLP:** Scikit-learn, NLTK[cite: 2, 3]
* **Data Visualization:** Matplotlib, Seaborn[cite: 1, 2, 3]
* **Environment:** Jupyter Notebook[cite: 1, 2, 3]