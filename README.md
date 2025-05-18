Contributors: Zibing Wang, Yuting Feng, Nanxi Wang, Chunjiang Li 

📊 Crystal Market Trends Analysis
This repository contains Python scripts for analyzing market trends in the crystal industry. It includes Google Trends data extraction, sentiment analysis, NLP keyword extraction, and data visualization to identify popular crystal-related keywords and customer preferences.

🚀 Features
✔ Extract Popular Keywords from Reddit comments on crystal-related discussions.
✔ Google Trends Analysis to check real customer search interest.
✔ Sentiment Analysis to understand how people feel about different keywords.
✔ Word Cloud & Data Visualizations for better insights.
✔ Comparison with Amazon & Etsy product listings for real-world commercial impact.
✔ Optional AWS Integration for large-scale analysis.

📂 Project Structure
📁 CrystalMarket_Analysis
│── 📄 README.md               # Project documentation
│── 📄 requirements.txt        # Dependencies
│── 📄 crystal_analysis.ipynb  # Jupyter Notebook with NLP & sentiment analysis
│── 📄 google_trends.py        # Fetch Google Trends data
│── 📄 amazon_scraper.py       # Scrape product keywords from Amazon
│── 📄 sentiment_analysis.py   # Analyze keyword sentiment
│── 📄 visualization.py        # Generate graphs & word clouds
│── 📂 data/
│   ├── reddit_comments.csv    # Scraped Reddit data
│   ├── google_trends.csv      # Google Trends data
│   ├── amazon_keywords.csv    # Amazon product titles
│── 📂 images/
│   ├── wordcloud.png          # Generated word cloud
│   ├── sentiment_chart.png    # Sentiment trend graph

1️⃣ Clone the Repository
git clone https://github.com/ChunjiangLiLeo/CrystalMarket.git
cd CrystalMarket

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Scripts
📊 Google Trends Analysis
python google_trends.py

📝 Sentiment Analysis
python sentiment_analysis.py

🎨 Visualizations
python visualization.py

📌 Usage
1️⃣ Extract and analyze Reddit discussions to find trending words.
2️⃣ Compare Google Trends search data to validate customer interest.
3️⃣ Check sentiment polarity to prioritize words for marketing.
4️⃣ Use the word cloud & bar graphs for SEO & product naming strategies.
5️⃣ (Optional) Extend the project using AWS Comprehend for large-scale NLP.

🛠️ Future Enhancements
✅ Automate weekly data collection & visualization updates.
✅ Expand to include Etsy & Shopify data for better e-commerce insights.
✅ Add real-time tracking of trends with Google Trends API automation.

Contributing
We welcome contributions! Follow these steps to contribute:

Fork the repository
Create a feature branch
git checkout -b new-feature
git commit -m "Added new analysis method"
git commit -m "Added new analysis method"
git push origin new-feature

Open a Pull Request
 License
This project is licensed under the MIT License. See LICENSE for details.

✨ Credits & Acknowledgments
🔗 Google Trends API
🔗 PRAW (Reddit API)
🔗 Amazon Product Scraper
🔗 NLTK Sentiment Analysis

