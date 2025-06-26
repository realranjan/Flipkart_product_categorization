# Ecommerce Product Categorization

This repository contains the solution to the **Ecommerce Product Categorization** challenge. The project focuses on developing an efficient text classification model to categorize eCommerce products based on their descriptions.

## Problem Statement

In the fast-paced eCommerce industry, accurate product categorization is critical for improving customer experience, reducing search friction, and enhancing product discoverability. The challenge lies in handling ambiguities, unconventional naming conventions, and multi-language data. This project addresses these challenges with an innovative and scalable solution.

## Approach

1. **Data Handling:**
   - Loaded and explored the dataset for valuable insights.
   - Addressed class imbalance using stratified sampling and SMOTE oversampling.
   
2. **Text Preprocessing:**
   - Used **NLTK** for natural text preprocessing.
   - Converted textual descriptions to numerical features using techniques like **TF-IDF** and **Word2Vec**.
   
3. **Model Development:**
   - Performed train-test split using stratified sampling.
   - Trained and evaluated various deep learning models:
     - Sequential models
     - Random classifiers
   - Fine-tuned the models using hyperparameter optimization to improve performance.

4. **Evaluation:**
   - Compared models based on their train and test accuracy.
   - Selected **Sequential Model** as the best-performing model with a test accuracy of **98%**.

## Key Insights

- **Price Correlation:** Higher retail prices correspond to higher discount prices.
- **Top Sellers:** Clothing and Jewelry are the highest-selling categories.
- **Low Sellers:** Bags, Wallets & Belts, and Baby Care show the lowest sales.
- **Jewelry Pricing:** Jewelry has the highest average retail and discounted price.

## Results

| Model                | Train Accuracy | Test Accuracy |
|----------------------|----------------|---------------|
| Sequential Model     | 97.65%         | 98.08%        |
| Random Classifier    | 99.99%         | 96.04%        |

### Combined Model Performance

- The combined model (Sequential Model and Random Classifier) achieved:
  - **Test Accuracy**: 98.44%
  - **F1 Score**: 98.43%
- The classification report highlights:
  - High precision and recall across most classes.
  - Weighted average F1-score of **98%**, demonstrating balanced performance.
- The ensemble model effectively handles class imbalances while maintaining high predictive accuracy.

## Benefits of Accurate Categorization

1. **Improved Customer Experience:** Enhanced browsing and navigation for seamless product discovery.
2. **Increased Product Discoverability:** Broader exposure to relevant products, boosting sales and satisfaction.
3. **Reduced Search Friction:** Faster and frustration-free searches, reducing abandoned sessions.

## Conclusion and Future Work

The accurate categorization model developed in this project is a crucial tool for improving eCommerce platforms. Future enhancements may include:
- Exploring advanced deep learning models.
- Integrating visual features, such as product images, for better accuracy.

## Project Highlights for Resume (XYZ Storytelling)

- **Situation:** Faced with the challenge of accurately categorizing eCommerce products to improve customer experience and product discoverability in a large, imbalanced, and noisy dataset.
- **Action:**
  - Engineered robust data preprocessing pipelines using NLTK, TF-IDF, and Word2Vec to convert raw product descriptions into meaningful features.
  - Addressed class imbalance with stratified sampling and SMOTE, ensuring fair model training.
  - Developed, trained, and fine-tuned deep learning models (Sequential Model, Random Classifier) and implemented ensemble techniques for optimal performance.
  - Conducted comprehensive model evaluation and hyperparameter tuning to maximize accuracy and F1-score.
- **Result:**
  - Achieved a test accuracy of **98.44%** and a weighted F1-score of **98.43%** with the ensemble model, outperforming baseline classifiers.
  - Improved product categorization accuracy, directly contributing to enhanced customer experience and increased product discoverability for eCommerce platforms.

### Quantized Resume Points

- Built and deployed a text classification pipeline for eCommerce product categorization, achieving **98%+ accuracy** on real-world data.
- Engineered advanced NLP preprocessing (NLTK, TF-IDF, Word2Vec) and handled class imbalance with SMOTE and stratified sampling.
- Designed, trained, and optimized deep learning models, including ensemble approaches, resulting in a **weighted F1-score of 98.43%**.
- Extracted actionable business insights (e.g., top-selling categories, price correlations) to inform strategic decisions.
- Demonstrated expertise in data science, machine learning, and deep learning for high-impact, production-ready solutions.

You can now review and save the README file in your repository.
