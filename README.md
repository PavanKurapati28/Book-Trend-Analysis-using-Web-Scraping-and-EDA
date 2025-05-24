📚 Book Trend Analysis using Web Scraping & EDA

🔍 Project Overview
This project demonstrates the complete data pipeline of web scraping, data cleaning, analysis, and dashboard visualization using data from a book listing website (Books to Scrape). The aim is to derive meaningful insights from the books catalog and visualize them using Power BI.

🛠️ Technologies Used
Python (Data Collection & Processing)

Libraries:

requests and BeautifulSoup for web scraping

pandas for data manipulation

Power BI for interactive data visualization

Jupyter Notebook for development

📥 Data Collection
Website: Books to Scrape

Scraped Data (20 pages totaling 1000 books):

Title

Price (in £)

Stock Availability

Star Rating

Product Page URL

Genre (Category)

Description (from product pages)

🧹 Data Cleaning & Processing
Extracted numeric price values from strings

Parsed stock availability into quantity

Converted star rating text into numeric (1–5)

Cleaned descriptions and handled missing data

Standardized genre values and removed null entries

📊 Key Power BI Visualizations
The final dataset was visualized using a Power BI dashboard, containing the following elements:

🚩 Summary Cards
Number of Books: 1000

Average Price: £35.07

Total Genres: 50

📈 Charts & Visuals
Price Distribution of Books
Bar chart showing how book prices are distributed across price ranges.

Count of Each Rating (1–5)
Frequency distribution of books by star rating.

Average Rating by Genre
Horizontal bar chart displaying the average rating per book genre.

Top 20 Genres by Number of Books
Most populated genres based on number of books.

Count of Book URLs by Genre
Total book entries available for each genre.

Count of Book URLs by Availability
Book count grouped by their availability status.

Count of Availability by Genre
Pie chart showing how available books are distributed among genres.

📁 Repository Contents
Web Scraping Project(Books-1).ipynb – Full notebook with code, data scraping, cleaning, and insights

Books_Dashboard.pbix – Power BI dashboard file

README.md – Project summary and usage guide

🧠 Key Learnings
Built a complete data pipeline from web scraping to visual insights

Practiced working with unstructured HTML data and turning it into structured datasets

Enhanced skills in Power BI for designing informative dashboards

Gained experience with real-world project structuring and storytelling through data
