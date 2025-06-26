# Ecommerce Product Categorization

This repository contains the solution to the **Ecommerce Product Categorization** challenge. The project focuses on developing an efficient text classification model to categorize eCommerce products based on their descriptions.

## Resume Highlights (XYZ Storytelling)

- Improved eCommerce product categorization accuracy to 98.44% (F1 Score: 98.43%) by developing and fine-tuning deep learning models (Sequential Model, Random Classifier) on real-world product data.
- Enhanced class balance and model robustness by implementing stratified sampling and SMOTE oversampling, resulting in high precision and recall across all product categories.
- Automated text preprocessing pipeline using NLTK, TF-IDF, and Word2Vec, enabling scalable and efficient feature extraction from raw product descriptions.
- Identified key business insights (e.g., top-selling categories, price correlations) through exploratory data analysis, supporting data-driven decision-making for eCommerce strategy.
- Reduced search friction and improved customer experience by deploying a high-accuracy categorization model, increasing product discoverability and reducing abandoned sessions.

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

You can now review and save the README file in your repository.
