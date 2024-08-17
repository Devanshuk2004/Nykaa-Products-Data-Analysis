# Nykaa Product Analysis README

## About

This project focuses on analyzing product data from the Nykaa platform. The dataset provides valuable insights into pricing strategies, product popularity, and customer preferences. It includes several key fields:

- **Name**: Represents the name or title of the product, including brand name, product name, and sometimes additional details like variant or flavor.
- **Reviews**: Number of reviews a product has received.
- **Offer Price**: The reduced price of a product during a promotional period or when a specific discount is applied.
- **Original Price**: The regular price of the product without any offers or discounts.
- **Discount**: Specifies the percentage or amount of discount applied to the product, indicating the difference between the original price and the offer price.
- **Free Gift**: Indicates whether a free gift is available with the purchase.

## Work Done

### Data Mining:
- Removed unwanted and unnecessary strings from the reviews (e.g., removed "MRP:₹" from the original price, "₹" from the offer price, and "% off" from the discount).
- Dropped null values to ensure a clean and complete dataset.

### Exploratory Data Analysis (EDA):
- Analyzed the correlation between the original price and discount to understand pricing strategies.
- Created a correlation graph for all numeric columns to uncover relationships between variables.
- Generated a distribution plot of the original price to visualize the spread of product prices.
- Added categorical columns to classify products into different categories based on their attributes.

### Machine Learning Models:
- Applied various machine learning algorithms to analyze the dataset:
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Gaussian Naive Bayes (Gaussian NB)

## Repository Structure

- **data**: Contains the raw dataset and processed data files.
- **notebooks**: Jupyter notebooks for data preprocessing, EDA, and model training.
- **models**: Saved models and scripts for training and evaluation.
- **results**: Visualizations, reports, and other output files generated from the analysis.

## Getting Started

1. Clone this repository to your local machine.
2. Ensure you have Python 3.x and the necessary libraries installed (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn).
3. Navigate to the `notebooks` directory and open the Jupyter notebooks to explore the analysis and results.
4. Follow the steps outlined in the notebooks to reproduce the analysis or modify it as needed.

## Contributing

Contributions to this project are welcome! Feel free to fork this repository, make changes, and submit pull requests. For major changes, please open an issue first to discuss proposed updates or improvements.

## Contact

For any questions, suggestions, or issues, please feel free to contact me via email at [your_email@example.com].

Thank you for your interest in the Nykaa Product Analysis project! I hope you find the insights generated from the analysis valuable.
