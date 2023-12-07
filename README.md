# Data-Science-Golden-Task-Number-2-Price-Recommendation-for-Online-Sellers-by-CodeClause
The "PRICE RECOMMENDATION FOR ONLINE SELLERS" project is a comprehensive solution designed for online sellers to optimize their product pricing strategies. 

# Price Recommendation for Online Sellers

## Introduction
The "Price Recommendation for Online Sellers" project, developed by **GOLTHI MADHU APPALA NARASIMHA** as part of the CodeClause Internship on Data Science, is a sophisticated solution aimed at assisting online sellers in optimizing their product pricing strategies. Leveraging machine learning, specifically XGBoost Regression, the code predicts optimal prices based on various factors such as previous reviews, ratings, discounted prices, and product details.

## Project Overview
### Files Included:
1. `Price_Recommendation_For_Online_Sellers.py`: Python script containing the code for data preprocessing, XGBoost Regression model training, and GUI implementation.
2. `amazon.csv`: Amazon products dataset used for price recommendation.
3. `README.md`: This readme file providing an overview of the project.

### Dependencies:
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- NLTK (Natural Language Toolkit)
- Tkinter (for GUI)

### Usage:
1. Run the `Price_Recommendation_For_Online_Sellers.py` script to launch the GUI.
2. Input product details, including discounted prices, ratings, and reviews.
3. Click the "Recommend Price" button to obtain the predicted optimal price.
4. Review the recommended price displayed on the GUI.

## Project Structure
1. **Data Preprocessing:**
   - Handling missing values.
   - Removing unnecessary features.
   - Processing text data, including tokenization, stemming, and TF-IDF vectorization.

2. **XGBoost Regression Model:**
   - Splitting the dataset into dependent and independent features.
   - Training the XGBoost Regressor on the training set.
   - Evaluating the model on the test set using performance metrics.

3. **Graphical User Interface (GUI):**
   - Developing a user-friendly interface using Tkinter.
   - Inputting product details via text fields.
   - Utilizing the trained model to predict and display recommended prices.
   - Enabling non-technical users to leverage machine learning for pricing decisions.

### GUI Explanation:
The Graphical User Interface (GUI) serves as a central component of this project, providing an intuitive platform for users to interact with the price recommendation system. Here's a breakdown of the GUI's functionality:

- **Product Details Input:**
  - Users can input relevant product details such as product name, category, discounted price, discount percentage, rating, rating count, about product details, review title, and review content.

- **Recommend Price Button:**
  - Clicking the "Recommend Price" button triggers the system to utilize the trained XGBoost Regression model to predict the optimal price based on the provided product details.

- **Predicted Price Display:**
  - The recommended price is then displayed on the GUI, providing users with actionable insights for making informed pricing decisions.

- **User-Friendly Design:**
  - The GUI is designed with simplicity in mind, ensuring that even users without a background in data science can easily navigate and benefit from the price recommendation system.

## Conclusion
The "Price Recommendation for Online Sellers" project showcases the integration of advanced machine learning techniques with a user-friendly GUI to empower online sellers in making informed pricing decisions. The GUI's accessibility makes it a valuable tool for sellers, even those without a background in data science, to optimize their product pricing strategies.
