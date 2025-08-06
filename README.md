🛍️ Myntra Product Analysis & Rating Prediction
This project showcases the full lifecycle of a data science project using real-world data from Myntra, a leading fashion e-commerce platform in India. The project involves:

🔍 Web Scraping product data using Selenium

📊 Data Analysis & Visualization using Pandas, Matplotlib, Seaborn, and Plotly

🤖 Machine Learning Models to predict product ratings

📈 Evaluation & Insights for business-driven decisions

📁 Project Structure
bash
Copy
Edit
myntra-project/
│
├── data/                   # Contains raw and cleaned datasets
├── notebooks/              # Jupyter notebooks for EDA, visualization, and ML
├── models/                 # Saved models (optional)
├── images/                 # Graphs and plots generated from the data
├── README.md               # Project documentation
├── requirements.txt        # Required libraries
└── main.py                 # Project's main runner script (if applicable)
🛠️ Technologies Used
Web Scraping
selenium

webdriver

time.sleep() for throttling requests

Data such as product name, brand, rating, price, discount, etc., were scraped directly from the Myntra website.

Data Analysis
pandas for data wrangling

numpy for numerical operations

matplotlib, seaborn, and plotly for visualization

Visualizations
Bar charts, box plots, and histograms to analyze:

Rating distribution

Brand-wise pricing

Discount analysis

Top-rated and top-discounted products

Machine Learning
To predict Product Ratings, the following models were trained and evaluated:

RandomForestClassifier

LogisticRegression

SVM (Support Vector Machine)

KNeighborsClassifier

🚀 Results & Insights
✅ Random Forest outperformed others in terms of accuracy and stability.

📉 Pricing and discount patterns vary heavily between brands.

⭐ Most products fall between 3.5 to 4.5 in user ratings.

📌 Future Work
Deploy the model as a Flask or Streamlit web app

Automate web scraping using schedulers (e.g., cron, Airflow)

Expand to include user review sentiment analysis


