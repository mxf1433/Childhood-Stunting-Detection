# Childhood-Stunting-Detection

Childhood stunting is a critical global health issue affecting children under the age of five, particularly in low-income and developing countries. Stunting, reflecting chronic malnutrition, indicates inadequate physical and cognitive development, leading to long-term health and societal consequences. According to the WHO, approximately 150 million children under five were estimated to be stunted in 2021, with 98% residing in low- and middle-income countries.

Objective
This study aims to predict stunting in toddlers based on factors of  height, gender, and age. Leveraging machine learning techniques, we seek to identify significant predictors of stunting and develop a model to classify toddlers into four categories, from severely stunted to tall. This research is crucial for better understanding the determinants of stunting and developing targeted interventions to address this public health issue.

Dataset
The "Stunting Toddler (Balita) Detection" dataset, obtained from Kaggle, contains 121,000 rows of data, including age, sex, height, and nutritional status of toddlers. The dataset is based on the WHO z-score formula for stunting detection in children under five, with no missing values.

Methodology
The dataset was imported and cleaned, with columns relabeled and missing values checked. One-hot encoding was applied to the Gender column, and Age_month and Height_cm columns were scaled. Summary statistics were calculated, and a bar plot was created to visualize the distribution of Nutritional_status categories in the dataset.

Conclusion
Machine learning offers a powerful approach to analyze large datasets efficiently and accurately, identifying subtle patterns and interactions among variables. By predicting stunting in toddlers, we can improve the effectiveness of nutritional interventions and enhance the health and well-being of children worldwide.

Note: The dataset used in this study is not included in this repository. To access the dataset, please visit the Kaggle website https://www.kaggle.com/datasets/rendiputra/stunting-balita-detection-121k-rows/data
