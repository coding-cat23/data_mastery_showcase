# 🧴 Sephora Product Reviews Analysis 🧴  

## 📖 Overview
This Jupyter Notebook explores a comprehensive dataset of Sephora beauty products and user reviews, with a special focus on **skincare** items. The dataset includes product details such as brand, price, rating, and size, as well as user reviews with ratings, recommendations, and personal attributes (e.g., skin type, hair color). The primary goal is to analyze the textual user reviews to uncover trends, sentiments, and themes.

---

## 🎯 Objectives
1. **Exploratory Data Analysis (EDA):**
    - Understand the distribution of ratings, review counts, and product popularity.
    - Analyze user characteristics (e.g., skin type, tone) in relation to product feedback.

2. **Natural Language Processing (NLP):**
    - Use a large language model (LLM) to:
      - Perform **sentiment analysis** on the reviews.
      - Extract **common themes** and **frequent concerns/praises** across products.

---

## 📊 Key Features
- **EDA Visualizations:**
  - Distribution of product ratings.
  - Top 20 most loved products.
  - Average rating by brand.
  - Skin type vs. rating distribution.
  - Review volume trends over time.
  - Price vs. average rating correlation.

- **NLP Analysis:**
  - Sentiment analysis of reviews using Google Generative AI.
  - Extraction of key themes from user reviews.

---

## 📂 Dataset Information
- **Product Info Dataset:**
  - Contains details about products such as name, brand, price, rating, and size.
- **Product Reviews Dataset:**
  - Includes user reviews with attributes like rating, helpfulness, skin type, and review text.

**Dataset Source:** [Sephora Products and Skincare Reviews on Kaggle](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews)  
**Collected:** March 2023  

---

## 🔧 Tools & Libraries
- **Pandas**, **NumPy** for data handling  
- **Matplotlib**, **Seaborn** for visualization  
- **Google Generative AI API** for advanced NLP tasks  

---

## 🧠 Why Use LLMs?
Traditional sentiment tools often miss the nuance in human-written reviews. By using a modern LLM, this project captures:
- Subtle emotions,
- Product-specific language (e.g., "non-comedogenic", "absorbs well"),
- Themes around effectiveness, packaging, price perception, and more.

---

## 🚀 How to Run
1. Clone the repository and open the Jupyter Notebook.
2. Ensure the required libraries are installed:
    ```bash
    pip install pandas numpy matplotlib seaborn google-generativeai
    ```
3. Replace the placeholder API key with your actual Google Generative AI API key.
4. Run the notebook cells sequentially to reproduce the analysis.

---

## 📌 Results
- Insights into customer preferences and satisfaction.
- Identification of popular products and brands.
- Trends in user reviews based on skin type, price, and other factors.
- Sentiment and theme analysis of user reviews.

---

## 📜 License
This project is for educational purposes only. The dataset is sourced from Kaggle and is subject to its terms of use.

---

## 🤝 Acknowledgments
- Kaggle for providing the dataset.
- Google Generative AI for enabling advanced NLP analysis.
