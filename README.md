# smartwatches-market-analysis-
# 🕒 Smartwatch Market Analysis – Flipkart  

## 📘 Project Overview  

The **Smartwatch Market Analysis – Flipkart** project is a comprehensive data analytics case study focused on understanding the smartwatch market landscape using real-time e-commerce data scraped from **Flipkart**. The objective is to perform a full-cycle data analysis — starting from **web scraping** raw data, performing **data cleaning and preprocessing**, and moving toward **exploratory data analysis (EDA)** and **insight visualization**.  

The smartwatch market has witnessed rapid growth in India, driven by increasing health awareness, fitness tracking, and integration with smartphones. This project aims to highlight the **most influential factors behind smartwatch sales**, **price trends**, **brand positioning**, and **consumer preferences** through structured data analysis.  

---

## 🎯 Objectives  

The main goals of this project are to:  
1. **Collect** smartwatch product data from Flipkart using web scraping techniques.  
2. **Clean** and preprocess raw data to ensure accuracy and consistency.  
3. **Analyze** pricing patterns, customer ratings, and brand performance.  
4. **Visualize** insights using graphs and charts for better interpretation.  
5. **Identify** factors that impact smartwatch popularity and pricing.  
6. **Deliver** actionable insights for consumers, marketers, and data enthusiasts.  

---

## 🧰 Tech Stack  

| Category | Tools / Libraries Used |
|-----------|------------------------|
| **Language** | Python |
| **Web Scraping** | BeautifulSoup / Playwright / Selenium |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Environment** | Jupyter Notebook / PyCharm |
| **Version Control** | Git & GitHub |

---

## 🔎 Data Collection  

Data was collected directly from the **Flipkart website** using **web scraping**. The scraping process focused on extracting essential details for each smartwatch listing, including:  

- Product name  
- Brand  
- Price  
- Discount percentage  
- Ratings and number of reviews  
- Key specifications (Bluetooth, Display type, Battery life, etc.)  

A structured scraping pipeline was developed using **Python’s BeautifulSoup** and **Playwright** to handle dynamic pages, ensuring accurate data retrieval from multiple Flipkart result pages.  

The scraped dataset was stored in CSV format under:  
`/data/Flipkart_Smartwatches_Raw.csv`  

---

## 🧹 Data Cleaning and Preprocessing  

The raw dataset required significant cleaning to prepare it for analysis. The following transformations were applied:  

- **Removed duplicates** and irrelevant entries.  
- **Standardized brand names** to maintain consistency (e.g., “Noise Smartwatch” → “Noise”).  
- **Converted price values** from string (₹XX,XXX) to integer.  
- **Handled missing ratings** using median imputation.  
- **Parsed feature strings** (like “Bluetooth, Heart Rate Monitor”) into separate boolean columns.  
- **Extracted numerical data** (e.g., review counts, rating averages) for correlation analysis.  

After cleaning, the processed dataset was saved as:  
`/data/Flipkart_Smartwatches_Final.csv`  

---

## 📊 Exploratory Data Analysis (EDA)  

EDA was performed using **Pandas**, **Matplotlib**, and **Seaborn** to uncover insights from the cleaned dataset.  

### Key Analytical Questions:  
1. What is the **price distribution** of smartwatches on Flipkart?  
2. Which **brands** dominate the smartwatch market?  
3. Is there a correlation between **price and customer rating**?  
4. What are the **most common features** in top-rated smartwatches?  
5. Which **price segment** offers the best value for customers?  

### Major Visualizations:  
- **Price Distribution Plot:** Showed that most smartwatches fall within ₹1,500–₹5,000.  
- **Brand Comparison Bar Chart:** Revealed that brands like **Noise**, **boAt**, and **Fire-Boltt** dominate the market share.  
- **Rating vs. Price Scatterplot:** Displayed weak correlation, suggesting that higher price doesn’t always guarantee better satisfaction.  
- **Feature Frequency Heatmap:** Showed that Bluetooth connectivity and AMOLED displays are highly common in top-rated products.  

All visual outputs were exported to the `/visuals/` directory, including:  
- `price_distribution.png`  
- `brand_comparison.png`  
- `rating_correlation.png`  

---

## 📈 Insights and Findings  

After performing in-depth EDA, several insights were identified:  

1. **Dominant Price Range:**  
   Most smartwatches are priced below ₹5,000, indicating strong demand for affordable options in India’s growing wearable market.  

2. **Top Brands:**  
   Brands like **Noise**, **boAt**, and **Fire-Boltt** collectively capture the majority of listings. Their dominance can be attributed to aggressive pricing and marketing strategies.  

3. **Ratings and Reviews:**  
   Smartwatches with more than 4.0 average ratings usually emphasize battery life and fitness tracking features.  

4. **Features Impact on Price:**  
   Advanced specifications like AMOLED display, voice assistant support, and longer battery life significantly increase the price bracket.  

5. **Customer Preference Trends:**  
   Customers prefer smartwatches that offer multi-sport tracking, lightweight design, and better display clarity rather than high-end premium models.  

6. **Correlation Patterns:**  
   Although higher-priced watches tend to have slightly better ratings, **affordable models** are more popular due to their value-for-money proposition.  

---

## 🧠 Learning Outcomes  

This project helped in mastering several **data science and analytics concepts**, including:  

- Building **web scraping pipelines** for dynamic websites.  
- Applying **data cleaning and wrangling** techniques.  
- Performing **EDA** to extract actionable insights.  
- Creating **data visualizations** to communicate findings clearly.  
- Managing end-to-end workflow — from raw data to decision-oriented insights.  
 


