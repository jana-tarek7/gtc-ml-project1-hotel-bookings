# gtc-ml-project1-hotel-bookings

Hotel Bookings: Data Cleaning, Preprocessing & EDA
This project focuses on data cleaning, preprocessing, and exploratory data analysis (EDA) using the Hotel Bookings dataset. The aim is to prepare the data for further modeling and to uncover insights about customer booking behavior, cancellations, and seasonal trends.

📂 Project Structure
Project1.ipynb → Jupyter Notebook with cleaning, preprocessing, and EDA steps.
hotel_bookings.csv → Raw dataset used for analysis.

🛠️ Workflow
1. Data Cleaning & Preprocessing
Handling missing values
Removing duplicates
Data type conversions
Feature renaming for clarity
Encoding categorical variables (if needed)
Outlier detection & treatment

2. Exploratory Data Analysis (EDA)
Overview of dataset structure (head, info, describe)
Univariate analysis (distribution of features)
Bivariate/multivariate analysis

3. Feature Engineering
New features were created to enrich the dataset:
total_guests = adults + children + babies
total_nights = stays_in_weekend_nights + stays_in_week_nights
is_family = Binary flag (Yes/No) indicating if the booking includes children or babies

⚙️ Requirements
Install dependencies before running the notebook:
pip install pandas numpy matplotlib seaborn


📈 Key Insights (Examples)
Cancellations are strongly linked with lead time and deposit type.
City hotels receive more bookings compared to resort hotels.
Seasonal trends reveal peaks in bookings during summer months.
Data preprocessing reduces noise and prepares the dataset for predictive modeling.

📌 Future Work
Apply machine learning models to predict cancellations.

Create interactive dashboards for real-time hotel analytics.

🙌 Acknowledgments
