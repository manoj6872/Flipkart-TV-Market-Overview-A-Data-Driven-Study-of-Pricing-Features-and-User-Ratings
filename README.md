# Flipkart-TV-Market-Overview-A-Data-Driven-Study-of-Pricing-Features-and-User-Ratings

📊 Flipkart TV Market Overview: A Data-Driven Study of Pricing, Features, and User Ratings This project analyzes the Flipkart TV market using web scraping and exploratory data analysis (EDA). The dataset, collected from Flipkart listings, includes details like brand, price, screen size, resolution, ratings, and reviews. After cleaning and preprocessing, insights were derived on pricing trends, brand popularity, and customer preferences. The findings highlight how features and ratings influence consumer choices in the online TV market.

# 🧠 Objective
- Best-selling TV brands
- Price segments
- Key product features (screen size, resolution, smart features)
- Customer feedback (ratings and reviews)


# 🔧 Technologies & Libraries Used 
- Python Web Scraping: BeautifulSoup, requests, re (Regular Expressions)
- Data Manipulation: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn

# 🌐 Web Scraping Details
- Source: Flipkart TV Listings
- Data Extracted: Product name, brand, price, rating, reviews, resolution, screen size, and features.
- Total Records Scraped: 455 rows × 9 columns (raw data)

# 🧼 Data Cleaning Steps
- Handling missing values and duplicates
- Standardizing inconsistent formats
- Correcting data types
- Extracting structured info from text

# 📈 Exploratory Data Analysis
🔹 Univariate Analysis
- Frequency distribution of brands and screen sizes
- Most popular screen size: 32 inches
- Most common brand: InnoQ
  
🔹 Bivariate Analysis
- Relationship between brand and resolution
- HD Ready is the most common resolution
- Higher screen size has better ratings
  
🔹 Multivariate Analysis
- Correlation between price, ratings, reviews
- Price & screen size: moderate positive correlation
- Ratings don’t always increase with price

# 💡 Key Insights
- TVs in the ₹20,000–₹60,000 price range are the most preferred.
- Full HD and HD Ready models deliver comparable satisfaction levels.
- QLED TVs receive slightly higher ratings but come at a premium price.
- Mid-sized LED TVs provide the best balance of value and performance.
- Customer ratings show a positive correlation with the number of reviews

# ❓ Business Questions Answered
- Which brands are most popular?
- What price range is most preferred?
- How do screen size and resolution impact pricing?
- Do higher-rated TVs cost more?
- What features influence customer choices?
- How does launch year affect pricing and demand?
  
# Conclusion
- This project highlights how data science can extract actionable business insights from e-commerce product listings. The findings can assist Flipkart and similar platforms in optimizing inventory management and developing customer-focused marketing strategies.
