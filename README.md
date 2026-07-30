🎢 Exploratory Data Analysis (EDA) on Amusement Park

This project performs end-to-end Exploratory Data Analysis on a real-world roller coaster dataset to uncover patterns in coaster speed, height, and introduction trends across years and manufacturers.

🛠️ Tools & Libraries

* Python, Pandas, Matplotlib, Seaborn, Scikit-learn

📂 Dataset

* Source: coaster_db.csv (raw, messy real-world data)
* Records: 1,087 roller coasters globally
* Features: Speed, Height, Year Introduced, Location, Manufacturer, Type

🔍 What I Did

* Cleaned raw data: removed duplicates, handled nulls, standardized column names
* Selected 13 relevant features for analysis
* Detected outliers using the IQR method and verified them against real-world coaster records
* Built 6+ visualizations (histogram, KDE, scatter, bar, pairplot, line plot) to extract meaningful insights
* Built a simple linear regression model to predict coaster speed from height

📊 Key Insights

* Strong positive correlation found between coaster speed and height (R² = 0.79 for the regression model)
* Peak coaster construction periods identified between 1999–2002
* Outliers in speed and height detected using the IQR method (5 height, 17 speed) — verified as genuine record-setting coasters rather than data errors

  Key Findings

The dataset is cleaned --removing duplicates, handling null values.
Outlier analysis (IQR method) identified 5 height outliers and 17 speed outliers — representing genuine record-breaking coasters, retained rather than removed.
Coaster height and speed show a strong positive correlation; a simple linear regression predicting speed from height achieved an R² of 0.79.
Construction activity peaked in 1999-2002 in USA.

## Author
**Tushar Sable** — [LinkedIn](https://linkedin.com/in/tushar-sable9/)
