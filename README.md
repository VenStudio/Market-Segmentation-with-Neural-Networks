# Market Segmentation with Neural Networks

---

## Overview

The Market Segmentation with Neural Networks project aims to segment customers based on demographics, behavior, and other relevant criteria using a neural network model. By analyzing the Online Retail Dataset, this project seeks to provide actionable insights for targeted marketing strategies, product development, and customer service enhancements.

## Database

The dataset used in this project can be found on [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data).

## Purpose

This segmentation helps:

- **Targeted Marketing:** Develop personalized marketing strategies to engage different customer segments effectively.
- **Product Development:** Identify customer preferences and develop products that cater to distinct market segments.
- **Customer Service:** Enhance customer service by understanding the specific needs and behaviors of different customer groups.

## Usage

1. **Set Up:** Install the required libraries using:
   ```bash
   pip install numpy pandas scikit-learn tensorflow seaborn matplotlib
   ```
2. **Data Preparation:** Load and preprocess the dataset, handling missing values and outliers, and creating RFM (Recency, Frequency, Monetary) features.
3. **Model Training:** Train the neural network model using the prepared data. Fine-tune the model with hyperparameter tuning, added complexity, and regularization techniques.
4. **Run Evaluation:** Evaluate the model's performance using metrics such as Mean Squared Error (MSE) and R-squared. Apply K-Means clustering to segment the customers based on predicted values.
5. **Analyze Segments:** Review the resulting customer segments and their distinct characteristics to derive insights and recommendations.

## Contributors
**This project was made by**

[Omar (Ven)](https://github.com/VenStudio)

*This project was made for a course from [ElectoPI](https://alcamp.electropi.ai/)*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
