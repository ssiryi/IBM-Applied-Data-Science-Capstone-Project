# 🚀 IBM Data Science Professional Certificate - Capstone Project

Hi there! 👋 This repository contains my final project for the **IBM Data Science Professional Certificate** on Coursera. This was the last step in a 10-course journey, and honestly, it was the most challenging but exciting part!

## 📄 Project Overview

The main goal of this project was to analyze SpaceX launch data and predict whether the Falcon 9 first stage will land successfully. SpaceX saves a lot of money by reusing these stages, so knowing the outcome in advance is huge for estimating launch costs.

I went through the whole data science pipeline: from collecting data to building machine learning models.

**Course Link:** [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science)

---

## 📂 What's in this repo?

Here is the breakdown of the assignments I completed (step-by-step):

### 1. Data Collection (API)
* **File:** `1_spacex_data_collection_api.ipynb`
* **What I did:** Requested data from the SpaceX API. It was cool to pull real-world data and convert it into a Pandas dataframe for analysis.

### 2. Web Scraping
* **File:** `2_webscraping_spacex_launches_from_wikipedia.ipynb`
* **What I did:** Scraped Falcon 9 launch records from Wikipedia using `BeautifulSoup`. Sometimes APIs don't have everything, so this was a good practice in getting data from HTML tables.

### 3. Data Wrangling
* **File:** `3_spacex_data_wrangling.ipynb`
* **What I did:** Cleaned the data. Checked for null values and converted categorical variables (like orbit types) into dummy variables (One-Hot Encoding) so the models could understand them.

### 4. EDA with Visualization
* **File:** `4_eda_data_visualization.ipynb`
* **What I did:** Used `Matplotlib` and `Seaborn` to find patterns. For example, looking at how Payload Mass affects the launch success rate.

### 5. EDA with SQL
* **File:** `5_eda_using_sql.ipynb`
* **What I did:** Loaded the dataset into a database and wrote SQL queries to answer specific questions, like "Which launch sites have the most success?".

### 6. Maps with Folium
* **File:** `6_launch_site_location_visualization_with_folium.ipynb`
* **What I did:** Visualized launch sites on an interactive map. I analyzed proximity to coastlines and railways to understand why launch sites are located where they are.

### 7. Interactive Dashboard
* **File:** `7_spacex_data_intereactive_dashboard_app.py`
* **What I did:** Built a dashboard using **Plotly Dash**. This allows users to filter launches by site and payload mass to see success rates dynamically.
* *Note: You need to run this python script to see the app locally.*

### 8. Machine Learning Prediction
* **File:** `8_spacex_machine_learning_prediction.ipynb`
* **What I did:** The fun part! I built a pipeline to train four different models:
    * Logistic Regression
    * Support Vector Machine (SVM)
    * Decision Tree
    * K-Nearest Neighbors (KNN)
    * *Result:* I compared their accuracy to find the best one.

### 9. Final Report
* **File:** `9_SpaceX_first_stage_landing_report.pdf` (converted from .pptx)
* **What I did:** Summarized the whole journey and key findings in a presentation.

---

## 🛠 Technologies Used
* **Languages:** Python, SQL
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Folium, Plotly Dash, Scikit-learn, BeautifulSoup, Requests.

---

## 🏁 Conclusion
This project really helped me understand how all the pieces of Data Science fit together. It's not just about modeling, but a lot about cleaning data and understanding the business problem (saving costs for SpaceX).

Feel free to check out the notebooks! If you have any questions or feedback, let me know. 🚀
