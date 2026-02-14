# OIBSIP_data_analytics

# Data Analytics Internship Portfolio - Oasis Infobyte


##  Project Track 1: Retail & Real Estate Analytics

### Level 1: EDA on Retail Sales Data
**Objective:** Perform a deep-dive Exploratory Data Analysis (EDA) on retail transaction data to uncover shopping patterns.
- **Key Actions:** Cleaned missing values, analyzed sales by category, and visualized peak transaction times.
- **Tools:** Pandas, Matplotlib, Seaborn.
- **Outcome:** Identified high-revenue product categories and customer demographic trends.

### Level 2: Predicting House Prices
**Objective:** Build a regression model to estimate property values based on various features.
- **Methodology:** Handled categorical variables (Furnishing Status), treated outliers using IQR, and performed feature scaling.
- **Model:** Multiple Linear Regression.
- **Dataset:** `Housing.csv`


##  Project Track 2: Marketing & Quality Analysis

### Level 1: Customer Segmentation
**Objective:** Use unsupervised learning to group customers based on their annual income and spending behavior.
- **Technique:** Applied **K-Means Clustering** and determined the optimal number of groups using the **Elbow Method**.
- **Insight:** Created 4 distinct segments (VIP, Standard, Target, and Careless) for personalized marketing.
- **Dataset:** `Dataset.csv` 

### Level 2: Wine Quality Prediction
**Objective:** Predict the quality of wine using its chemical properties.
- **Methodology:** Treated as a classification problem, grouping scores into "Good" and "Average" categories.
- **Model:** **Random Forest Classifier**.
- **Key Drivers:** Alcohol content and Volatile Acidity were identified as the strongest predictors of quality.
- **Dataset:** `WineQT.csv`


## Project Track 3: NLP & Market Insights

### Level 1: Sentiment Analysis
**Objective:** Analyze and classify 160,000+ tweets to determine public sentiment regarding specific topics.
- **Methodology:** Preprocessed text data using **TF-IDF Vectorization** (Unigrams & Bigrams).
- **Model:** Optimized **Logistic Regression** for high-speed classification.
- **Categories:** Positive (1), Neutral (0), and Negative (-1).
- **Dataset:** `Twitter_Data.csv`

### Level 2: Google Play Store Analysis
**Objective:** Conduct a comprehensive analysis of the mobile app market by combining app metadata with user feedback.
- **Methodology:** Merged `apps.csv` and `user_reviews.csv` to map technical ratings against emotional sentiment.
- **Analysis:** Explored **Sentiment Polarity** to compare the user experience between Free and Paid applications.
- **Dataset:** `apps.csv` + `user_reviews.csv`

##  Technical Stack
- **Languages:** Python 3.12
- **Data Processing:** Pandas, NumPy
- **Visualizations:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn, Statsmodels
- **Environment:** Google Colab

##  Usage
1. Upload the required `.csv` datasets to your working directory.
2. Ensure the filenames in the code match the uploaded files (e.g., `Dataset.csv`, `WineQT.csv`).
3. Run the Jupyter Notebooks to view the generated tabular summaries, statistical models, and plots.

**Intern:** Kishor A  
**Organization:** Oasis Infobyte  
**Internship Track:** Data Analytics
