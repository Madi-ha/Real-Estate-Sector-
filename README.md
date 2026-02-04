🏠 AI Real Estate Intelligent Assistant
An intelligent system built to assist home buyers and real estate investors by estimating property prices, analyzing market value (Overpriced vs. Underpriced), and identifying key price drivers using machine learning.

🚀 Features
Price Estimation: Predicts property value based on 17 features including location, carpet area, and amenities.

Market Analysis: Automatically classifies properties as Overpriced, Fair, or Underpriced based on a ±10% deviation from the predicted market value.

Feature Importance: Identifies which factors (e.g., number of windows, carpet area, number of balconies) most heavily influence property prices in the dataset.

Neighborhood Insights: Provides localized summaries of average pricing and listing counts for specific cities.

📊 The Model
The project utilizes a Random Forest Regressor with 200 estimators.

Performance: The model achieved an R² Score of 0.996, indicating a high level of accuracy on the test set.

Top 3 Price Drivers:

window_no (28.5%)

carpet_area (18.5%)

balcony (18.3%)
